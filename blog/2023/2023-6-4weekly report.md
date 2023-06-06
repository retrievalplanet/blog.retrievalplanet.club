# 2023-6-4检索星球周报


## 🚀项目进展

### 1️⃣saturn

**L1-node**

1.在原始的非根目录下失败

![2023-6-4-3](.\img\2023-6-4-3.png)


###  2️⃣boost工具

1.修复：正确取消graphsync请求

2.设置UI默认监听地址为localhost

3.在mpool用户界面中显示msg参数

4.阅读交易建议信息后，重设阅读期限

5.在用户界面中显示已过去的时间和PSD等待时间

6.发布 v1.7.3-rc3

###  3️⃣storetheindex

1.停止集群中的dhstore实例，准备删除它们的数据

2.提升dhstore-helga的CPU

3.检查在indexstar列表中的位置是否影响应收账款的数量。

4.增加Inga的摄取工人数量

5.在开发中部署FoundationDB CRD并定义管理器清单

6.在开发平台上部署盒式集装箱的升级版

7.在dev中定义新的gp3存储类

8.删除多余的用户权限

9.取消速率限制

10使用分配器自动分配已知的发布者时

11.为r6a-xl实例类型扩展开发工作组子网

12.移动管理和摄取服务器，删除libp2p查找服务器

13.移除在ipni-cli中实现的命令

14.用go1.20.x构建容器

15.将最新的dhfind部署到prod中



### 4️⃣Station

**desktop**

1.Station Desktop v0.17.0已经发布

这个版本应该可以修复0.16.0中引入的Windows/Linux问题。

2.core:使用split2修复nldjson解析。

3.core:附加err.cause

4.Station Core v11.1.0发布

这个版本取消了日志存储。之前的设计（`logrotate`+`tail`）被证明不能跨平台兼容。因此大大简化了**站核心**，同时旨在最终以一种更跨平台的方式添加后端存储。如果你已经在 "systemd"、"Docker "或其他为你管理日志的工具中运行**站核心**，应该不会注意到任何行为的变化。

5.更新许多依赖

![2023-6-4-3](.\img\2023-6-4-2.png)

**Zinnia**

1.添加了 `zinnia:test` 模块，并附有模块测试指南

2.为了帮助测试，还增加了 `zinnia:assert` 模块

3.将Chrono从0.4.25提升到0.4.26

4.部署： 将tokio从1.28.1提升到1.28.2





##  📢一周资讯

**1.Filecoin RPC Node Runners!** 

第一个加入Lava的不断增长的节点运行者社区。可以与用户建立联系，尽早获得独特的工具，并帮助Lava达到主网!

![2023-6-4](.\img\2023-6-4.jpg)

**2. 6月1日Hack FS申请关闭了**

**3. BUIDLWeek2023来啦！**

 6月2-4日： ETHSeoul

 6月5日： Web3在首尔的新机遇

 6月6-7日：BUIDLAsia
**4.Filecoin TL;DR发布FVM上使用FIL的新指南**
Filecoin TL;DR最近创建了一个新的指南，以了解购买、存储、转让和租赁FIL的方法。该指南是针对FIL如何在由Filecoin虚拟机（FVM）驱动的各种应用中使用。

链接：[How to buy FIL (filecointldr.io)](https://filecointldr.io/how-to-buy-fil)

**5.SPARK Ingestion 已经部署，该模块现在可以开始检索并提交检索结果**

SPARK模块的实施正在进行中，很快可以通过Zinnia部署到站内。
