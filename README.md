<p><h1 align="center">基于Java+Springboot+vue的小米商城</h1></p>

- <b>完整代码获取地址：从戎源码网 ([https://armycodes.com/](https://armycodes.com/))</b>
- <b>技术探讨、资料分享，请加QQ群：692619798</b> 
- <b>作者微信：19941326836  QQ：952045282</b> 
- <b>承接计算机毕业设计、Java毕业设计、Python毕业设计、深度学习、机器学习</b>
- <b>选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 一条龙服务</b>
- <b>所有选题地址 ([https://github.com/YuLin-Coder/AllProjectCatalog](https://github.com/YuLin-Coder/AllProjectCatalog)) </b>


## 一、系统介绍
本项目前后端分离

本项目分为管理员与普通用户两种角色

用户角色包含以下功能：
- 首页 
- 登录、注册、商品分类、首页轮播、商品展示、购物车、订单结算、个人订单管理。

管理员角色包含以下功能：
- 后台首页
销售趋势图、访客量
- 用户管理
用户管理
- 商品管理
商品分类管理、商品上下架、商品图片管理
- 推荐管理
底部推荐栏，大类推荐栏




## 二、所用技术

后端技术栈：

- springboot
- mybatis
- druid
- mysql
- jwtToken
- redis


前端技术栈：

- vue


## 三、环境介绍

基础环境 :IDEA/eclipse, JDK 1.8, Mysql5.7及以上,Node.js(14),Maven

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图

![contents](./picture/picture1.png)

![contents](./picture/picture2.png)

![contents](./picture/picture3.png)

![contents](./picture/picture4.png)

![contents](./picture/picture5.png)

![contents](./picture/picture6.png)

![contents](./picture/picture7.png)

![contents](./picture/picture8.png)

![contents](./picture/picture9.png)

![contents](./picture/picture10.png)

![contents](./picture/picture11.png)

![contents](./picture/picture12.png)

![contents](./picture/picture13.png)

![contents](./picture/picture14.png)

![contents](./picture/picture15.png)

![contents](./picture/picture16.png)

![contents](./picture/picture17.png)



## 五、浏览地址

前端访问地址：http://localhost:8080/

用户账号/密码：ynw/123456

管理员账号/密码：admin/2000918131X  

## 六、安装教程
先运行前台项目tongyimall-master

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的xiaomi.sql文件；

2. 使用IDEA/Eclipse导入springboot项目，若为maven项目请选择maven;导入成功后请执行maven clean;maven install命令，然后运行；

3. 进入src/main/resources修改application.yml 里面的数据库配置和redis配置

4. 启动项目后端项目 

5. vscode打开vue项目，

6. 打开终端，执行npm install 依赖下载完成后执行 npm run dev,执行成功后会显示访问地址

后台管理同上步骤，代码在tongyimall-admin-master目录下





