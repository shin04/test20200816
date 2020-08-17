```
$ docker-compose build
$ docker-compose run --rm app rails db:create
$ docker-compose run --rm app rails db:migrate

$ docker-compose up -d
↑ [エラー吐かれたら]
$ docker-compose up -d --remove-orphans

docker-compose upできたら http://localhost:3000 で起動確認できるはず
いつものHello Railsの画面がでたらOKです

```

環境
Ruby 2.6.5
Rails 6.0.3
DB - sqlite3(これMySQLにしたいけど一旦サーバー立てた)