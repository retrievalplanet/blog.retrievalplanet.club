# 2023-5-20检索星球周报


## 🚀项目进展

### 1️⃣saturn

**L1-node**

1.开始轮换认证

2.降低开放文件的缓存，每个工作者只保留最热门的文件

3.匹配宽限期超时

4.L2不再是土星的近期路线图，而是ipfs和SPs

5.处理接收证书和key的非确定响应


###  2️⃣boost工具

1.修复statx输出字符串

###  3️⃣storetheindex

1.将DHBatchSize设置为1，作为实验的前提。

2.撤销 "暂时关闭inga以触发压实"。

3.自动更新lassie-event-recorder的图像

4.切换写到原始的dhstore

5.增加最大节点组限制，为集群部署做准备

6.实验在dhstore上使用更大的CPU

7.现在dhstore有了更多的空间，又开始了以前的工作

8.部署提供正确公告路径的分配器


### 4️⃣Station

**desktop**

1.发布0.16.1

2.更新了很多依赖的版本

![5-20-2](.\img\5-20-2.png)



3.更新core到10.0.1

**zinnia**

1.将Swatinem/rust-cache从2.2.1升级到2.3.0

2.重构：一个最小的测试框架

引入一个新的内置模块`zinnia:test`。这个模块输出一个单一的函数`test(name, fn)`，它可以用来定义和运行Zinnia模块的测试。

3.将模块加载器移到自己的文件中

4.文档：更新标语

5.将Deno断言嵌入zinnia:assert中

6.Zinnia CLI可以从任何地方导入JS

7.从发布版本中移除protoc的依赖性

8.Zinnia现在支持从本地文件导入JavaScript模块

9.Zinnia 和Station Core现在已经完全整合!



##  📢一周资讯

1.**Filecoin DeStor供应商门户网站上线**，一站式商店，为DeStor供应商提供关于分散存储的最新更新和GTM内容。

注册入口：[Join the DeStor Portal - Filecoin DeStor SP Portal (channeltivity.com)](https://destorportal.channeltivity.com/BecomeAPartner?utm_campaign=SP Portal Launch&utm_content=248939883&utm_medium=social&utm_source=twitter&hss_channel=tw-1504473748841242638)

2.**HackFS 2023开始了**！

时间：2023年6月2日至21日

HackFS 2023是一个汇集了以太坊生态系统中一些顶尖人才和专家的活动。通过提供丰富的web3资源，如导师、赞助商和软件，使团队在3周内做出项目。

活动网址：[联邦理工集团 |黑客FS 2023 (ethglobal.com)](https://ethglobal.com/events/hackfs2023)

3.**Video Jam 黑客松结束**

![image-20230519104600662](.\img\FuBCkjlaQAIH_VV.jpg)



**第一名HuddleCast**

HuddleCast允许内容创作者通过可交易的Hyperspace Filecoin智能合约出售其视频或游戏内容的捆绑/权利。

HuddleCast解决的问题：
现有的流媒体人往往有大量的追随者，在Twitch等直播网络上直播后，他们会将自己的内容发布到youtube或其他网站上--但这可能就是终点。鉴于这些追随者，我们想通过提供纪念品来提供一个与粉丝进一步联系的机会，并为内容创作者提供一个额外的收入机会。HuddleCast允许任何流媒体人将其流媒体内容的集合变成可购买的合同和IPFS视频组。

作品详情：[HuddleCast | Devfolio](https://devfolio.co/projects/huddlecast-c6aa)

**第二名HuddleScribe**

面向未来协作的终极会议应用

HuddleScribe是一个创新的会议应用，提供一系列独特的功能，使其成为未来协作的终极会议应用。它对Huddle01 SDK和Filecoin虚拟机的使用确保了它的高度安全性，并提供了一种独特而有效的方式来控制对内容的访问，保护敏感数据不受未经授权的访问。

作品详情：[HuddleScribe | Devfolio](https://devfolio.co/projects/huddlescribe-d60f)

**第三名zkMeetups**

主办和参加受隐私保护的代币事件

zkMeetups是一个综合平台，利用零知识证明（ZKP）技术为隐私保护的活动提供完整的解决方案。该平台为有门槛的聚会提供各种选择，包括令牌门槛和NFT门槛活动。通过覆盖Web3空间中所有可能的网关，zkMeetups确保所有活动都是安全和私密的。代币门控的聚会要求用户的钱包里有特定的代币或加密货币才能参加活动。这种方法确保只有对项目或社区有特定参与程度的用户才能参加活动。

作品详情：[zkMeetups | Devfolio](https://devfolio.co/projects/zkmeetups-0808)

**4.SBS-Earth即将到来!**

时间：8月16日

SBS-Earth，一个完全虚拟的、全球性的ReFi节，为实地项目和web3技术的实际应用带来更多的能见度！开创性的活动，将联合行业领袖、创新者和可持续发展爱好者，探索区块链在促进一个更绿色和更公平的世界方面的力量。

网站：https://sbs.earth/

**5.在SynBioBeta与Filecoin SP社区见面**

世界上最大的合成生物学会议SynBioBeta 2023，5月23日至25日在奥克兰万豪城市中心加入我们，了解分散存储如何解决研究人员的数据管理问题

![5-20-1](.\img\5-20-1.png)

**6.共识日回来了**

在6月5日至6日参加第三期ConsensusDays，这是一个专注于共识和相关主题的最新研究的虚拟研讨会。

**7.第六届Funding the Commons将于7月15日至16日在法国巴黎的美丽背景下举行**

这次Funding the Commons的安装时间是对Ethereum社区会议的完美补充，后者在第二天举行，离大学只有很短的步行距离。巴黎将是我们在2023年期间的主要亲身活动，其独特之处在于，除了主旨发言人和小组讨论之外，还纳入了开放空间技术和其他非会议式的程序。

链接：[资助下议院 - 即将举行的活动 (fundingthecommons.io)](https://fundingthecommons.io/)







