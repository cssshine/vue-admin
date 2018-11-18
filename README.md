## Vue后台权限管理系统（双版本:PHP、NodeJS）

	本项目为前后端分离项目 (权限已覆盖后台菜单和操作按钮)
	技术栈：Vue2.5 + Vue-cli3 + Vue全家桶
	服务端为双版本 NodeJS版(ThinkJs3.2) PHP版(ThinkPhP5.1)
	前后端鉴权处理 JSON Web Token(JWT)

## 演示地址

<a href="http://120.78.219.51:9003" target="_blank">PHP版 (ThinkPhP5.1)</a>
<a href="http://120.78.219.51:9002" target="_blank">NodeJS版 (ThinkJs3.2)</a>

## 鉴权处理

* 前后台分离项目需要跨域支持，传统的session cookie已不适合做客服端持久会话
* 本项目采用的是JSON Web Token(JWT)做用户授权认证
* refresh_token控制用户访问时长，access_token做交互验证（短时间内有效，过期自动刷新）


## 项目截图

![](http://qiniu.sponges.cn/201811181400_380.png)

* 有相关页面按钮权限时
![](http://qiniu.sponges.cn/201811181356_229.png)

* 无按钮权限时显示  （测试账号 test 密码 111111）
![](http://qiniu.sponges.cn/201811181355_213.png)

* 双token授权
![](http://qiniu.sponges.cn/201811181449_7.png)

