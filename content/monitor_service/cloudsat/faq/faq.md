---
title: "常见问题"
linkTitle: "常见问题"
date: 2020-02-28T10:08:56+09:00
description:
draft: false
weight: 2
keyword: CloudSat, 自定义监控数据
---

## 上传自定义监控数据代码示例

目前提供了 Golang 和 Python 两种语言的[上传自定义监控数据代码示例](/monitor_service/cloudsat/manual/upload_monitor_data/) 供参考。

## 为什么自定义监控上传数据成功，页面没有显示？

自定义页面监控列表中涉及到一些时间区间内的监控数据计算，最小统计周期为 5 分钟，因此需连续发送一段时间（不小于 5 分钟）页面才有数据显示。

如持续发送超过五分钟仍未正常显示，请检查上传数据的 meter（监控指标）字段是否和在自定义监控页面下该命名空间下创建的监控指标名称一致。

