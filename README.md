# Movie01 / PV01 採用版のBlender

家の間取り・家具、職場の室内、過去編の川岸や地形、人物や物の配置、カメラ、アニメーションを含むBlender **5ファイル**です。目覚ましのBlender採用版1件と、採用・保存動画への実入力4件を収録しています。

## 別PCで同じ景色・配置を開く

1. **[Blender一式のZIPをダウンロード](https://github.com/tontoon99/movie01-blender-selected/blob/main/downloads/Movie01-Blender-selected.zip?raw=true)**して解凍し、`Movie01-Blender-selected/START-HERE.html` を開きます。
2. **Blender 5.2.1 LTS**を起動し、「File → Open」で表の.blendを開きます。画面上部のScene欄を、表のシーン名に合わせます。
3. 「View → Cameras → Active Camera」で同じカメラの画角を表示し、タイムラインで動きを確認します。編集時は作業用コピーへ保存します。

| 場面 | 開くBlender | 選ぶシーン |
|---|---|---|
| 職場・会議の輪に座る | [`PV01-SHOT04-background-natural-v10-4s.blend`](blender/scenes/modern-office-b-20260916/shot04-blender-background-natural-v10-20260920/PV01-SHOT04-background-natural-v10-4s.blend) | `01_SHOT04_CAMERA_TRAVEL` |
| 職場・発言のタイミングを逃す | [`PV01-SHOT05-delayed-gesture-v4.blend`](blender/scenes/modern-office-b-20260916/shot05-delayed-gesture-v4-20260920/PV01-SHOT05-delayed-gesture-v4.blend) | `01_SHOT05_PROFILE_REVEAL_FOCUS` |
| 目覚ましを止める | [`PV01-bedroom-alarm-adopted-v17B.blend`](blender/scenes/morning-bedroom-two-shots-20260923/adopted/PV01-bedroom-alarm-adopted-v17B.blend) | `PV01_Bedroom_Alarm_Simple_v17B` |
| 髪を結びながら台所へ | [`PV01-hair-tie-natural-blocking-v06-back-centered.blend`](blender/scenes/morning-hair-tie-natural-blocking-v06-back-centered-20260922/PV01-hair-tie-natural-blocking-v06-back-centered.blend) | `01_FRAMING_GUIDE` |
| 過去・川岸で着地し、馬と歩く | [`PV01-v42-immediate-step-v47.blend`](blender/scenes/past-scene01-v42-immediate-step-v47-20260924/PV01-v42-immediate-step-v47.blend) | `V47_V42_IMMEDIATE_STEP` |

.blendのモデルと画像はこの一式だけで開けるように整えています。Git LFSの導入はこの専用ZIPには不要です。現在の物体配置・寸法・カメラ・動きは.blendにあり、`blender/metadata/` に一覧もあります。

[詳しい再開手順](docs/README.md) / [5シーンとの対応表](docs/scene-map.csv) / [ファイル検証](verification.json)

採用画像と実際の入力画像47点、採用・保存動画8本、シーンごとの制作説明は[Driveの共有先](https://drive.google.com/drive/folders/17nl8A0gVquQmT1m-OklU8OqpLZ6RFRk0)に置く構成です。HTML資料ZIPに画像・動画・このBlender一式を同梱しています。

## 作品の制作資料・画像・動画

- [HTML制作資料ZIP](https://drive.google.com/file/d/1Emy47uRh__eyAShSCYFe6K9tojb4ktcT/view)
- [画像・動画の素材集](https://drive.google.com/drive/folders/17nl8A0gVquQmT1m-OklU8OqpLZ6RFRk0)

このリポジトリにはMovie01の選定したBlender5ファイルと、その再開に必要な説明・メタデータ・関連プロンプトを収録しています。
