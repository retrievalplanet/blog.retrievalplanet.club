# 2023-8-27检索星球周报


## 🚀项目进展

### 1️⃣saturn

1.chore(protobuf)：更新 `protobuf` 版本 protoc-24.0 => protoc-24.1

2.chore(reload.sh)：添加默认的 `PRE_UPDATE_WAIT_DIVISOR` 在reload.sh文件中

![image-20230826122314489](img/8-27-4-2023.png)

3.升级 Lassie 至0.16.1

###  2️⃣boost工具

*None*

###  3️⃣storetheindex

1.ci: uci/copy-templates

+ chore: 将 `go.mod` 升级到 1.20 并且 `run go fix`
+ chore: 将 `go-libp2p` 和 `quic-go` 升级至最新版本

2.创建新的 dhstore 节点 `dhstore-ravi`

3.将 `inga-indexer` 改为使用 `dhstore-ravi`

4.部署新的 `ipnisycn` 索引器，以检查是否与现有 `providers` 合作

5.更新 dev 环境中的 `ipnisync sti` 镜像

### 4️⃣Station

##### desktop

1.更改 `deps(dev)`：`bump electron` 版本从 25.5.0 更新到 26.0.0

2.`desktop` 版本更新至 0.21.0

3.更新项目部分依赖

![image-20230826121539739](img/8-27-1-2023.png)

![image-20230826121629865](img/8-27-2-2023.png)

##### zinnia

1.ci: 使用Go version 1.20

2.更新部分项目依赖

![image-20230826121834676](img/8-27-3-2023.png)

##  📢一周资讯

