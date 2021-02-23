# myBaseProject

## execute java for docker-compose

```
// dockerビルド
docker-compose build

// dockerをバックグラウンドで起動
docker-compose up -d

// 確認
docker-compose ps

// インスペクション(java)
docker-compose exec java bash

// javaコンパイル(別ディレクトリでコンパイル）
:/usr/src# javac app/*/*.java -d classes

// java実行
;/usr/src# cd classes
:/usr/src/classes# java ${class name (ex.BaseController)}
```
