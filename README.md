# 🔱项目介绍【已完结🎉】
> 对你有用的话，希望能给项目点个Star，非常感谢。

> 对于项目的任何问题，或者你在本地部署时遇到的无法解决的问题，都可以提交issues，又可能你遇到的问题别人已经提交了issues，那么你就直接可以得到解决。没有解决的我会在第一时间进行解决和答复

## 瑞吉外卖

&emsp;&emsp;本项目是参考B站黑马程序员的《瑞吉外卖》教程所实现的一个SpringBoot+MybatisPlus+Mysql技术栈的前后端分离外卖管理系统。对于初学者较为友好，业务逻辑简单易上手，适合刚学完ssm做的一个练手项目。

&emsp;&emsp;项目目前分为V1和V2两个版本，V2版本较V1版本来说，加入了Redis技术和其他地方的一些优化。

- 未学习Redis的读者，可以根据V1版本进行学习，后期适配Redis即可。
- 了解过Redis的读者，直接建议上手V2版本，适配Redis，可以适当浏览V1的Session部分，进行对比，从而更好的体现出使用Redis的优点，加深印象。

- 前台预览

![前台](https://github.com/codermast/Takeout-food/blob/master/resource/%E6%88%AA%E5%B1%8F2022-12-01%2019.32.09.png?raw=true)
- 后台预览

![后台](https://github.com/codermast/Takeout-food/blob/master/resource/%E6%88%AA%E5%B1%8F2022-12-01%2019.37.24.png?raw=true)
## 🔷使用技术
- SpringBoot
- MySql
- Mybatis Plus
- Redis

## 项目模块
- 🔺后台
  - [x] 登录模块
  - [x] 员工管理
  - [x] 分类管理
  - [x] 菜品管理
  - [x] 套餐管理
  - [x] 订单管理
- 🔻前台
  - [x] 用户模块
  - [x] 购物车模块
  - [x] 地址模块
  - [x] 订单模块
  - [x] 菜品模块

## 项目部署

1. 下载本项目到服务器。

2. 修改`src/main/resources/application.yml`文件内的数据库信息
> V1需要改动的就是下面说明的三个地方
  - 数据库名
  - 数据库用户名
  - 数据库密码
> V2还需要添加Redis的配置信息
3. 在服务器上部署时，将项目打成`jar`包，使用`java -jar 包名`进行运行
4. 访问后台：[localhost:8080/backend/page/login.html](http://localhost:8080/backend/page/login.html)即可
5. 访问前台：[localhost:8080/front/page/login.html](http://localhost:8080/front/page/login.html)
## ❤️‍🩹版本内容
### V1版本

#### 技术栈
- SpringBoot
- MybatisPlus
- Mysql
- Session
#### 版本更新
> 2022/11/28：~~V1版本的后台功能已经开发完毕，就剩前台的API还没有开发完毕。~~
>
> 2022/12/1 ：V1版本的前后台均已开发完毕，也将图片的下载和删除适应到了SpringBoot的Jar包中，可以打包在服务器中运行。
### V2版本
- SpringBoot
- MybatisPlus
- Mysql
- Redis

**缓存到Redis的内容：**
- [x] 缓存短信验证码
- [x] 缓存菜品信息
- [x] 缓存用户信息
- [x] 缓存地址信息
- [x] 缓存套餐信息
## 参考教程

- 笔记整理：CSDN-[https://blog.csdn.net/qq_33685334/article/details/128150052](https://blog.csdn.net/qq_33685334/article/details/128150052)

- 视频教程：黑马程序员-瑞吉外卖项目[https://www.bilibili.com/video/BV13a411q753](https://www.bilibili.com/video/BV13a411q753)


## 资料下载

- 后端API思维导图：[Xmind格式：点我下载](https://github.com/codermast/Takeout-food/blob/master/resource/%E7%91%9E%E5%90%89%E5%A4%96%E5%8D%96API%E5%89%96%E6%9E%90.xmind)
- SQL文件：[点我下载](https://github.com/codermast/Takeout-food/blob/master/resource/db_reggie.sql)
  ![](https://github.com/codermast/Takeout-food/blob/master/resource/瑞吉外卖API剖析.png)
