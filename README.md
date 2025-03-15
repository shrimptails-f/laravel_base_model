# 概要
Laravelのローカル環境構築をスキップする用のリポジトリです。<br>
本リポジトリにはLaravel関連のソースは含めません、Reopen in Containerをしたあといい感じのバージョンのLaravelをインストールしてくだい。
※ちなみにLaravel8.0でDB疎通確認できた.envをプロジェクトルートに配置したので良かったら参考にしてくだい。

# 環境構築手順
1. Dockerをインストール
2. VsCodeをインストール
3. ソースをクローン
4. VsCodeの拡張機能にDevContainersをインストール
5. Ctrl Shift Pでコマンドパレットを開く
6. DevContainer:Reopen in Containerを押下
7. create projectコマンドを実行
``` bash
composer create-project laravel/laravel:^8.0 example-app
```
プロジェクトルートにLaravelの関連ファイルを配置したかったら、生成されたファイルをすべてプロジェクトルートに移動して下のコマンドを実行する
```bash
composer dump-autoload
```
