
【海报】


# 项目介绍

本期给大家介绍一个简单图书管理 系统.。是一个麻雀虽小五脏俱全的项目，有登录，注册，增删改查等基本功能。是一个标准的 Java Web 项目。代码量少，适合初学者练手学习。

该系统有三种角色： 管理员，读者。管理员可以添加图书，添加用户，拥有系统最高权限。读者可以由管理员分配账号，登录本系统，浏览图书并借阅和还书操作。

主要模块有： 登录，注册，图书管理，借阅管理，读者管理，用户中心。

技术栈：
* 后端:  SpringBoot +Mybatis+SpringSecurity+Thymeleaf
* 数据库 : MYSQL
* 前端:  Html+Jquery+CSS+JS

## 一 业务介绍

本系统分为以下几个模块：

### 1.登录

> ![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102224146.png)

### 2.图书管理
可以查看所有图书，并且可以搜索，编辑，添加图书
> ![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102225639.png)
>![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102225712.png)

### 3 借阅管理
该模块主要针对读者，可以浏览图书，并借阅，也可以查看自己借阅的图书，并进行还书操作
> ![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102225803.png)
> ![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102225828.png)
> ![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102225838.png)

### 4.读者管理
该模块可以添加读者，添加读者账号可以进行借书等操作
> ![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102225936.png)
> ![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102225946.png)
### 5 用户中心
可以查看修改所有用户的信息,也可以把某个用户设置为管理员角色,进行图书管理。
> ![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102230037.png)
> ![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102230049.png)
> ![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102230059.png)

## 二 技术介绍
### 1.技术栈

* 后端:  SpringBoot +Mybatis+SpringSecurity+Thymeleaf
* 数据库 : MYSQL
* 前端:  Html+Jquery+CSS+JS

### 2.代码介绍
![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102230318.png)

### 三 Quick Start

### 1. 环境准备
* MYSQL 5.7
* JDK1.8
* Maven 3
* IDEA

> 以上环境需要准备好, 在自己的本地搭建好,方可进行下面步骤
### 2. 下载源码

关注微信公众号: **ITSource 每日分享**,回复 `0015` 获取源码


### 3. 后端部署

- Step1: 下载源码
- Step2: IDEA 打开项目
- Step3: 安装 Maven 依赖
- Step4: 配置检查
> 数据库配置: 找到配置文件 `src/main/resources/application.yml` 修改数据库配置。如图
> ![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102224332.png)

注意：**不需要手动创建数据库和初始化表结构，直接运行项目，会自动创建数据库，初始化SQL语句**
- Step4: 启动后端项目
> Idea 运行后端项目,看到以下信息,表示运行成功
> ![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102224215.png)


点击任何一个连接,即可跳转浏览器打开.
> ![image.png](https://itguang.oss-cn-beijing.aliyuncs.com/20240102224146.png)


>登录:  输入账号密码: admin 123 即可登录成功!

## 下载源码

---
关注微信公众号: **ITSource 每日分享**,回复 `0015` 获取源码

---

**关注微信公众号 【ITSource每日分享】,免费获取一万个IT资源：项目源码，软件工具，面试面经，学习视频 应有尽有！！！!**

![关注 微信公众号 ! 获取更多学习资源呀 ](https://itguang.oss-cn-beijing.aliyuncs.com/订阅号.jpeg)

> 可付费二次开发,  定制, 一对一讲解, 有意可微信联系:  **itguangit**