# 名古屋城ハンコARデモ

このフォルダは、MindAR.js + A-Frame で動かすスマホブラウザ用WebARデモの雛形です。

## ファイル構成

- `index.html` : ARデモ本体
- `print_marker_a4.html` : A4印刷用マーカー。10mm/15mm/25mmを配置
- `assets/marker_nagoya_castle.png` : MindARターゲット作成・印刷に使う画像
- `assets/nagoya_castle_stamp_lowpoly_mono.glb` : 3Dモデル
- `targets.mind` : 自分で生成して、この階層に置いてください

## 必須作業

1. MindAR Image Targets Compiler を開く
2. `assets/marker_nagoya_castle.png` をアップロード
3. Start → Download で `targets.mind` を作る
4. ダウンロードした `targets.mind` を `index.html` と同じ階層に置く
5. GitHub Pages、XserverのHTTPS領域などにアップロードする

## 操作

- 横スワイプ：3Dモデル回転
- ダブルタップ：3倍ズーム / 元に戻す

## 注意

Google Driveは静的サイトの正式なホスティングには向きません。ファイル保管用として使い、公開はGitHub PagesまたはXserver推奨です。
