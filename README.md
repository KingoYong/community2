##码匠社区

##资料
[spring 文档](https://spring.io/guides)
[spring web文档](https://spring.io/guides/gs/serving-web-content/)
[bootstrap](https://v3.bootcss.com/getting-started/#download)
[github 认证](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)

##工具
[OkHttp](https://square.github.io/okhttp/)

##脚本
```sql
create table user
(
	id int auto_increment primary key,
	account_id varchar(100) null,
	name varchar(50) null,
	token char(36) null,
	gmt_create bigint null,
	gmt_modified bigint null,
	bio varchar(256) null
);

```