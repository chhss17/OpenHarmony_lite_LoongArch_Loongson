## 题目：鸿蒙小型系统在龙芯平台的实现
## 项目描述
在龙芯开发板上运行鸿蒙轻量系统，实现基础功能（任务调度、外设驱动、网络通信等）并对比与其他架构的性能区别。
LS2K0300/500是基于LA264处理器核的多功能SoC芯片，支持多种嵌入式操作系统，适用于工业控制、通信设备、信息家电和物联网等领域，但其目前缺乏鸿蒙系统支持。
本项目目标是能够将鸿蒙内核在龙芯LS2K0300或2K0500开发板上成功运行。参与本项目可以加深对操作系统原理和计算机体系结构的理解。

## 参赛要求
* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求

## 项目导师
* 徐斌 tsuibin@loongson.cn

## 难度
低-中

# License
主要仓库遵循Apache License V2.0

## 预期目标
* 确认系统从 Bootloader 到鸿蒙内核的完整启动; 
* 运行多个线程，测试任务切换是否正常;  
* 通过 UART 输出日志、控制 GPIO 点亮 LED; 
* 使用 perf 工具分析中断延迟、任务切换时间; 
* 对比龙架构与 ARM 平台的系统调用吞吐量

## 参考资源
*[龙芯相关大赛参考文档](https://github.com/LoongsonLab/oscomp-documents)

*[鸿蒙小型系统芯片移植指导]
(https://docs.openharmony.cn/pages/v5.0/zh-cn/device-dev/porting/porting-smallchip-prepare-needs.md")

## 备注
龙芯能够提供免费的LS2K0300或2K0500开发平台
