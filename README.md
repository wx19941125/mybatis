## Welcome to mybatis

mybatis,数据库持久层框架，ORM框架。

    1 hibernate,全自动ORM框架,以面向对象思想去操作数据库,与JDBC相比,封装JDBC全部过程;

    2 mybatis,半自动ORM框架,以面向原生sql思想去操作数据库,与JDBC相比,封装了传递参数和对结果集的处理;
### 搭建mybatis环境

导包→mybatis.xml→Mapper.xml→测试;

### mybatis单表CURD

XML+Mapper;传递参数和对结果集的处理;

### mybatis多表CURD

XML+Mapper;级联查询和对自定义结果集的处理;动态sql查询;

### mybatis事务处理

使用JDBC事务(java.sql.Connection)完成事务管理,即``` <transactionManager type="JDBC" /><!--配置事务的管理方式--> ```

### mybatis缓存机制
