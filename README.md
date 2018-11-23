# ArchitectureDesignTree
架构设计的基本规则


<pre>
一篇架构设计说明书大致应该是这样的：

   文档概述：
           项目背景
           项目目标
           文档版本信息
           目标读者
           参考文档
           名词解释
           等
   整体架构：
           主要从整个IT层描述系统所处的位置，与周边关联系统之间的调用关系
   逻辑架构：
           系统内部功能模块的划分
           各模块功能的介绍
           模块相互之间的关系
   接口设计：
           系统间的接口设计
           系统内各模块之间的接口设计
   数据架构：
           本系统与上下游系统间的数据流转关系
           本系统内关键数据表设计
           数据管理策略
   技术架构：
           实施此架构需要用到哪些技术
           复用能力
           风险
   部署架构：
           网络拓补结构
           硬件性能要求
           高可用的方案
           是否存在单点故障
   非功能性设计：
           性能
           高可用
           可扩展性
           可维护性
           安全性
           可移植性
   其他说明与FAQ
</pre>