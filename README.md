#### 自动化办公伙伴
 - 办公自动化（OA）是面向组织的日常运作和管理,员工及管理者使用频率最高的应用系统，极大提高公司的办公效率。

#### 项目介绍
- oasys是一个OA办公自动化系统，使用Maven进行项目管理
- 基于springboot框架开发的项目，mysql底层数据库，前端采用freemarker模板引擎，Bootstrap作为前端UI框架
- 集成了jpa、mybatis等框架
- 
#### 项目结构
![项目结构](https://images.gitee.com/uploads/images/2018/0926/164310_e781580c_1277461.png "项目结构目录.png")

#### 前端技术
Freemarker + Bootstrap + Jquery

#### 后端技术
SpringBoot + MyBatis + Spring-Data-Jpa+ Fastjson

#### 部署流程

	    1.下载项目、把oasys.sql导入本地数据库
		2. 修改application.properties，
		3. 修改数据源，oasys——>自己本地的库名，用户名和密码修改成自己的
		4. OasysApplication.java中的main方法运行，控制台没有报错信息，数据启动时间多久即运行成功
		5. 在浏览器中输入localhost:8088/logins

###  项目截图

![演示1.gif](https://images.gitee.com/uploads/images/2019/0927/141250_aeec4d38_1277461.gif)
![演示4.gif](https://i.loli.net/2018/09/26/5bab4565b121e.gif)
![演示3.gif](https://images.gitee.com/uploads/images/2019/0927/141251_4ef0327c_1277461.gif)

![主页面.png](https://images.gitee.com/uploads/images/2019/0927/141250_2286d104_1277461.png)
![登陆页面.png](https://images.gitee.com/uploads/images/2019/0927/141250_f5277aa8_1277461.png)
![文件管理.png](https://images.gitee.com/uploads/images/2019/0927/141250_491ce25d_1277461.png)
![讨论区.png](https://images.gitee.com/uploads/images/2019/0927/141251_d4992cd4_1277461.png)
![新建流程.png](https://images.gitee.com/uploads/images/2019/0927/141251_c7d89853_1277461.png)
![通讯录.png](https://images.gitee.com/uploads/images/2019/0927/141251_bcf9cbda_1277461.png)
