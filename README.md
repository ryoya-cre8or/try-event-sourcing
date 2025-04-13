# Kafka環境

このプロジェクトはDockerを使用してKafkaとZooKeeperの環境を提供します。

## 必要条件

- Docker
- Docker Compose

## 起動方法

以下のコマンドで環境を起動できます：

```bash
docker-compose up -d
```

## 確認方法

環境が正常に起動したことを確認するには：

```bash
docker-compose ps
```

## 停止方法

環境を停止するには：

```bash
docker-compose down
``` 