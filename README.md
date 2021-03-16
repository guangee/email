# SpringBoot+Email发送邮件

> 使用场景举例:1. 重置密码发送重置链接到用户邮箱。 2. 定时任务导出订单报表excel发送到客户邮箱

1. pom.xml添加对应的依赖

```xml

<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-mail</artifactId>
</dependency>
```

2. 在yml文件中配置对应的邮件。

> 我这里配置的163邮箱的账号密码

3. 在代码中使用 JavaMailSender 发送邮件


# 代码仓库
https://gitlab.coding-space.cn/demo/email

