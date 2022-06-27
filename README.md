# dockerSample
## Use Command LIne
Read "commandLine.md".
參數都可以依據需求修改。

## Use docker-compose File (.yml)

### 使用方法
檔名為'xxx-docker-compose.yml'
1. 可修改為'docker-compose.yml'
即可在該路徑直接使用指令`docker compose up -d`啟動。
2. 不修改檔名，使用指令
`docker compose -f xxx-docker-compose.yml up -d`啟動

### Structure
- DB
  - mongoDB
  - arangoDB
  - postgres
  - redis
