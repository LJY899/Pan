# 网盘项目
## 1. 项目配置
JAVA：推荐JDK1.8

数据库：MySQL8.0

项目启动类：PanApplication.java

## 2. 前置准备
将项目拉取到本地，用IDEA打开；
添加MySQL数据源，创建bjpan数据库，执行bjpan.sql；
## 3. 配置更改
- 数据库配置在src/main/resources/application.properties中修改
- 云盘用户保存文件的路径在src/main/resources/application-windows.properties，需要自己更改
## 4. 项目启动
1. 运行PanApplication.java，打开浏览器输入http://localhost:8080/
2. 默认网盘用户：用户名admin，密码123456
