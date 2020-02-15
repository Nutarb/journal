
# 1. 目录
<!-- TOC -->

- [1. 目录](#1-%e7%9b%ae%e5%bd%95)
  - [1.1. `2020-02-15`](#11-2020-02-15)
    - [1.1.1. 什么是readyState](#111-%e4%bb%80%e4%b9%88%e6%98%afreadystate)
    - [1.1.2. 什么是status](#112-%e4%bb%80%e4%b9%88%e6%98%afstatus)

<!-- /TOC -->

## 1.1. `2020-02-15`

### 1.1.1. 什么是readyState

readyState是XMLHttpRequest对象的一个属性，用来标识当前XMLHttpRequest对象处于什么状态

|值|含义
|---|---
|0|初始化，XMLHttpRequest对象还没有完成初始化
|1|载入，XMLHttpRequest对象开始发送请求
|2|载入完成，XMLHttpRequest对象的请求发送完成
|3|解析，XMLHttpRequest对象开始读取服务器的响
|4|完成，XMLHttpRequest对象读取服务器响应结束

### 1.1.2. 什么是status

status是XMLHttpRequest对象的一个属性，表示响应的HTTP状态码

|值|含义
|---|---
|1xx|信息响应类，表示接收到请求并且继续处理
|2xx|处理成功响应类，表示动作被成功接收、理解和接受
|3xx|重定向响应类，为了完成指定的动作，必须接受进一步处理
|4xx|客户端错误，客户请求包含语法错误或者是不能正确执行
|5xx|服务端错误，服务器不能正确执行一个正确的请求
