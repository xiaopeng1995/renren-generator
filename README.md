**项目说明** 
- renren-generator是人人开源项目的代码生成器，可在线生成entity、xml、dao、service、html、js、sql代码，减少70%以上的开发任务
<br> 


CREATE TABLE `tb_goods` (
 `goods_id` bigint NOT NULL AUTO_INCREMENT,
 `name` varchar(50) COMMENT '商品名',
 `intro` varchar(500) COMMENT '介绍',
 `price` decimal(10,2) COMMENT '价格',
 `num` int COMMENT '数量',
 PRIMARY KEY (`goods_id`)
 ) ENGINE=InnoDB DEFAULT CHARSET=utf8 COMMENT='商品管理';


 **本地部署**
- 通过git下载源码
- 修改application.yml，更新MySQL账号和密码、数据库名称
- Eclipse、IDEA运行RenrenApplication.java，则可启动项目
- 项目访问路径：http://localhost

**演示效果图：**
![输入图片说明](http://cdn.renren.io/img/82b99a1f0f884454ac3fff5e7f658ac8 "在这里输入图片标题")



