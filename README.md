# Mybatis-demo(entry level)

## 1。概述

mybatis是一个优秀的基于Java的持久层框架，它内部封装了jdbc，使开发者只需要关注sql语句本身，而不需要花费精力去处理加载驱动、创建链接、创建statement等繁杂的过程。

mybatis通过xml或注解的方式将要执行的各种statement配置起来，并通过Java对象和statement中sql的动态参数进行映射生成最终执行的sql语句。

最后mybatis框架执行 sql并将结果映射为Java对象并返回。采用ORM思想解决了实体和数据库映射的问题，对jdbc进行了封装，屏蔽了jdbc api底层的访问细节，使得开发者无需再与jdbc api 打交道，就可以完成对数据库的持久化操作。

