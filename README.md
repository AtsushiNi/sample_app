# README

# Ruby on Rails チュートリアルのサンプルアプリケーションです

これは、次に教材で作られたサンプルアプリケーションです。
[*Ruby on Rails チュートリアル*](https://railstutorial.jp/)
[Michael Hartl](https://www.michaelhartl.com/) 著

##ライセンス

[Ruby on Rails チュートリアル](https://railstutorial.jp)内にあるソースコードはMITライセンスとBeerwareライセンスのもとで公開されています。

##使い方

このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。
その後、次のコマンドで必要になるRubyGemsをインストールします。

、、、
$ bundle install --without production
、、、

その後、データベースへのマイグレーションを実行します。

、、、
$ rails db:migrate
、、、

最後に、テストを実行してうまく動いているかどうか確認してください。

、、、
$ rails test
、、、

テストが無事に通ったら、Railsサーバーを立ち上げる準備が整っているはずです。

、、、
$ rails server
、、、

詳しくは、Rails on Rails チュートリアルを参考にしてください。
