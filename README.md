# dev-docker-env

个人开发环境 Docker Compose 配置，包含常用中间件，开箱即用。

## 包含服务

- MySQL 8.4
- Redis
- Nacos 2.5.1
- RocketMQ (namesrv + broker + dashboard)
- XXL-Job
- Seata
- MinIO
- Neo4j
- Elasticsearch + Kibana
- Sentinel

## 快速开始

```bash
# 克隆
git clone https://github.com/yourname/dev-docker-env.git
cd dev-docker-env

# 启动（使用 --compatibility 使内存限制生效）
docker-compose --compatibility up -d

# 停止
docker-compose down