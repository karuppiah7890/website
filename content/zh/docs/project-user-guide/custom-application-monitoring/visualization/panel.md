---
title: "图表"
keywords: '监控, Prometheus, Prometheus Operator'
description: '探索仪表板属性和图表指标。'
linkTitle: "图表"
weight: 10816
---

KubeSphere 当前支持两种图表：文本图表和图形图表。

## 文本图表

文本图表适合显示单个指标的数值。文本图表的编辑窗口包括两部分，上半部分显示指标的实时数值，下半部分可进行编辑。您可以输入 PromQL 表达式以获取单个指标的数值。

- **图表名称**：该文本图表的名称。
- **单位**：指标数据的单位。
- **精确位**：支持整数。
- **监控指标**：包含可用的 Prometheus 指标。

![文本图表](/images/docs/zh-cn/project-user-guide/custom-application-monitoring/visualization/charts/text-chart.png)

## 图形图表

图形图表适合显示多个指标的数值。图形图表的编辑窗口包括三部分，上半部分显示指标的实时数值，左侧栏用于设置图表主题，右侧栏用于编辑指标和图表描述。

- **图表类型**：支持折线图和堆叠图。
- **图表配色**：修改图表各个指标的颜色。
- **图表名称**：图表的名称。
- **描述信息**：图表描述。
- **添加**：新增查询编辑器。
- **图例名称**：图表中线条的图例名称，支持参数。例如 `{{pod}}` 表示使用 Prometheus 指标标签 `pod` 来给图表中的线条命名。
- **间隔**：两个数据点间的步骤值 (Step Value)。
- **监控指标**：包含可用的 Prometheus 指标。
- **单位**：指标数据的单位。
- **精确位**：支持整数。

![图形图表](/images/docs/zh-cn/project-user-guide/custom-application-monitoring/visualization/charts/graph-chart.png)