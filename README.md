# GLB-browser-viewer
GLB Viewer - View Fixed Edition
これは、複数の .glb モデルをドラッグ＆ドロップで切り替えながら表示できる軽量な3Dビューワーです。Googleの <model-viewer> コンポーネントを用いて構築されており、ビュー切り替えやカメラ調整機能も備えています。

# 主な機能
.glb ファイルのドラッグ＆ドロップによる表示

読み込んだモデルの切り替え機能（ラジオボタンで選択）

プリセットされたカメラアングル（正面、背面、右側、左側、斜め上、真上）

モデルサイズに基づく自動カメラ距離調整

# 使用方法
このリポジトリをクローンまたはダウンロード：

bash
Copy
Edit
git clone https://github.com/your-username/glb-viewer.git
index.html をブラウザで開く。

.glb ファイルをウィンドウ内にドラッグ＆ドロップして読み込む。

UI左側パネルでモデルを切り替え可能。

UI右側パネルのボタンで視点変更（例：正面、背面など）。


# 使用ライブラリ
@google/model-viewer

Tailwind CSS

CDNで読み込まれているため、ローカルにインストールは不要。

# 対応形式
.glb（GL Transmission Format 2.0バイナリ形式）


