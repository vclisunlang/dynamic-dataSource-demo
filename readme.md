SpringBoot + MyBatis plus + Mysql

JDK 版本 1.8

用到了lombok插件,使用方法百度

创建数据库db1,执行user.sql

创建数据库db2,执行t_order.sql

http://localhost:8080/user

http://localhost:8080/order

http://localhost:8080/price

参考：
    http://baomidou.oschina.io/mybatis-plus-doc/#/multi-datasource?id=%e5%a4%9a%e6%95%b0%e6%8d%ae%e6%ba%90%e4%bd%bf%e7%94%a8-spring-abstractroutingdatasource-%e5%ae%9e%e7%8e%b0
    
    
   
在集成shiro的时候，AuthorizingRealm中的加载比spring容器加载要快，所以有些自定义的service先加载进进入到AuthorizingRealm在加载到spring的容器，导致自定义的方法不能被AOP切点捕获。
