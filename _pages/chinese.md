---
title: ""
permalink: /chinese/
author_profile: true
---
## 个人简介
[cv](https://akaliu.github.io/files/resume.pdf)



## 学习经历

| 时间                | 学位                            | 工作学习单位           | 专业                        |
|:------------------- | :----------------------------- |:---------------------- |:-------------------------- |
| 2020.9 - 至今      | 硕博连读            | 中国科学院计算技术研究所 | 计算机系统结构|
| 2016.9 - 2020.6    | 本科                | 东南大学 | 通信工程|


## 代表性工作 [[完整列表](https://akaliu.github.io/publications/)]

* DFGC: DFG-Aware NoC Control Based on Time Stamp Prediction for Dataflow Architecture
[[pdf](https://akaliu.github.io/files/iccd-paper.pdf)]
[[slides](https://akaliu.github.io/files/iccd-presentation.pdf)]
[[video](https://drive.google.com/file/d/1myxa5YtLx6YrFwELE0Lr0SWWTjwLozqv/view?usp=share_link)]<br>
<b>Tianyu Liu</b>, Wenming Li, Zhihua Fan. <br>
<i>International Conference on Computer Design</i> (**ICCD**), 2023. <b>CCF-B 会议</b>.
* DFU-E: A Dataflow Architecture for Edge DSP and AI Applications [[pdf](https://akaliu.github.io/files/tpds-paper.pdf)]<br> Wenming Li, Zhihua Fan, <b>Tianyu Liu</b>, et al.<br> <i>IEEE Transactions on Parallel and Distributed Systems</i> (**TPDS**), 2025. <b>CCF-A Journal</b>. 

  
## 参与项目&科研工作
* 2020.9 - 至今 “DPU”系列芯片研发
  * **架构设计与实现** 独立负责“DPU-F” 芯片上新一代片上网络及路由的设计及验证，实现新型拓扑互联，提高数据流多核架构的片上数据传输效率和带宽
  * **架构设计与实现** 独立负责控制模块的设计及验证，实现数据流动态触发；实现调度功能，完成任务/线程级共享机制优化设计
  * **性能调优与测试** 独立负责性能统计与可视化和GDB 细粒度断点调试功能开发，明确运行时硬件资源使用情况，解决数据流架构上单指令调试难题，降低系统优化难度
  * **性能调优与测试** 模拟器：根据内核性能调优需求对模拟器进行Profiling 和代码优化，完成算子和模拟器环境迁移工作；RTL：片上网络和控制的冗余逻辑剪除
  * **验证环境与维护** 统筹验证环境维护和总体验证工作，协调各模块验证工作，参与子系统和SoC验证环境的修改、SMOKE TEST 等；参与后端时序分析及架构优化
  
* 2022.2 - 至今 异构数据流处理器系统软硬件协同优化
  * **计算路由级调度** 研究基于数据流架构的软硬件协同方法，根据数据流CGRA 上静态预测缺失导致流图关键路径传输执行受阻的问题，研究设计基于执行机制的静态时间戳静态预测算法，设计计算和传输的优先级调度机制，通过静态协同方式降低流图边数据传输阻塞，研究成果形成文章1 篇(ICCD-2023)
  * **软硬件工作流** 研究基于数据流架构的软硬件协同工作流，包括数据流多层次执行模型、硬件灵活动态控制机制和映射优化方法，深度优化架构的软硬件协同过程，使用动态协同的映射及执行方式提高架构整体能效，研究成果形成文章1 篇(TACO 在投)
  * **任务级调度**分析科学计算领域大规模稀疏线性系统求解在GPU 上的性能瓶颈，实现其在数据流架构上的硬件加速优化，设计多任务灵活调度机制，研究成果形成文章1 篇(CAL 在投)

* 2022.1 - 至今 稀疏神经网络加速
  * **稀疏预测加速** 研究基于数据流架构的稀疏神经网络优化，通过SVD 分解对稀疏卷积计算进行加速，设计专用加速器，研究成果形成文章2 篇(TPDS-2024, DATE-2023)
  * **压缩算法与硬件协同设计** 提出一个压缩和加速稀疏卷积神经网络的算法硬件协同设计方案，平衡稀疏性适应性与计算效率，研究成果形成文章1 篇(TACO 在投)

* 2021.10 - 2022.11 华为合作项目“高通量计算阵列研究”
  *  参与基带算子移植性能分析及数据流架构优化工作，包括对Cholesky, SVD 等算法的调研分析及高通量计算架构的调研工作, 完成架构调研报告和算子优化方案，形成专利1 篇

* 2021.1 - 2022.12 综合数字处理芯片研制(中科院空天信息研究院合作项目) 
  * 参与合成孔径雷达成像算法SAR的移植优化工作，基于可重构架构设计通用映射方案，形成文章1 篇(CAL)


## 获奖情况

* 2023年海光博士生奖 
* 2023年中国科学院大学学业奖一等奖 
* 2022年中国科学院大学冬奥会和冬残奥会优秀志愿者
* 2022年三好学生标兵
* 2021年易方达金融科技硕士生奖 
* 2021年中国科学院大学学业奖一等奖 

