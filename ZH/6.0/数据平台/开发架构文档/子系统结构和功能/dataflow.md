# DataFlow
## 实时计算

![](../media/5a49de203c07f782b62fd76511f75e76.png)

实时计算支持秒级流式计算，支持无窗、滑窗、滚窗、累窗 4 总计算模式。

## 离线计算

![](../media/8f5f4e44f2951315945c36ce2535ef94.png)

离线计算支持小时、天级别的批量计算。

## 调度系统

![](../media/eb3a78f72b6063dc0edb7e03425ad53b.png)

调度系统支持托管长任务、短任务，同时提供操作任务 API 及任务运行状况 API。

## Yarn

蓝鲸数据平台使用 Yarn 来托管计算任务。从企业版 3.3 版本开始，调度器由原来的公平调度切换到容量调度，并支持 Cgroup 隔离。
