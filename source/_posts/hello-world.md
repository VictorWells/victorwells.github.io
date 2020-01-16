---
title: 关于一次updade导致的死锁问题记录
date: 2020-01-16 10:51:38
tags: dubbo 事务
---

&emsp;&emsp;今天生产报错，打印日志显示为 update table where id=? 造成的死锁。
