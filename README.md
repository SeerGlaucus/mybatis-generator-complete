# mybatis-generator-complete
**目的用于mybatis-generator的简化配置使用**
### 使用
1. clone工程到本地，导入maven工程到eclipse中（这里用的开发及运行环境为Eclipse+Maven+JDK8）。
2. 修改resources目录下generatorConfig.properties文件中的数据库配置和生成文件位置配置。
3. 修改resources目录下generatorConfig.xml文件中Table标签的TableName属性为要生成的数据表名。
4. 项目》Run As》 Maven Build》 Goals：
			_mybatis-generator:generate -Dmybatis.generator.overwrite=true_
	 生成文件。
