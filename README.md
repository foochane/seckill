##一、Java高并发秒杀APi之业务分析与DAO层代码编写
###1.构建maven项目
首先我们要搭建出一个符合Maven约定的目录来,这里大致有两种方式。
第一种:
第一种使用命令行手动构建一个maven结构的目录,命令如下：

>mvn archetype:generate -DgroupId=com.suny.seckill -DartifactId=seckill -Dpackage=com.suny.seckill -Dversion=1.0-SNAPSHOT -DarchetypeArtifactId=maven-archetype-webapp

第二种：在IDEA种直接创建工程
 ![填写Maven在你本机的位置](../screenshot/maven工程创建1.png)  
