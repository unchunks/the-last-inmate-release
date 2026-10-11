![総ダウンロード数](https://img.shields.io/github/downloads/unchunks/the-last-inmate-release/total?label=総ダウンロード数&color=blue&style=social)

# The Last Inmate（開発中のテスト版）

**光を求め、音に怯える。**

目の退化した異形たちが、音だけを頼りに獲物を追う地下監獄。足音も物音も、すべてが波紋になって闇に広がる。その波紋は敵の居場所を教えてくれるが、同時にあなたの居場所を敵に知らせる。地上への脱出を目指す、一人称のリアルタイム・ローグライクホラー。捕まっても、次の囚人に道具を 1 つだけ遺せる。

開発中のテスト版です。内容は変わります。不具合や感想を [Issues](https://github.com/unchunks/the-last-inmate-release/issues) で教えてもらえると助かります。

## ダウンロード

最新版は [Releases](https://github.com/unchunks/the-last-inmate-release/releases/latest) から。

| 版 | Windows | Android |
|---|---|---|
| v0.4.2 | [TheLastInmate_Phase4_v0.4.2.zip](https://github.com/unchunks/the-last-inmate-release/releases/download/v0.4.2/TheLastInmate_Phase4_v0.4.2.zip) | [TheLastInmate_Phase4_v0.4.2.apk](https://github.com/unchunks/the-last-inmate-release/releases/download/v0.4.2/TheLastInmate_Phase4_v0.4.2.apk) |

**ヘッドホンで遊んでください。** 音の方向がわからないと遊べません。暗いゲームなので、部屋を暗くするのがおすすめです。

### 動く環境

- Windows：Windows 10 / 11（64bit）、DirectX 12 に対応した GPU
- Android：Android 7.1 以上、64bit（ARM64）、Vulkan に対応した端末。横向きで遊びます

## 遊び方

### Windows

1. zip をダウンロードして、好きな場所に展開する
2. 中の `TheLastInmate.exe` を起動する
   - 「Windows によって PC が保護されました」と出たときは、「詳細情報」→「実行」を選ぶ（署名のないテスト版のため）
3. 初めて起動すると明るさの調整の画面が出るので、「かろうじて見えるマーク」が見えるところまで合わせる
4. タイトルで「はじめる」を選ぶ。初めてなら短いチュートリアルから始まる

`licenses` フォルダ（使っているソフトウェアのライセンス表記）は消さないでください。

### Android

1. 端末で apk をダウンロードする
2. ファイルマネージャーなどで apk を開き、「インストール」を選ぶ
   - 「不明なアプリのインストール」が許可されていないと出たときは、設定でそのアプリに「この提供元のアプリを許可」をオンにする
3. インストールが終わったら起動する。安全のため、「不明なアプリのインストール」の許可は元に戻しておくのがおすすめ

画面の左側のスティックで移動し、右側をドラッグして見回します。ボタンは画面に出ます。

### 操作（Windows）

| 操作 | キーボード・マウス |
|---|---|
| 移動 / 見回す | WASD / マウス |
| 走る | Shift（押している間） |
| しゃがむ | C |
| 深呼吸（目を閉じて落ち着く。その間は動けない） | 右クリック長押し |
| 懐中電灯 | Q |
| 拾う・ドアを静かに開ける・ロッカーに隠れる | E（長押し） |
| ドアを蹴破る・バールでこじ開ける | F |
| 選んでいるアイテムを使う（投げる・飲む） | 左クリック |
| スロットの切り替え | 1〜3 / ホイール |
| 捕まったとき、次の囚人のために隠すアイテムを選ぶ | 1〜3 |
| 一時停止（設定・タイトルに戻る・終了） | Esc |

ゴールは、出口（緑の灯りと EXIT の札のあるドア）にたどり着くことです。それ以外は、遊びながら見つけてください。

## テスト版について

- 捕まったあとに「今の死は理不尽でしたか？」と出ます。1（Y）で「はい」、2（N）で「いいえ」です。答えなくても 20 秒で先へ進みます（スマートフォンでは出ません）
- プレイの記録（懐中電灯を点けていた時間、捕まった場所など）が、遊んでいる PC の中だけに保存されます。どこにも送られません
  - Windows の保存先：`%USERPROFILE%\AppData\LocalLow\DefaultCompany\the-last-inmate\playtest.jsonl`
  - 感想と一緒にこのファイルを Issues に添付してもらえると、調整にとても役立ちます（添付は任意です）

## 不具合・感想

[Issues](https://github.com/unchunks/the-last-inmate-release/issues) に書いてください。不具合のときは、次のことがわかると助かります。

- 版（ダウンロードしたファイル名の v0.4.2 など）
- Windows / Android と、PC・端末の機種
- 何をしたら、どうなったか
- Windows で落ちたときは `%USERPROFILE%\AppData\LocalLow\DefaultCompany\the-last-inmate\Player.log`

## クレジット

ゲームの中のクレジット（タイトルの「クレジット」）と同じ内容です。

モデル・アニメーション

- "Modular 3D hospital environment" by Madd Game Art — [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- "Metal Food Tray" by Kami Rapacz — [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- Abandoned Asylum — Lukas Bobor
- Abandoned Factory (Lite) — Tirgames assets
- Zombie Monster Animations FREE — Kevin Iglesias
- MC Sample - Believable 3D Animations — Mocap Central
- Blood Decals - 3 Free Realistic PBR Decals — Weasel Whistle

音

- 効果音ラボ
- 無料効果音で遊ぼう！（小森平）
- Pixabay — hasin2004
- Freesound（CC0）の素材

ソフトウェア・フォント

- Steam Audio — © Valve Corporation, Apache License 2.0
- URP Volumetric Fog — © Cristian Qiu Félez, MIT License
- Noto Sans JP — © 2014-2021 Adobe, SIL Open Font License 1.1
- Made with Unity

各ライセンスの全文は、Windows 版の `licenses` フォルダにあります。

---

© 2026 unchunks. このリポジトリはビルドの配布用です。ゲームのビルドの再配布・改変はご遠慮ください。

---

## English

**The Last Inmate** is a first-person real-time roguelike horror game (work in progress). Creatures with degenerated eyes hunt by sound alone. Every footstep and every noise spreads through the dark as a visible ripple, showing you where they are and telling them where you are. Escape the underground prison; if you are caught, leave one item behind for the next inmate.

- Download the latest build from [Releases](https://github.com/unchunks/the-last-inmate-release/releases/latest): Windows (zip, 64-bit) or Android (apk, ARM64, Vulkan, Android 7.1+).
- **Headphones are required.**
- Windows: unzip and run `TheLastInmate.exe`. If SmartScreen appears, choose "More info" → "Run anyway" (the test build is unsigned).
- This is a test build. A local play log (`playtest.jsonl`) is saved on your PC only and never sent anywhere. Bug reports and feedback are welcome in [Issues](https://github.com/unchunks/the-last-inmate-release/issues).
