---
title: "部署 Deep Learning 服务"
description: 本小节主要介绍 Deep Learning 部署指南
keyword: 人工智能，深度学习，Deep Learning，部署服务，部署集群，创建集群
weight: 05
collapsible: false
draft: false
---

## 前提条件

- 已获取管理控制台登录账号和密码。
- 已创建 [VPC 网络](/vpc/manual/vpcnet/10_create_vpc/)和[私有网络](/network/vpc/manual/vxnet/05_create_vxnet/)，且私有网络已加入 VPC 网络。

## 操作步骤

1. 登录管理控制台。

2. 在控制台导航栏中，选择**产品与服务** > **人工智能（AI）** > **Deep Learnling**，进入管理页面。

3. 点击**立即部署**。

4. 基本设置。

   <img src="../../_images/basic.png" style="zoom:50%;" />

   填写服务名称和描述，选择版本。

4. 网络设置。

   ![](../../_images/dl_net_config..png)

   出于安全考虑，所有的集群都需要部署在私有网络中，选择自己创建的已连接路由器的私有网络中。

5. 环境设置

   <img src="../../_images/env_config.png" style="zoom:50%;" />

6. 用户协议

   <img src="../../_images/user.png" alt="user" style="zoom:50%;" />
