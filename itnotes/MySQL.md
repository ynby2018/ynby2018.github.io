## MySQL命令
### MySQL 备份和还原数据库
```
mysqldump -uroot -p -h 192.168.0.1 -P 123 --set-gtid-purged=OFF -x --hex-blob --default-character-set=utf8mb4 DBNAME > F:\DBNAME20201126.sql
```
* -x 锁表
* --no-data 导出跳过的表结构 
* --ignore-table 跳过表和视图
* --tables 指定导出表

```
mysql -uroot -p -h 192.168.0.1 -P 123 --default-character-set=utf8mb4  DBNAME < F:\DBNAME202010291528.sql
```