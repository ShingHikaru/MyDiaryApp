# Diary App
This is a simple django diary app. Django ver 3.1.2 is used. 

This app is deployed on GCP App Engine and
the database is 

## Quick start
### App engine URL
https://global-gist-319203.rj.r.appspot.com/

### Local Development
You need to install 
```
% source venv/bin/activate
% cd mydiaryproject
% python manage.py makemigrations
% python manage.py migrate
% python manage.py runserver
```

## Memo
Terminalの重要コマンド
$ cd .. 上の階層のディレクトリに戻る
$ cd フォルダを指定
$ ls ディレクトリに格納されているファイルの一蘭を表示
$ mkdir フォルダの作成
$ python3 -m venv .djangoenv 仮想環境作成に必要なデータをdjangoenvに格納
$ pip install djangoやpythonなどの指定のバージョンのインストールに使う

$ python3 manage.py runserver アプリの実行（Ctl + cで解除）

Djangoの各データの役割
・urls.py
Django プロジェクトの URL 宣言、いうなれば Django サイトにおける「目次」に相当。
・manage.py
Djangoのコマンドユーティリティ。





