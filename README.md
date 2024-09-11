## Docker　API起動コマンド
```zsh
docker-compose up
```
## 起動url
http://localhost:8000/docs

## MySQLクライアントを起動コマンド
```
docker-compose exec db mysql demo
```

## test実行コマンド
```
docker-compose run --entrypoint "poetry run pytest --asyncio-mode=auto" demo-app
```

## 参考URL
https://zenn.dev/sh0nk/books/537bb028709ab9/viewer/f1b6fc

## Flutterでフロントエンド作成
https://github.com/sodateya/fastapi_on_flutter
