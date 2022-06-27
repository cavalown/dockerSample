# dockerSample
## Use Command LIne
Read "commandLine.md".
參數都可以依據需求修改。

## Use docker-compose File (.yml)

### 使用方法
檔名為'xxx-docker-compose.yml'
1. 修改檔名為'docker-compose.yml'
- 啟動： 在該路徑直接使用指令`docker compose up -d`
- 關閉&刪除：在該路徑直接使用指令`docker compose down`
2. 不修改檔名，直接指向要使用的檔案路徑
- 啟動：`docker compose -f xxx-docker-compose.yml up -d`
- 關閉&刪除：`docker compose -f xxx-docker-compose.yml down`

### Structure
- DB
  - mongoDB
  - arangoDB
  - postgres
  - redis
