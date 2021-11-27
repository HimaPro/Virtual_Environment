仮想環境を用意したいフォルダに次の３つのファイルを保存します。

1. active,bat
2. deactive.bat
3. Open_Virtual.bat


フォルダ内でアドレスバーに「cmd」と入力しコマンドプロンプトを開きます。

仮想環境用のパッケージをインストールします。
pip install virtualenv

仮想環境を作成します。
python -m venv .venv

以上です。


仮想環境を開く場合は、「Open_Virtual.bat」をダブルクリックします。するとコマンドプロンプトが起動し仮想環境が有効になります。
