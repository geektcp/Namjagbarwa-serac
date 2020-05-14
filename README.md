# alpha-serac
> serac系统要做什么？ <br/>
创造一套传输层协议SCP(Serac-Controll-Protocol)，天生具有数据加密特性！融合TCP传输控制机制，UDP高效传输性。<br/>
创造一套java语言的底层网络封装工具，支持原始套接字，支持SCP协议


## 概述
> 传输层协议TCP，UDP已经存在多年，这套协议已经很老了，存在很多安全隐患。
> SCP协议， 新研发传输层控制协议。天生具有数据加密属性，高效传输性，无状态性。
> SRPC协议， 基于SCP传输层协议的应用层RPC协议，远程过程调用

```
底层传输库
java封装工具库
```


## 前期功能
```
1、基于原始套接字构造各种常见的和不常见的数据包，包括TCP, UDP, HTTP, DNS, ARP等数据包。
2、支持任意报头字段设置。
3、支持负载内容自定义。

一个可以高度复用的数据包生成器。
1、Linux C语言的项目工程的编码构建方式
2、构造任意结构的数据包。
3、学习互联网底层深处的细节。
4、认识网络安全或者黑客攻击手段的原理。
5、观察到互联网络通信的本质。
```

## 中期功能
```
用户无缝切换netty到serac
```
