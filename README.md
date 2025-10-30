# TEST
# Blender EOTA Tools
## インストール
1. https://github.com/peakys-org/BlenderEOTAToolsTrial/releases/ から、最新のリリースの ZIP ファイルをダウンロードします。
2. Blender を起動して、トップバーの編集[Edit] >  プリファレンス...[Preferences…] から、Preference ウィンドウを開き、アドオン[Add-ons] に進みます。
3. ウィンドウの右上の下矢印のメニューから、ディスクからインストール[Install from Disk...] に進み、ダウンロードした ZIP ファイルを選択します。
4. インストール後、一度 Blender を終了します。
5. 3D ビューポート[3D Viewport] のタブとして「EOTA_Tools」が利用できます。
![Image](https://github.com/user-attachments/assets/d6666cd7-2f9a-447a-abf8-3e73b94a96a9)

## フィードバック
[**是非ご意見をお聞かせください！(Google Form)**](https://docs.google.com/forms/d/e/1FAIpQLSefeNHd3IgLEh-5zvnnR53sBz5-dhEXeFPGSsqIZxN-uO7UzQ/viewform?usp=sf_link)

## デモ動画
[![デモ動画サムネイル](https://github.com/user-attachments/assets/a18bfd9c-253a-4f42-be83-f97cb145a27e)](https://drive.google.com/file/d/1KsITm78NIKZx9f725tZ70sgjK0ENtBSi/view?usp=sharing)


## 各要素解説

### 操作
![Image](https://github.com/user-attachments/assets/69fe51d9-caa8-4aef-a2b5-d1d35f7de167)

- カメラの位置に関する操作です。

### カメラ一覧
![Image](https://github.com/user-attachments/assets/bc800a33-b85f-4d57-ba41-be0c39a5f774)

- 「カメラからの視野」は、3D ビューポート[3D Viewport] の右側にある、カメラビューを切り替えます[Toggle the camera view] ボタンと等価です。
- リストは、シーンオブジェクトのカメラの一覧です。このリストからカメラを選択するとそのカメラは、シーンカメラになり、他のカメラは隠されます。
  - マウスカーソルがパネル上にある状態で、次のショートカットが使えます。
    - Shift + Alt + w  または 上　 →　リストの上に移動
    - Shift + Alt + s  または 下　 →　リストの下に移動

### 解像度
![Image](https://github.com/user-attachments/assets/d08d7864-5630-452b-9647-3def6a734111)

- 基本となる解像度です。プリセットが用意されています。オーバースキャンが0のときに出力される画素数です。

### カメラへの設定
![Image](https://github.com/user-attachments/assets/98985c0d-f0df-48ec-9dfc-dd12076fde2a)

#### 一段目
- オーバースキャン領域の割合を示します。
- 実際に出力される画素数です。

#### 二段目
- ラベルの通りです。

#### 三段目
- オーバースキャン枠に対する設定です。
- オーバースキャン枠はレンダリング結果にも描画されます。不要の場合は、「線の太さ」を 0px にするなどします。

### 出力
![Image](https://github.com/user-attachments/assets/b1388f1d-b099-463e-890f-e492a4de2b5c)

- 「ファイル名」「カメラ名」は、出力先のファイル名にこれらを含ませます。

### 印字
![Image](https://github.com/user-attachments/assets/8feebfe2-6d3b-461d-84be-fa1f430a40c2)

- 出力画像に情報を印字します。

### マニュアル
![Image](https://github.com/user-attachments/assets/b30a862e-b4f5-40bd-9a99-9d1aced6468b)

- このページを開きます。

## 全体像
EOTA Tools は 3D ビューポート[3D Viewport] のタブとして現れます。

![Image](https://github.com/user-attachments/assets/ec62823d-5f74-4c38-8723-73c5e55442c2)
