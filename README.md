# gin-jwt-template
このリポジトリはgo/gin/jwt-goを用いたWebAPI/トークン認証実装のベースとなる試験的なリポジトリです。

## TODO
- [ ] DB/ORM
- [ ] token認証

## Dockerコンテナ環境自動構築
```
docker/bootstrap
```

## Dockerコンテナ起動
```
docker-compose up

# デーモン起動の場合には-dオプション付きで
docker-compose up -d
```

## アーキテクチャ
```
Clean Architectureを試験採用

参考はこちら
http://psychedelicnekopunch.com/archives/1308
```
