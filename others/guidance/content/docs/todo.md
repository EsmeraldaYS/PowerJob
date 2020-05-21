---
title: 开发计划
weight: 4

---

{{< hint info >}}
截止目前（v1.2.0），框架的基本功能（调度和分布式计算）已经趋于稳定，大家可以放心接入使用。不过为了使框架更为成熟易用，仍有需要不断改进和开发的地方。
{{< /hint >}}

## 下阶段规划

* 支持DAG工作流
* 任务的优先级系统，需要可抢占式实现，~~~而不是SchedulerX那种傻等式~~~
* 在线日志的限流 & 本地数据库分表提升在线日志最大吞吐量
* 保护性判断（优先级较低，太繁琐了且意义不大，毕竟面向开发者，大家不会乱填参数对不对～）

## 共同建设邀请 (❁´◡`❁)*✲ﾟ*

都看到这里了，相比您对本项目产生了**浓厚**的兴趣，欢迎加入开源社区，为框架贡献自己的力量～

（PR、Issue求求了～）

如果有什么想法、建议或意见，都欢迎联系作者：tengjiqi@gmail.com。
