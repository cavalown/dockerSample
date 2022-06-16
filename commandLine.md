# 使用指令啟動Dockert Container

## Database
### Arango DB
```docker=
$ docker run -it --name ArangoDB -p 8529:8529 -e ARANGO_ROOT_PASSWORD=password -v 要存檔的資料夾路徑:/var/lib/arangodb3 arangodb/arangodb:3.9.1
```
### Postgress
```docker=
$ docker run -it --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres
```