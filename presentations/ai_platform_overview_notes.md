# AI 平台：2018.5 — 2025.5 (Mike's PPT)

## 概要
- 封面名称: Mike's PPT
- 时间范围: 2018.5 — 2025.5
- 主题色: 科技感绿色（深绿→青绿渐变）
- 字体: 思源黑体/Inter（中英混排）

## 幻灯片清单（共 6 页）
1. 封面页
   - 标题: AI 平台：2018.5 — 2025.5
   - 副标题: Mike's PPT
   - 简短定位: 专注构建企业级 AI Infra 与 AI 平台，覆盖 MLOps/LLMOps 与 ToB/ToG 解决方案
   - 视觉: 深绿渐变背景, 白色大标题, 右下角可放团队 logo
   - 演讲者备注: 简短介绍本人/团队，突出时间范围与跨平台能力

2. 总览页（主展示页）
   布局: 左侧竖列（时间线 + 角色/一句话定位）；右侧主区分三部分
   - 左侧（约 30% 宽）
     - 时间线: 2018.5 — 2025.5，标注关键里程碑（可编辑）
     - 角色/职责一句话: 构建企业级 AI 平台与解决方案，推动跨业务落地
     - 能力徽章: 华为内部各业务流程+AI、各垂直行业 AI 基础设施及解决方案、DevOps 流程
     - 演讲者备注: 简述个人/团队在平台建设中的核心贡献

   - 右侧上: 平台与产品卡（每项为可编辑卡片）
     - AI Infra 平台
     - MLOps 平台
     - LLMOps 平台
     - 模型训练与推理平台
     - L1 LLM 增训/微调
     - AI 使能平台（RAG、AI Agent 框架）
     - ToB/ToG AI 解决方案
     - 演讲者备注: 快速逐项概述每个平台的职责和交付成果

   - 右侧中: 技术栈 ↔ 产品映射图（4 列）
     列: AI Infra / AI Platform / AI Enable Platform / AI Solution
     行（技术项示例, 可编辑）:
       - 容器与调度: Kubernetes, Docker
       - 分布式训练框架: Horovod, BytePS, Petastorm
       - 模型仓库: MLflow, ModelDB
       - 数据平台: Data Lake, Kafka, Feature Store
       - 推理服务: Triton, TensorFlow Serving, ONNX Runtime
       - 增训/微调: LoRA, Delta Tuning, Instruction Tuning 流程
       - RAG 服务: Vector DB (Milvus/Pinecone), Embedding 服务
       - Agent 框架: LangChain-like, Custom Orchestrator
       - 监控/DevOps: Prometheus, Grafana, CI/CD (Jenkins/GitHub Actions)
     映射方式: 用色块或连线展示每个技术项在哪些产品列中被使用/负责
     演讲者备注: 强调跨层协同、责任边界与复用能力

   - 右侧下: 竞争者矩阵（含 Logo）
     - 列表/小矩阵: Azure AI | AWS AI | 阿里云 AI | OpenSource
     - 定位简述: 我方差异化为“面向企业的定制化解决方案 + 深度行业集成”
     - Logo 风格: 彩色官方 Logo（占位），请在 PR 后替换为合规版本
     - 演讲者备注: 对比竞品优势/短板，突出我们在行业适配与流程集成的能力

   - 底部横条: KPI 与能力摘要（示例已填）
     - 覆盖业务线: 12 个
     - 部署频次/年: 48 次
     - 训练成本下降: 22%
     - 推理延迟改善: 30%
     - 演讲者备注: 如无具体数据可替换为占位

3-6. 详细页（每页对应 1 个子平台，示例结构如下）
   - 页面头部: 平台名称
   - 平台简介: 目标/定位（1 段）
   - 关键技术栈: 列表
   - 示意架构占位: 插入占位图或留空以便替换真实架构截图
   - 主要功能点: 3-5 个要点
   - KPI/成果: 填入可量化数据或占位
   - 关键挑战与解决方案: 2-3 行
   - 演讲者备注: 提供 2-3 句讲稿提示

示例：

- 详细页：AI Infra
  - 简介: 构建稳定、弹性的计算与存储基础设施，支持分布式训练与大规模推理
  - 关键技术: Kubernetes, GPU 云构建, 分布式文件系统, 网络加速
  - 功能点: 弹性集群管理、资源配额与隔离、成本监控
  - KPI: GPU 利用率提升 18%、训练排队时间减少 40%
  - 挑战与策略: 成本控制 -> 引入自动伸缩策略与 Spot 实例
  - 演讲者备注: 强调稳定性与成本控制能力

- 详细页：MLOps / LLMOps
  - 简介: 提供模型生命周期管理、CI/CD、模型质量回归检测与试验对比
  - 关键技术: MLflow, Model Registry, CI/CD pipelines, 可复现训练流水线
  - 功能点: 模型管理、自动化训练、A/B 实验平台、灰度部署
  - KPI: 版本回滚时间 < 30 分钟; 模型上线周期从 4 周缩短至 2 周
  - 演讲者备注: 强调效率与可靠性

- 详细页：AI Enable Platform (RAG / AI Agent)
  - 简介: 提供检索增强生成、向量检索、上下文管理与多模态 Agent 支撑
  - 关键技术: Embeddings 服务, Vector DB, Prompt 管理, Agent Orchestrator
  - 功能点: 上下文检索、知识注入、工具调用与策略管理
  - KPI: RAG 检索准确率提升 12%, 用户交互满意度 +9%
  - 演讲者备注: 强调业务场景的落地效果

- 详细页：AI Solution (ToB/ToG)
  - 简介: 面向行业客户提供定制解决方案，包含部署、集成与运维保障
  - 关键技术: 行业数据接入层、合规/隐私工具、接入 SDK
  - 功能点: 行业模型库、可视化仪表盘、行业流程自动化
  - KPI: 客户部署周期 3 周; 客户满意度评分 4.6/5
  - 演讲者备注: 强调行业适配与运维保障能力

## 竞品对比（示例文案）
- Azure AI: 企业级服务、生态完整、企业集成强
- AWS AI: 规模与服务广度、成熟的基础设施
- 阿里云 AI: 国内云服务整合、对本地化合规支持强
- OpenSource: 灵活、成本低但需要更多工程化投入
- 我方定位: 在行业落地、流程集成与定制能力上具备优势
- 演讲者备注: 简短点出三项差异化（行业数据连接、定制化训练、运维交付）

## 演讲者备注（每页）
- 我会为每页加入 2-3 行演讲稿提示，简洁明了，帮助面试时快速讲解关键点。

## 交付物
- presentations/ai_platform_overview_2018-2025.pptx （占位 pptx，等待替换为真实 pptx 二进制文件）
- presentations/ai_platform_overview_notes.md （本文件，包含逐页文本、演讲备注与替换指南）

## 版权与 Logo
- 竞品 Logo 采用彩色官方 Logo 的占位，实际分享或公开时请确认合规授权。

## PR/提交信息
- 分支: add-ai-platform-ppt
- 提交信息: Add AI platform overview PPT (green theme) with detailed pages
- PR 标题: Add AI 平台（2018.5—2025.5）演示 PPT
