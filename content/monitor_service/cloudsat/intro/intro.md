---
title: "CloudSat 简介"
date: 2020-12-01T00:38:25+09:00
description: Test description
draft: false
enableToc: false
keyword: CloudSat, 自定义监控
---

# 产品概述

云监控服务 CloudSat 为云上用户提供开箱即用的企业级开放型一站式监控解决方案。涵盖了用户账户内的所有核心 IT 设施基础监控。支持基于指标、事件、自定义指标等各类监控与告警服务。利用云监控告警服务内的各项功能，可实现全闭环、全链路的立体化监控系统。

使用云监控服务 CloudSat，可以有效降低企业IT运维监控成本。也可及时了解业务的运行状况和健康度，及时收到异常报警做出反应，保证应用顺畅运行。


# 功能简介

## 监控概览

监控概况模块主要对云产品的整体监控情况进行整体的汇总与展示，为用户提供一个查看入口。用户可从全局视角来查看账号内所有云资源的监控状况，以及核心资源的用量排序。

### 功能概述

监控概览为用户提供实时查看整体监控数据的功能，将云平台最核心的服务监控指标使用率情况集中呈现在一张监控大屏里，根据用户的资源运行与监控状态进行实时的监测与更新，为用户定制一个立体化监控平台，供用户进行全局管理。  

监控概览内，提供了资源整体监控告警情况统计、告警统计、云服务器核心指标使用量监控与排序、网络核心指标的监控与排序、存储关键指标的监控与排序等。
通过查看监控概览，让用户实时了解各云服务的资源使用情况和告警情况。
监控概览的主要展示信息分为以下四大类：

1. 实时展示资源类型与总数统计。
2. 各资源告警、正常、未配置告警策略数据统计展示。
3. 近 24 小时 事件/告警统计数据展示。
4. 资源核心指标数据总和以及 Top5 统计展示。

### 适用场景
1. 在日常运维工作中，满足用户对账号下全部基础资源的全局监控状态视角概览需求，可了解并把控所有资源的整体运行健康情况。
2. 在进行运维工作整体优化评估时，可参考所有资源的报警数据趋势图，分析并发现资源出现异常时的高峰时段，加以应对与防范。
2. 可通过资源用量排序了解核心基础资源的使用情况，有助于用户及时执行配置调整。

## Dashboard

云监控的 Dashboard 功能为用户提供自定义查看监控数据、定位异常资源的功能。用户可跨区域、跨资源类型创建自定义监控图表与面板。该功能可灵活、高效地适用于各类监控场景下，实现对同类指标的对比监控需求。用户可以在一张监控大盘中跨资源类型、跨实例查看监控数据，并将相同业务的不同资源指标集中展现。

### 功能概述

监控 Dashboard 为用户提供了可跨资源类型、跨指标类型、跨可用区的自定义集中监控服务，用户可根据业务需求，将各类维度的数据集中在同一个面板下，进行统一可视化监控。

监控 Dashboard 支持丰富的监控时间周期，在每种监控周期下对应的的监控间隔粒度都有所不同，用户可根据监控场景选择符合需求的时间周期。同时，若需要对某一个时间周期下的关键时间点进行进一步操作，可选择‘暂停’刷新的设置，面板将停止自动刷新。

### 术语解释

1. 指标：指标作为具体监控资源中的变量值，如云服务器的 CPU 使用率，也是本次监控 Dashboard 最核心的变量。
2. 面板：可自定义图表的面板区域，一个账号可创建多个面板，可对面板进行重命名、删除等操作。
3. 图表：一张监控图表由资源所属区域、某一类具体资源、该资源的某一个具体指标、需要监控的资源实例（上限 10 个），四个主要因素构成，最终集成为图形化数据，本期支持折线图+列表详述。
4. 监控周期：监控指标的时间范围，目前分别支持：最近 6 小时、最近一天、最近两周、最近一个月、最近六个月、用户自定义周期。按面板页面级统一控制。
5. 监控粒度：实时监控指标的时间粒度，具体监控的时间粒度与对应的时间周期有关。

### 适用场景

1. 监控面板: 监控面板是可供用户自定义编辑的监控视图区，可向监控面板内加入不同区域、不同资源、不同指标的监控图表。
2. 监控图表: 用户可在某一区域内自行创建该区内某类资源的多个实例、单个指标集成的数据图形。创建完成后，可对已创建的图表进行查看、修改、数据导出、删除等操作。
3. 面板全屏: 用户可在面板图表生成之后进行集中监控，若暂时不再操作图表以及面板的其他功能，仅需要盯屏查看监控图表以及数据，可选择“全屏”显示模式，进入全屏式面板。全屏式面板的监控可视化图表效果更佳，同时依然可以支持在监控面板上的数据查看、时间周期切换等功能。

## 分组管理

可根据云资源的实际业务划分，对资源实例进行分组监控，集中配置告警策略，提升运维效率。在实例分组功能内，提供了跨云产品、跨地域的云产品资源分组管理功能，支持用户从业务角度/组织结构/资源规划视角，集中管理业务线等涉及各类资源的健康状态与告警规则。极大的减少了基于业务场景的运维成本。

### 功能概述

实例分组提供了跨云产品、跨地域的云产品资源分组管理功能，可支持用户从业务角度、组织架构角度等，集中管理业务线涉及到的云服务器、硬盘、数据库、负载均衡、网络等各类核心资源。从而按业务线、组织架构等分类，来管理资源涉及到的报警规则，并高效查看监控数据，从而可以迅速提升运维效率。

以下为资源分组的核心功能介绍：
1. 列表汇总所有的分组信息，展示组内的关键统计信息，如：资源类型、资源总数、告警资源数/未告警资源数/未配置告警规则的资源数、创建类型、操作等。
2. 管理实例分组。
3. 管理告警规则。

目前资源组支持的监控资源包括：

**【云服务器】**
- 云服务器状态
- 告警服务
- 告警状态

**【VPC网络】**
- VPC状态
- 告警服务
- 告警状态

**【公网IP】**
- 公网IP状态
- 告警服务
- 告警状态

### 适用场景

1. 购买了多类型云产品的客户，需要利用分组功能将同一业务相关的云服务器、数据库、对象存储、缓存等资源添加到同一分组中进行集中管理。在分组维度内集中去管理报警规则，查看监控数据，可以极大地降低管理复杂度，提高云监控使用效率。
2. 客户在购买了云资源后，所部署的业务重要程度不同，对核心系统需要最高标准的监控告警服务；对非核心的业务系统则需要相对中级的告警策略设置，此类场景，适合将不同重要度的资源集中起来，统一管理、统一批量设置与绑定告警策略。
3. 云资源运维人员若需要对不同部门、不同业务使用资源的情况进行分组查看与管理，则可使用实例分组，按照部门或者业务进行资源划分，清晰了解到各组内的资源情况。

## 事件监控

事件监控模块汇集了云产品各类运维事件，以及用户业务的异常事件。对各类事件进行整体统计与展示，提供多种细查方式与查询模式，提供按资源类型、事件类型、事件名称等多种筛选模式下的事件汇总统计结果，便于关联业务与问题复盘。除此之外，可直接在事件监控列表上进行告警策略的设置与修改工作。

### 功能概述

云监控服务中的「事件监控」功能作为云平台事件信息中枢，产品化了云平台各类基础资源的生命周期与运转中的重要事件信息，并构建完善的事件消费渠道与流程，支撑客户云上监控与运维。

事件监控功能支持以下主要的核心能力：
1. 集中统计展示系统预置的云产品关键事件。
2. 支持不同视图形式下的事件信息展示。
3. 支持对用户关注的事件进行告警策略设置。

### 适用场景

1. 为日常运维工作，提供更加完善的云上资源监控信息维度，为监控运维提供更全面数据支撑。
2. 在对监控数据进行数据消费的环节，提供事件信息消费渠道，帮助用户转化监控信息价值。

## 告警服务

告警功能提供对监控指标的告警服务支持，用户对云服务的核心监控指标设置告警规则，当监控指标触发用户设置的告警规则阈值时，则会按照用户设置的查收通知形式，收取告警信息。目前平台支持以邮箱、短信等方式通知用户，让用户可以在第一时间得知云资源发生的异常情况，快速准确定位，并迅速处理故障，避免因资源问题或者外部操作原因，造成业务上的损失。

### 功能概述

监控告警功能是对资源层面的监控数据，设置告警条件和通知列表， 有助于及时了解资源使用情况和处理突发事件。具体包含以下几个核心的功能点：

1. 设置告警策略规则。
2. 绑定资源到具体的告警规则内。
3. 设置告警通知联系人。
4. 设置联系人接收方式。

### 适用场景

目前支持的监控项包括：

**云服务器**
* CPU 使用百分比
* 内存使用百分比
* 磁盘空间使用百分比，检查范围包括云服务器中所有已挂载（mount）的分区
* 云服务器网卡的进流量，检查范围包括云服务器所有网卡
* 云服务器网卡的出流量，检查范围包括云服务器所有网卡

**公网IP**
* 公网进流量
* 公网出流量

**路由器**
注： 路由器新增针对网络 PPS 和路由器 CPU / 内存的监控告警仅支持新的区域和可用区
* 路由器所连网络的进流量，检查范围包括所有与此路由器连接的私有网络
* 路由器所连网络的出流量，检查范围包括所有与此路由器连接的私有网络
* 路由器所连网络的入口 PPS，检查范围包括所有与此路由器连接的私有网络
* 路由器所连网络的出口 PPS，检查范围包括所有与此路由器连接的私有网络
* 路由器自身的 CPU 利用率
* 路由器自身的内存利用率

**私有网络**
注： 私有网络监控告警仅支持新的区域和可用区
* 私有网络所有网卡的进流量，检查范围包括私有网络内的所有网卡
* 私有网络所有网卡的出流量，检查范围包括私有网络内的所有网卡
* 私有网络所有网卡的入口 PPS，检查范围包括私有网络内的所有网卡
* 私有网络所有网卡的出口 PPS，检查范围包括私有网络内的所有网卡

**负载均衡器**
1. 监听器 HTTP/HTTPS 协议
* 请求数：接收到的请求数
* 平均响应延迟时间：监听器下所有后端的响应时间
* 平均并发数：并发连接数
* 后端1xx/2xx/3xx/4xx/5xx响应数：监听器下所有后端返回的，对应状态码的响应数
* 后端服务器可用个数
* 后端服务器不可用个数
2. 监听器 TCP 协议
* 连接数：监听器下所有后端的 TCP 连接数
* 平均并发数：并发连接数
* 后端服务器可用个数
* 后端服务器不可用个数
3. 后端服务 HTTP 协议
* 平均响应延迟时间：监听器下所有后端的响应时间
* 服务状态：后端服务器是否异常
* 后端1xx/2xx/3xx/4xx/5xx响应数：此后端返回的，对应状态码的响应数
4. 后端服务 TCP 协议
* 连接数：此后端的 TCP 连接数
* 服务状态：后端服务器是否异常

**关系型数据库**
关系型数据库的监控告警只会监控 “主节点” ，包括如下监控项：
* CPU：CPU 使用百分比
* 内存：内存使用百分比
* 磁盘使用率：磁盘空间使用百分比
* 活跃连接数：数据库的活跃连接数
* 查询请求：数据库执行的所有查询请求的次数
* 慢查询：根据数据库配置的慢查询标准，监控慢查询的次数
* 全表扫描次数：发生全表扫描的次数。 (全表扫描是数据库服务器用来搜寻表的每一条记录的过程， 直到所有符合给定条件的记录返回为止，大多发生在对无索引的表进行查询)

**MongoDB**
* CPU：CPU 使用百分比
* 内存：内存使用百分比
* 磁盘使用率：磁盘空间使用百分比
* 连接数：数据库的连接数

**Redis/Memcached**
* 内存利用率：内存使用百分比
* 被拒绝 key 个数

**Zookeeper**
* CPU：CPU 使用百分比
* 内存：内存使用百分比
* 集群服务是否可用

**Kafka**
* CPU：CPU 使用百分比
* 内存：内存使用百分比
* 磁盘使用率：磁盘空间使用百分比
* 出现未复制分区或离线分区

**Hadoop/Spark/Storm/ElasticSearch/HBase**
* CPU：CPU 使用百分比
* 内存：内存使用百分比
* 磁盘使用率：磁盘空间使用百分比

## 自定义监控

自定义监控的功能支持，可满足云平台已有用户、非云平台用户对基础资源的指标监控需求，可与CloudSAT服务内的其他功能结合使用，形成完整的立体化监控告警服务。
在自定义监控功能模块内，需要完成以下几个目标：

1. 对体量较大的客户，可上报非平台预置、其他云平台上的监控数据
2. 对非云平台用户，在自定义功能内，提供轻量、简易的数据上报与监控管理能力
3. 可接入 Zabbix 的基础监控数据，运用 cloudsat 的告警服务、dashboard、图形化指标数据展示等各类功能，简化运维人员运维工作，实现通过云平台达成全面监控的目标弹性裸金属服务器是即将推出的一款全新产品。

### 功能概述

1. 上报数据：按规定路径与参数规范，进行监控指标数据上报。

2. 数据上报状态：系统会对上报的监控数据的各种状态进行及时的反馈与同步，包括延迟/上报失败原因等，保证用户对自定义上报的数据的可控性。

3. 上报后数据展示样式/展示条件/限制/功能：数据归属（组）/图形展示，按数据归属组（命名空间）/维度等过滤查询，数据保存时间/数据类型要求/设置告警规则/查看数据/图形等。

### 适用场景

1. 自定义监控是提供给用户可自由定义监控项及报警规则的能力。用户可以针对自己关心的业务指标进行监控，将采集到监控数据上报至云监控，由云监控来进行数据的处理，并根据处理结果进行报警。

2. 兼容云平台用户、非云平台用户对基础资源的指标监控需求，可与 CloudSAT 服务内的其他功能关联使用，形成全面的立体化监控告警服务。

