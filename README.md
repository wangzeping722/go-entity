# Why to use go-entity
解脱双手，一键生成 gorm 所需要的 entity。

# How to use
## 配置文件
参照 `db.json.example` 中的格式编写配置文件。当 `tables` 为空数组时，表示对所有的表生成代码。
```json
{
  "host": "127.0.0.1",
  "user": "root",
  "pwd": "pwd",
  "dbname": "test",
  "tables": ["user"]
}
```

## 运行
```shell script
go run main.go
```