# mybatis-mapping-generator
mybatis映射自动生成工具

## 操作步骤
1. 修改 generatorConfig.xml 中数据库连接
2. 设置生成模型的包名和位置
3. 设置要生成的表 tableName是数据库中的表名或视图名 domainObjectName是实体类名
4. 运行 java -jar mybatis-generator-core-1.3.2.jar -configfile generatorConfig.xml -overwrite

## 参考资料
http://blog.csdn.net/zhshulin/article/details/23912615