﻿OA办公自动化系统，使用Maven进行项目管理，基于springboot框架开发的项目，
mysql底层数据库，前端采用freemarker模板引擎，Bootstrap作为前端UI框架，
集成了jpa、mybatis等框架。作为初学springboot的同学是一个很不错的项目，
如果想在此基础上面进行OA的增强，也是一个不错的方案。

###部署流程

	        1.下载项目、把oasys.sql导入本地数据库
		2. 修改application.properties，
		3. 修改数据源，oasys——>自己本地的库名，用户名和密码修改成自己的
		4. 修改相关路径，配置图片路径、文件路径、附件路径
		5. OasysApplication.java中的main方法运行，控制台没有报错信息，数据启动时间多久即运行成功
		6. 在浏览器中输入localhost:8088/logins


用户名：admin
密码：123456



