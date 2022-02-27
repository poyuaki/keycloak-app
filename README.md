# keycloakを用いた認証機能の実装(Vue)
これはテストです。

# 現在の進捗(22/02/27)
とりえあずvueを動かせるようになりました。SPAはhistoryモードなのでnpm run serveで動かしてます。

# 参考元
[oauth2-with-keycloak](https://github.com/s-moteki/oauth2-with-keycloak)

# vueに関して

## 起動
```
docker-compose up app
```

変更した場合には`docker-compose build app`をする

## 起動(dockerを用いない)
```
npm run serve
```
※appフォルダ内で実行
