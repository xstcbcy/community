## ShoeBox社区

## 资料
[Spring 文档](https://spring.io/guides)
[Spring Web](https://spring.io/guides/gs/serving-web-content/)
[ew社区](https://elasticsearch.cn/explore)
[Bootstrap 文档](https://v3.bootcss.com/getting-started/)
[Github OAuth 文档](https://docs.github.com/en/developers/apps/building-oauth-apps)
[Spring](https://docs.spring.io/spring-boot/docs/2.0.0.RC1/reference/htmlsingle/#boot-features-embedded-database-suppoort)
## 工具
[Git](https://git-scm.com/downloads)
[Visual paradigm](https://www.visual-paradigm.com/)

## 脚本
```sql 
CREATE TABLE user
(
  id           INT AUTO_INCREMENT
    PRIMARY KEY,
  account_id   VARCHAR(100) NULL,
  name         VARCHAR(50)  NULL,
  token        CHAR(36)     NULL,
  gmt_create   BIGINT       NULL,
  gmt_modified BIGINT       NULL
)
  ENGINE = InnoDB;
```