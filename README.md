# -
鄙人空闲之际整理了本专业的计算机网络的知识点，只适用于本校生，其他校外同学看个乐即可，未经授权，禁止转载哦！
#
考试范围：第一、二、三、四、五、六、九章
1.2互联网的概述
计算机网络的定义：计算机网络（简称为网络）由若干结点（node）和连接这些结点的链路（link）组成

互联网的定义：网络之间还可以通过路由器互连起来，这就构成了一个覆盖范围更大的计算机网络。这样的网络称为互联网（internetwork or internet） 

概念：网络把许多计算机连接在一起，而互连网则把
许多网络通过路由器连接在一起。与网络相连的计
算机常称为主机。

1.2.2 互联网基础结构发展的三个阶段
第一阶段是从单个网络ARPANET 向互连网发展的过程。
第二阶段的特点是建成了三级结构的互联网。
第三阶段的特点是逐渐形成了多层次ISP 结构的互联网。

1.3互联网的组成
（1）边缘部分：由所有连接在互联网上的主机组成。这部分是用户直接使用的，用来进行通信（传送数据
音频或视频）和资源共享。
（2）核心部分：由大量网络和连接这些网络的路由器组成。这部分是为边缘部分提供服务的（提供连通性和交换）。

1.3.1
在网络边缘的端系统之间的通信方式通场可以划分为两大类：客户-服务器方式（C/S方式）和对等方式（P2P方式）。

什么是客户（client）和服务器（server）呢？
客户和服务器都是指通信中涉及的两个应用进程。客户-服务强方式所描述的是进程之间服务和被服务的关系。
客户是服务请求方，服务器是服务提供方。

1.3.2互联网的核心部分
在网络核心部分起特殊作用的是路由器(router) ，它是一种专用计算机（但不叫做主
机）.路由器是实现分组交换的关键构件，其任务是转发收到的分组，这是网络核心部分最重要的功能。

1 ．电路交换的主要特点
电路交换：必须经过过“建立连接（占用通信资源）一通话（一直占用通信资源） ➔ 释放连接（归还通信资源）”三个步骤的交换方式称为电路交换。
 
2. 分组交换的主要特点
分组交换则采用存储转发技术。
主机是为用户进行信息处理的。
路由器则是用来转发分组的，即进行分组交换的。
 
1.5.2 几种不同类别的计算机网络
1. 按照网络的作用范围进行分类
(1) 广域网WAN (Wide Area Network) 广域网的作用范围通常为几十到几千公里，
因而有时也称为远程网(long haul network) 。广域网是互联网的核心部分，其任务是通过长距
离（例如，跨越不同的国家）运送主机所发送的数据。连接广域网各结点交换机的链路一般
都是高速链路，具有较大的通信容量。本书不专门讨论广域网。

(2) 城域网MAN (Metropolitan Area Network) 城域网的作用范围一般是一个城市，
可跨越几个街区甚至整个城市，其作用距离约为5 ~ 50 km。城域网可以为一个或几个单位
所拥有，但也可以是一种公用设施，用来将多个局域网进行互连。目前很多城域网采用的是
以太网技术，因此有时也常并入局域网的范围进行讨论。

(3) 局域网LAN (Local Area Network) 局域网一般用微型计算机或工作站通过高速
通信线路相连（速率通常在10 Mbit/s 以上），但地理上则局限在较小的范围（如1 km 左
右）。在局域网发展的初期，一个学校或工厂往往只拥有一个局域网，但现在局域网已非常
广泛地使用，学校或企业大都拥有许多个互连的局域网（这样的网络常称为校园网或企业
网）。我们将在第3 章3.3 至3.5 节详细讨论局域网。

(4) 个人区域网PAN (Personal Area Network) 个人区域网就是在个人工作的地方把
属千个人使用的电子设备（如便携式电脑等）用无线技术连接起来的网络，因此也常称为无
线个人区域网WPAN (Wireless PAN) ，其范围很小，大约在10m 左右。我们将在第9 章9.2
节对这种网络进行简单的介绍。
顺便指出，若中央处理机之间的距离非常近（如仅1 米的数量级或甚至更小些），则一
般就称之为多处理机系统而不称它为计算机网络。

1.6计算机的性能
1.6.1计算机网络的性能指标
1.速率： 比特（bit）,一比特就是二进制中的0或1嗷。
2.带宽：
3.吞吐量
4.时延（阿罗稍稍感觉是重点）：
（1）发送时延（2）传播时延（3）处理延时（4）排队延时

总延时=发送延时+传播延时+处理延时+排队延时
5.时延带宽积
6.往返时间RTT
7.利用率



1.7计算机网络的体系结构



