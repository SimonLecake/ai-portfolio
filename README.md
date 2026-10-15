<div align="center">

# SimonLecake · AI 应用作品集

### 从业务问题出发，让 AI 进入可用、可检查的工作流程。

LLM 评估 · 检索增强生成 · 数据分析 Agent · 计算机视觉

**简体中文** · [English](README_EN.md) · [GitHub 主页](https://github.com/SimonLecake)

</div>

**源码状态：四个项目均已设为 Public。点击下方仓库链接，即可查看源码、项目说明与使用方法。**

## 四个项目，四种应用场景

我的实践关注 AI 应用中的完整链路：理解业务要求、选择模型与工具、组织数据、交付交互界面，并为结果设计验证与人工反馈机制。

| 项目 | 解决什么问题 | 代表性设计 | 仓库与案例 |
| --- | --- | --- | --- |
| **[JD Evaluation Calibrator](https://github.com/SimonLecake/jd-rewrite-skill)** | 模型误读招聘要求，人工与 AI 判断不一致 | 17 类误判归纳、规则校准、样本回测 | [查看源码 →](https://github.com/SimonLecake/jd-rewrite-skill) · [案例](projects/jd-evaluation-calibrator.md) |
| **[Bilibili Knowledge Assistant](https://github.com/SimonLecake/bilibili-knowledge-assistant)** | 视频和笔记难以积累、查找与综合使用 | 视频转写、文档入库、多查询 RAG 与排序融合 | [查看源码 →](https://github.com/SimonLecake/bilibili-knowledge-assistant) · [案例](projects/bilibili-knowledge-assistant.md) |
| **[ChatBI Stock Assistant](https://github.com/SimonLecake/chatbi-stock-assistant)** | 一个数据问题需要手动写 SQL、算指标、画图 | 自然语言查询、三个分析工具、只读数据访问 | [查看源码 →](https://github.com/SimonLecake/chatbi-stock-assistant) · [案例](projects/chatbi-stock-assistant.md) |
| **[Steel Defect Inspection](https://github.com/SimonLecake/steel-defect-inspection)** | 检测结果与人工复核、问题样本整理脱节 | YOLO / VLM 双路线、检测记录、审核与导出 | [查看源码 →](https://github.com/SimonLecake/steel-defect-inspection) · [案例](projects/steel-defect-inspection.md) |

## 看实际操作

三段作者实录，点击封面或“观看演示”直接进入对应项目 README 的播放器。看完演示，可继续阅读架构说明、浏览代码或按使用指南运行。

| 钢铁缺陷检测 | B 站知识库助手 | 股票数据分析助手 |
| :---: | :---: | :---: |
| [![钢铁缺陷检测](assets/demos/steel.jpg)](https://github.com/SimonLecake/steel-defect-inspection#实机演示) | [![B 站知识库助手](assets/demos/bilibili.jpg)](https://github.com/SimonLecake/bilibili-knowledge-assistant#实机演示) | [![股票数据分析助手](assets/demos/chatbi.jpg)](https://github.com/SimonLecake/chatbi-stock-assistant#实机演示) |
| **03:10** · [▶ 观看演示](https://github.com/SimonLecake/steel-defect-inspection#实机演示) | **04:05** · [▶ 观看演示](https://github.com/SimonLecake/bilibili-knowledge-assistant#实机演示) | **01:41** · [▶ 观看演示](https://github.com/SimonLecake/chatbi-stock-assistant#实机演示) |
| 双引擎检测 → 审核 → 导出 | 视频处理 → 总结入库 → 问答 | 自然语言 → 分析工具 → 表格与图表 |

录屏与架构图、合成数据图分别标注；演示不等于独立的模型效果评测。

## 这些项目体现了什么

| 能力 | 在项目中的体现 |
| --- | --- |
| **把业务规则写清楚** | 将招聘要求拆解为可执行的判断边界，区分加分项与否决条件 |
| **把模型接入完整流程** | 串联转写、检索、数据库查询、分析工具和可交互界面 |
| **让结果可以检查** | 保留资料来源、结构化结果、检测记录与人工复核入口 |
| **理解工程取舍** | 权衡本地存储、服务调用、只读约束、检索策略与运行成本 |
| **区分实现与效果** | 分别说明工程测试、模型质量、历史记录和待验证方案 |

JD 项目重点展示评估流程设计；Bilibili 与 ChatBI 展示应用实现与集成；钢铁质检基于既有学习实战材料整理，重点展示工程梳理、适配与验证。各案例均说明贡献范围与当前边界。

## 如何阅读与交流

- **快速浏览：** 从上方项目表进入对应 Public 仓库，或阅读精简案例。
- **技术评审：** 各项目 README 提供架构与使用说明；可直接浏览源码，案例页补充价值、取舍与验证范围。
- **进一步交流：** 可通过简历或申请材料中的联系方式讨论实现细节或安排演示。

本仓库汇总项目介绍、截图与演示，源码分别发布在上方四个 Public 仓库中；业务数据、个人语料、凭据及模型权重不随作品集分发。公开状态与使用许可分别说明：目前未统一添加开源许可证，复用时请查看各项目的许可与第三方来源说明。[公开范围与素材说明](PUBLICATION.md)
