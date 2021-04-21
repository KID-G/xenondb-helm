
# Logo 产品名

## 什么是 XenonDB？

XenonDB 是基于 MySQL 的开源、高可用、云原生集群解决方案。通过使用 Raft 协议，XenonDB 可以快速进行故障转移，且不会丢失任何事务。具备金融级强一致性、主从秒级切换，集 InnoDB + TokuDB 双存储引擎支持的增强型 MySQL 集群应用。适用于对数据一致性和高可用性有强烈要求的企业用户。

基于 MySQL 提供的数据库服务，支持一主多从高可用架构，集成 InnoDB + TokuDB 双存储引擎，支持自动备份、监控告警等管理功能

界面截图

## 架构图

![容器版](https://files.mdnice.com/user/8081/a791845e-d0e8-4646-bfbd-5e513706adb8.png)


## 核心功能
|   特性  |  描述   |
| --- | --- |
| 数据强一致性 | 金融版基于 Paxos 协议，采用一主两备三节点加购，自动脑裂保护处理   |
| 服务高可用 | 支持一主多从架构，多可用区主从部署，灵活满足各类可用性需求  |
| 保障数据安全 |   基于实时副本技术，私有网络100% 二层隔离，严密账户确保数据安全  |
| 跨区容灾 | 高可用版及金融版可实现多可用区主从部署，具有跨可用区容灾能力  |
| 自动运维 | 可设置自动备份策略、监控告警策略、自动扩容策略 |
| 降低成本 | 通过 TokuDB 存储空间的利用率提升50%，大幅降低存储成本 |

## 快速部署

k8s 平台

[KubeSphere 应用商店部署](https://github.com/molliezhang/deploy-doc/blob/master/%E9%80%9A%E8%BF%87kubesphere%E5%BA%94%E7%94%A8%E5%95%86%E5%BA%97%E9%83%A8%E7%BD%B2/zh/xenondb-app.md)

## 文档



## 产品对比（性能测试等）

## Roadmap

## 谁在使用？

![](https://files.mdnice.com/user/8081/32eb22ce-aa9f-47fd-808b-ee1455bb70e7.jpeg){width="100px"}
![](https://files.mdnice.com/user/8081/aa89a87b-31c5-4231-bfd8-ceaa90c99242.png){width="100px"}
![](https://files.mdnice.com/user/8081/4a2053e3-bb7e-4d86-a27b-22c47eda8115.jpg){width="100px"}



