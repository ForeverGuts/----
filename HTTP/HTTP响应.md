---
tags:
  - HTTP响应
time: 2025-12-26
aliases:
---
# 1. 状态码(Code)
当浏览者访问一个网页时，浏览者的浏览器回向网页所在服务器发出请求，当浏览器接受并显示网页前，网页所在服务器回返回一个包含HTTP状态码的信息头(Server Header) 用以响应浏览器的请求
常见HTTP状态码：
- 200 请求成功
- 301 资源网页等被永久转移到其他URL
- 404请求的资源网页等不存在
- 500内部服务器错误
状态码由三个数字组成，第一个数字定义了状态码的类型，后面两个数字表示具体的状态
![[Pasted image 20251226151625.png]]
# 2.响应头(Response Header)
响应头包含了网页的重要描述信息，比如网页格式 网页过期时间
注意下面的Set-Cookie，它会设置网页的Cookie，在后面的请求中发送给服务器端，用来做身份判定或者反爬
# 3.响应内容(Response Body)和Content Type
![[Pasted image 20251226152421.png]]
获得返回的内容类型：
- 网页数据(Html Json XML)
- 图片
- 样式表
- JavaScript
![[Pasted image 20251226152838.png]]
![[Pasted image 20251226152850.png]]