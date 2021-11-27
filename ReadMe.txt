仮想環境を用意したいフォルダに次の３つのファイルを保存する。

1. active,bat
2. deactive.bat
3. Open_Virtual.bat


フォルダ内でアドレスバーに「cmd」と入力しコマンドプロンプトを開く。

仮想環境用のパッケージをインストール
pip install virtualenv

仮想環境を作成する
python -m venv .venv

以上。


仮想環境を開く場合は、「Open_Virtual.bat」をダブルクリック。するとコマンドプロンプトが起動し仮想環境が有効になる。