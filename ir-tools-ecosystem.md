# 增量阅读工具生态（IR Tools Ecosystem）

## 概述

增量阅读的完整实践依赖专用软件。本文整理了目前主流的 IR 工具，包括原生支持 IR 的平台、Anki 插件、移动端方案以及学习资源。

---

## SuperMemo（原生 IR 平台）

**SuperMemo** 是增量阅读的**唯一原生完整实现**，由发明者 Piotr Woźniak 开发。

### 版本与获取

| 版本                    | 状态                 | 说明                          |
| ----------------------- | -------------------- | ----------------------------- |
| SuperMemo 19（SM19）    | 最新付费版           | 完整 IR 功能，功能最全        |
| SuperMemo 18（SM18）    | 付费版               | 使用 SM-18 算法               |
| **SuperMemo 15 及以前** | **免费（Freeware）** | 旧版免费提供，IR 基础功能完整 |

> 社区建议：对于刚入门的用户，可以先从**免费旧版**开始体验 IR，无需购买最新版本。

### 核心优势

- 完整的 IR 工作流：导入 → 阅读 → 提取 → 完形填空 → SRS 复习
- 最先进的 SRS 算法（SM-18）
- 深度的优先级管理系统
- 知识树（Knowledge Tree）组织结构
- 丰富的学习数据统计

### 主要不足

- **仅限 Windows**：没有官方 iOS/Android/macOS 版本（这是社区最大的抱怨之一）
- 界面设计陈旧，学习曲线陡峭
- 生态相对封闭

---

## Anki + 增量阅读插件

对于不愿切换到 SuperMemo 的用户，Anki 社区开发了 IR 插件。

### 推荐插件：Incremental Reading v4.11.8（非官方克隆版）

- **插件 ID**：`999215520`
- **下载地址**：[AnkiWeb - Incremental Reading v4.11.8](https://ankiweb.net/shared/info/999215520)
- **GitHub 源码**：[tvhong/incremental-reading](https://github.com/tvhong/incremental-reading)
- **官方论坛支持**：[AnkiForums](https://forums.ankiweb.net/t/incremental-reading-add-on-unofficial-clone/21331)

### 使用说明资源

- 现代使用指南：[GitHub README](https://github.com/tvhong/incremental-reading)
- 旧版指南（存档）：[Wayback Machine](https://web.archive.org/web/20200916200937/https://luoliyan.github.io/incremental-reading/)

### Anki IR 插件的适用场景

- 从长文本（网页、书籍、教材）创建 Anki 卡片
- 已深度使用 Anki 的用户，不想切换平台
- 主要处理较短的文章，不需要管理数千篇文章

### Anki IR 插件的局限

- 功能远不及 SuperMemo 原生 IR 完整
- 队列管理、优先级系统相对基础
- SRS 调度使用 Anki 算法（SM-2 或 FSRS），而非 SM-18

---

## 移动端方案

SuperMemo 没有官方移动端，是社区最大的痛点之一：

> "我真的很希望能在 iPad 或 iPhone 上进行'IR 流程'。  
> 我一直在尝试不同的系统来重现它，  
> 但始终没有找到完全替代的方案——  
> 只能在 iPad 上阅读，然后把提取的内容复制粘贴到 Notes 应用里……"  
> —— 19年 SuperMemo 用户

### 目前可用的移动端选项

**TededDroid**（Android）

- **GitHub**：[lucidl/tededroid](https://github.com/lucidl/tededroid)
- 由 Reddit 用户 daevisan 开发的 Android 开源 IR 应用
- 实现了基本的 IR 工作流

**变通方案（非原生）**

1. iPad 阅读 → 提取重要段落 → 手动复制到笔记 App → 之后导入 SuperMemo
2. 使用 Anki 移动端 + IR 插件（功能受限）
3. 使用其他支持标注的阅读 App，配合手动整理流程

---

## 替代平台与相关工具

### Soki（soki.ai）

- 现代的 IR 实践工具，支持网页和应用
- 设计更现代，适合不愿使用 SuperMemo 老旧界面的用户

### Obsidian + 间隔重复插件

- 结合 Obsidian Spaced Repetition 插件可实现类 IR 流程
- 更适合以笔记为中心的工作流
- SRS 算法不如 SuperMemo 成熟

### Readwise + Anki

- Readwise 做阅读标注同步，Anki 做间隔重复
- 流程：Kindle/网页标注 → Readwise → 导出到 Anki
- 缺点：标注是一次性的，不像 IR 那样渐进式提炼

---

## 工具选择建议

| 用户类型                    | 推荐方案                               |
| --------------------------- | -------------------------------------- |
| 认真学习 IR、不在乎学习曲线 | SuperMemo 15（免费）或 SM19            |
| 已用 Anki、想尝试 IR 思维   | Anki + IR 插件                         |
| Android 用户、想要移动端 IR | TededDroid                             |
| 语言学习为主                | Anki 足够（IR 方式思考即可）           |
| 学术研究者                  | SuperMemo + Michael Nielsen 风格工作流 |
| 知识管理 / 写作者           | 考虑 Obsidian + 渐进总结               |

---

## 学习资源

### YouTube 频道

**PleasurableLearning**（guillemps）

- 频道地址：[@PleasurableLearning](https://www.youtube.com/@PleasurableLearning)
- 数百个 IR 相关视频
- 推荐视频：
  - _5 Basic Skills of IR with genuine examples_：[youtube.com/watch?v=FEQ15d92kTk](https://youtu.be/FEQ15d92kTk)
  - _Newbie-friendly IR guide_：[youtube.com/watch?v=V25qRwBD4CM](https://youtu.be/V25qRwBD4CM)
  - _Definition of IR (theoretical)_：[youtube.com/watch?v=mJN2UA2xIBo](https://youtu.be/mJN2UA2xIBo)
  - _IR speed reading explained_：[youtube.com/watch?v=8SbVCRCsk_w](https://youtu.be/8SbVCRCsk_w)

### 必读文章

- **Piotr Woźniak**：[Incremental Learning](https://help.supermemo.org/wiki/Incremental_learning)（SuperMemo 帮助文档）
- **Michael Nielsen**：[Augmenting Long-term Memory](http://augmentingcognition.com/ltm.html)（从 SRS 用户角度的深度总结）
- **SuperMemo Guru**：[Incremental Reading](https://supermemo.guru/wiki/Incremental_reading)（理论深度最高）

---

## 相关概念

- [增量阅读概览](./incremental-reading-overview.md)
- [社区实践经验](./community-insights.md)
- [增量阅读 vs 其他方法](./ir-vs-other-methods.md)
- [间隔重复](./spaced-repetition.md)
