---
layout: page
title:  HTTP vs HTTP 2 vs HTTPs with SSL
permalink: /wiki/http1-2httpsSSL/
---

*by:* Weizhao Li & Ziyue Li & Zhuolun Gao


A short description of your post goes here.

---

The rest of your post goes here.
TIP:

插入图片例子：
1. github 上，把图片上传到/wiki/http1-2httpsSSL/images/ 目录下
2. 根据如下格式：

```bash
![image](https://github.com/wzli1214/gwAdvNet20.github.io/blob/dev/wiki/http1-2httpsSSL/images/Graduation_capital.jpg)

```

3. 这就会把images里面这周图片给显示出来
![image](https://github.com/wzli1214/gwAdvNet20.github.io/blob/dev/wiki/http1-2httpsSSL/images/Graduation_capital.jpg)

/**********************************/

### HTTP 1 vs HTTP 1.1 vs HTTP 2.0


### HTTPS
Hypertext Transfer Protocol Secure (HTTPS) is an extension of HTTP. It can also be called with HTTP over SSL (or TLS), which indicates its high relation with SSL protocol. 
Now,let’s take a brieft journey on how HTTPS evolved and take a closer look at the basic concepts of the it.

#### The defect of HTTP
There are three main defects that HTTP hold:
-	Communication uses clear text (not encrypted), which may be eavesdropped.
- The identity of the correspondent is not verified, so there may be spoofing.
- The integrity of the message cannot be proven, so it may have been tampered with.
To solve these questions and get a more safe communication, SSL (or TLS) are introduced.

#### Brief history of SSL
Secure Sockets Layer (SSL), and its now standardized successor, Transport Layer Security (TLS), was first developed by Netscape Company. Taher Elgamal(Figure 1), chief scientist at Netscape Communications from 1995 to 1998, has been described as the "father of SSL". SSL Version 1.0 was never publicly released because of serious security flaws in the protocol. Version 2.0, released in February 1995, contained a number of security flaws which necessitated the design of Version 3.0.

![image](https://github.com/wzli1214/gwAdvNet20.github.io/blob/dev/wiki/http1-2httpsSSL/images/Taher%20Elgamal.png)
Taher%20Elgamal


### Secure Sockets Layer (SSL) 