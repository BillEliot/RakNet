# RakNet

## 快速开始

* [RakNet](https://github.com/BillEliot/RakNet/wiki/RakNet)
* [多人游戏的组成(Components of a multiplayer game)](https://github.com/BillEliot/RakNet/wiki/%E5%A4%9A%E4%BA%BA%E6%B8%B8%E6%88%8F%E7%9A%84%E7%BB%84%E6%88%90(Components-of-a-multiplayer-game))
* [总览(System-Overview)](https://github.com/BillEliot/RakNet/wiki/总览(System-Overview))
* [具体实现(Detailed-Implementation)](https://github.com/BillEliot/RakNet/wiki/%E5%85%B7%E4%BD%93%E5%AE%9E%E7%8E%B0(Detailed-Implementation))
* [实例教程(Tutorial)](https://github.com/BillEliot/RakNet/wiki/%E5%AE%9E%E4%BE%8B%E6%95%99%E7%A8%8B(Tutorial))
* [编译配置(Compiler Setup Visual Studio)](https://github.com/BillEliot/RakNet/wiki/%E7%BC%96%E8%AF%91%E9%85%8D%E7%BD%AE(Compiler-Setup---Visual-Studio))

## 基础

* [Startup()](https://github.com/BillEliot/RakNet/wiki/Startup()) - 启动RakPeerInterface和对线程休眠计时器的解释。
* [Connecting()](https://github.com/BillEliot/RakNet/wiki/Connecting()) - 如何查找和连接到其它系统以及对问题的处理。
* [创建包(Creating Packets)](https://github.com/BillEliot/RakNet/wiki/%E5%88%9B%E5%BB%BA%E5%8C%85(Creating-Packets)) - 如何使用结构体和bitstreams创建自定义包以及如何编码世界戳。
* [接收包(Recieving Packets)](https://github.com/BillEliot/RakNet/wiki/%E6%8E%A5%E6%94%B6%E5%8C%85(Recieving-Packets)) - 如何通过结构体或bitstream将原始数据转换回可读的包。
* [SystemAddresses](https://github.com/BillEliot/RakNet/wiki/SystemAddresses) - 描述包中和作为一些函数参数的SystemAddress结构体的目的和使用。
* [Bitstreams](https://github.com/BillEliot/RakNet/wiki/Bitstreams) - RakNet中bitstream类概述以及通过API使用。
* [可靠类型(Reliability Types)](https://github.com/BillEliot/RakNet/wiki/%E5%8F%AF%E9%9D%A0%E7%B1%BB%E5%9E%8B(Reliability-Types)) - 涵盖可用于控制数据发送的参数。
* [网络消息(Network Messages)](https://github.com/BillEliot/RakNet/wiki/%E7%BD%91%E7%BB%9C%E6%B6%88%E6%81%AF(Network-Messages)) - API发送给用户的消息概述。同样列举在MessageIdentifiers.h。
* [给包添加时间戳(Timestamping your packets)](https://github.com/BillEliot/RakNet/wiki/%E7%BB%99%E5%8C%85%E6%B7%BB%E5%8A%A0%E6%97%B6%E9%97%B4%E6%88%B3(Timestamping-your-packets)) - 涵盖时间戳的目的。
* [网络ID对象(Network ID Object)](https://github.com/BillEliot/RakNet/wiki/%E7%BD%91%E7%BB%9CID%E5%AF%B9%E8%B1%A1(Network-ID-Object)) - 一个给每个类实例分配独一无二且全系统共享的标识符的工具类。
* [统计(Statistics)](https://github.com/BillEliot/RakNet/wiki/%E7%BB%9F%E8%AE%A1(Statistics)) - RakNet提供的统计数据。
* [安全连接(Secure Connections)](https://github.com/BillEliot/RakNet/wiki/%E5%AE%89%E5%85%A8%E8%BF%9E%E6%8E%A5(Secure-Connections)) - 如何启用并使用安全连接。
* [云主机(Cloud hosting)](https://github.com/BillEliot/RakNet/wiki/%E4%BA%91%E4%B8%BB%E6%9C%BA(Cloud-hosting)) - 使用云主机服务配置RakNet。
* [预处理指令(Preprocessor directives)](https://github.com/BillEliot/RakNet/wiki/%E9%A2%84%E5%A4%84%E7%90%86%E6%8C%87%E4%BB%A4(Preprocessor-directives)) - 使用不同的代码设置重新编译库。
* [自定义内存管理(Custom Memory Management)](https://github.com/BillEliot/RakNet/wiki/%E8%87%AA%E5%AE%9A%E4%B9%89%E5%86%85%E5%AD%98%E7%AE%A1%E7%90%86(Custom-Memory-Management)) - 对于主机，内存追踪等等。
* [IPV6支持(IPV6 support)](https://github.com/BillEliot/RakNet/wiki/IPV6%E6%94%AF%E6%8C%81(IPV6-support)) - 新一代IP地址格式。

## 插件

* [SQLite3Plugin概述(SQLite3Plugin Overview)](https://github.com/BillEliot/RakNet/wiki/SQLite3Plugin%E6%A6%82%E8%BF%B0(SQLite3Plugin-Overview)) - 通过网络执行SQlite语句(取代LightweightDatabase)。
