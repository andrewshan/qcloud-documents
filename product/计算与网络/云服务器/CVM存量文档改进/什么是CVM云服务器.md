腾讯云服务器CVM（Cloud Virtual Machine）是腾讯云提供的可扩展的计算服务。使用CVM避免了使用传统服务器时需要预估资源用量及前期投入，帮助您在短时间内快速启动任意数量的云服务器并即时部署应用程序。
腾讯云 CVM 支持用户自定义一切资源：CPU、内存、硬盘、网络、安全等等，并可在访问量和负载等需求发生变化时轻松地调整它们。

## 相关概念

使用腾讯云服务器CVM之前，您还需要了解以下概念：

- **实例**：云端的虚拟计算资源，包括CPU、操作系统、网络、磁盘等最基础的计算组件。
- **实例类型**：腾讯云提供的云服务器的各种不同CPU、内存、存储和网络配置。可以参考[实例规格](https://cloud.tencent.com/document/product/213/11518)了解更多。
- **镜像**：指云服务器CVM运行的预制模版，包括预配置的操作系统及预装软件。腾讯云CVM提供Windows，Linux等多种预制镜像。
- **本地盘**：与实例处于同一台物理服务器上的，可被实例用作持久存储的设备。
- **云硬盘**：提供的分布式持久块存储设备，可以用作实例的系统盘或可扩展数据盘使用。
- **私有网络**：腾讯云提供的虚拟的隔离的网络空间，与其他资源逻辑隔离。（待确认）
- **IP地址**：腾讯云提供[内网IP](https://cloud.tencent.com/doc/product/213/5225)和[公网IP](https://cloud.tencent.com/document/product/213/5224)。简单理解，内网IP提供局域网（ LAN ）服务，云服务之间经由内部链路互相访问。公网IP在用户在云服务器实例上部署的应用需要公开提供服务时使用。
- **弹性IP**：专为动态网络设计的静态公网 IP，满足快速排障需求。
- **安全组**：安全组可以理解为是一种虚拟防火墙，具备状态检测和数据包过滤功能，用于一台或者多台云服务器网络访问控制，安全组是重要的网络安全隔离手段。
- **登录方式**：安全性高的 [SSH 密钥对](https://cloud.tencent.com/doc/product/213/6092) 和普通密码的 [登录密码](https://cloud.tencent.com/doc/product/213/6093) 。



## 如何使用云服务器CVM

腾讯云提供如下方式进行云服务器CVM的配置和管理：

- **控制台**：腾讯云提供的Web服务界面，用于配置和管理云服务器。
- **API**：腾讯云也提供了API接口方便您管理云服务器CVM。关于API说明，请参考[API概览](https://cloud.tencent.com/document/api/213/15689)。
- **SDK**：您可以使用 [SDK编程](https://cloud.tencent.com/document/sdk)或使用腾讯云[命令行CLI](https://cloud.tencent.com/document/product/440/6317)工具调用CVM API。



## 快速购买及配置CVM实例

如果您是个人用户并且首次购买云服务器CVM，腾讯云推荐您通过我们提供的[快速配置CVM云服务器——增加连接]()。


## CVM 定价

CVM 支持包年包月和按量付费。更多信息，请参考 [ CVM 实例价格](/doc/product/213/2176) 。
CVM 及相关资源的价格信息，请参考 [产品定价](https://buy.cloud.tencent.com/calculator/cvm) 。

## 其他相关产品

- 您可以使用弹性伸缩定时或根据条件地自动增加及减少服务器集群数量。更多信息，请参考 [弹性伸缩产品文档](https://cloud.tencent.com/doc/product/377)。

- 您可以使用负载均衡横跨多个云服务器实例自动分配来自客户端的请求流量。更多信息，请参考 [负载均衡产品文档](https://cloud.tencent.com/doc/product/214)。
- 您可以使用容器服务管理在一组云服务器的应用生命周期。更多信息，请参考 [容器服务产品文档](https://cloud.tencent.com/doc/product/457)。

- 您可以使用云监控服务监控云服务器实例及其系统盘。更多信息，请参考 [云监控产品文档](https://cloud.tencent.com/doc/product/248)。
- 您可以在云上部署关系数据库，也可以使用腾讯云云数据库。更多信息，请参考 [云数据库MySQL](https://cloud.tencent.com/doc/product/236)。




