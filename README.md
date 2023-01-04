## 起動手順
```sh
$ cd ~/playground/opensearch
$ docker-compose up -d

// 以下コマンドを叩いてレスポンスが返ってくればOK
$ curl -XGET http://localhost:9200
```

## Dashboardへのアクセス
`http://localhost:5601/`にブラウザでアクセス'
