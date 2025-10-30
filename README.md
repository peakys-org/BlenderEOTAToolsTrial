# Blender EOTA Tools Beta 版
## インストール
1. https://github.com/peakys-org/BlenderEOTAToolsTrial/releases/ から、最新のリリースの ZIP ファイルをダウンロードします。
2. Blender を起動して、トップバーの編集[Edit] >  プリファレンス...[Preferences…] から、Preference ウィンドウを開き、アドオン[Add-ons] に進みます。
3. ウィンドウの右上の下矢印のメニューから、ディスクからインストール[Install from Disk...] に進み、ダウンロードした ZIP ファイルを選択します。
4. 3D ビューポート[3D Viewport] のタブとして「EOTA_Tools」が利用できます。
5. EOTA Tools は 3D ビューポート[3D Viewport] のタブとして現れます。
![Image]("https://github.com/user-attachments/assets/4d940c33-7917-4387-9dd3-28ace00a6eb8)

## フィードバック
[**ご意見をお聞かせください！(Google Form)**](https://docs.google.com/forms/d/e/1FAIpQLSefeNHd3IgLEh-5zvnnR53sBz5-dhEXeFPGSsqIZxN-uO7UzQ/viewform?usp=sf_link)

## 対応済み Blender バージョン
- Blender 4.0.0 から Blender 4.3.2 まで

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

- 「ファイル名」 「カメラ名」は、出力先のファイル名にこれらを含ませます。

### ご意見・ご要望
![image](https://github.com/user-attachments/assets/a5e1d597-656c-4797-9cd0-43f7fcc6dc27)

### マニュアル
![Image](https://github.com/user-attachments/assets/b30a862e-b4f5-40bd-9a99-9d1aced6468b)

- このページを開きます。
