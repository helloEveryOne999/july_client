# july_client
![build](https://img.shields.io/badge/build-passing-brightgreen)
![build](https://img.shields.io/badge/license-Apache%202-blue)

七月微信小程序——客户端

这是一款集成了Lin UI开发而成的SaaS社交平台微信小程序。该项目发起于2019年7月，故名为“七月”，现由私仓转为开源，开发之时这是“一个人的社交平台”，自己发动态，自己玩耍，现在正式向大家见面了！

整个系统由多个项目构成，其中后端API服务由Flask开发而成，暂时还未开源，可以通过下方API文档查看具体的接口说明。


## 技术栈
- Lin UI（一款优秀的微信小程序UI框架）：https://github.com/TaleLin/lin-ui
- wxutil（一款好用的微信小程序工具库）：https://github.com/YYJeffrey/wxutil


## 快速开始
1. 下载源码  
    ```
    git clone git@github.com:YYJeffrey/july_api.git
    ```

2. 安装依赖  
该项目源码中已经存在miniprogram_npm文件夹，故该步骤可以跳过，若需要安装其他扩展，请确保您已经安装了npm，并使用`npm install`安装所需依赖。

3. 修改AppID  
该项目是一个SaaS平台，您使用的测试号或者其他或者其他未注册到该平台的AppID时是没有任何数据的，可以通过修改**app.js**中globalData下的appId，将其改成本小程序的AppID即可`wx0611fd1ba2b0bcd6`即可。

    ```
    globalData: {
      appId: "wx0611fd1ba2b0bcd6",
      ...
    },
    ```


## API文档
这一套RESTful API是服务端部分的项目，不做过多介绍，具体内容可以通过下方链接查阅。  
[API文档地址](https://api.july.yejiefeng.com/api/doc)

**功能模块**

<img src="https://img.yejiefeng.com/screenshots/%E6%8E%A5%E5%8F%A3%E5%8A%9F%E8%83%BD%E5%9B%BE.png" width="450px" />


## 产品展示
<img src="https://img.yejiefeng.com/screenshots/1-%E8%AF%9D%E9%A2%98%E5%88%97%E8%A1%A8.jpeg" width="280px" /><br/>

<img src="https://img.yejiefeng.com/screenshots/2-%E8%AF%9D%E9%A2%98%E5%88%97%E8%A1%A8.jpeg" width="280px" /><br/>

<img src="https://img.yejiefeng.com/screenshots/3-%E8%AF%9D%E9%A2%98%E5%88%97%E8%A1%A8.jpeg" width="280px" /><br/>

<img src="https://img.yejiefeng.com/screenshots/4-%E8%AF%9D%E9%A2%98%E8%AF%A6%E6%83%85.jpeg" width="280px" /><br/>

<img src="https://img.yejiefeng.com/screenshots/5-%E8%AF%9D%E9%A2%98%E8%AF%A6%E6%83%85.jpeg" width="280px" /><br/>

<img src="https://img.yejiefeng.com/screenshots/6-%E6%A0%91%E6%B4%9E%E5%88%97%E8%A1%A8.jpeg" width="280px" /><br/>

<img src="https://img.yejiefeng.com/screenshots/7-%E6%A0%91%E6%B4%9E%E8%AF%A6%E6%83%85.jpeg" width="280px" /><br/>

<img src="https://img.yejiefeng.com/screenshots/8-%E6%A0%91%E6%B4%9E%E6%B7%B1%E5%A4%84.jpeg" width="280px" /><br/>

<img src="https://img.yejiefeng.com/screenshots/9-%E7%94%A8%E6%88%B7%E6%8E%88%E6%9D%83.jpeg" width="280px" /><br/>

<img src="https://img.yejiefeng.com/screenshots/10-%E4%B8%AA%E4%BA%BA%E4%B8%AD%E5%BF%83.jpeg" width="280px" /><br/>


## 版本说明
* **v0.0.1** - 小程序已达到生产使用标准，基本功能完善，上线2个月内无异样


## 体验七月

欢迎加入小程序交流群：592832957

支持闲聊和回答技术问题 😁

<img src="./images/logo/qr.jpg" width="180px" />
