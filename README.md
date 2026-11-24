# 👋 行路客 · 刘仁杰

### Senior AI Agent / Applied AI Engineer
**Agent Platform & Backend · 生产级 AI Agent · 后端平台工程**

> 求职中 · 接受远程 · 具备纽约公司跨时区协作经验

9 年后端平台与复杂业务系统交付经验，近年专注 **AI Agent 从工具编排到生产运行的工程化落地**。

曾远程参与纽约公司企业级 AI 运营平台建设，重点负责 **语音与拨号链路、客户问题闭环和系统包轻量化**，将系统启动时间缩短 **80%**，人工投诉减少约 **50%**。同时具备 MCP 运维 Agent、企业 RAG、多智能体应用与高并发数据平台的交付经验。

以 **Go、TypeScript、Java、Python** 为主要工程语言，可覆盖 Agent 编排、后端服务、数据链路、Web 应用与部署运维。

## 🧭 找到我

- 💻 **GitHub**：[liu51949822](https://github.com/liu51949822)
- ✉️ **邮箱**：[1240332437@qq.com](mailto:1240332437@qq.com)
- 📝 **技术博客**：[CSDN · 行路客](https://blog.csdn.net/weixin_45530192)
- 📦 **AI 云开发库**：[Gitee · raglib](https://gitee.com/callmeprice/raglib)
- 🤝 **关注机会**：AI Agent / Applied AI Engineer / Agent Platform / Backend Engineer

---

## 🛠 核心技术

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

| 方向 | 技术与实践 |
| :--- | :--- |
| **Agent 工程** | OpenAI Agents SDK、ReAct、planner/executor、Function Calling、Multi-Agent、MCP/FastMCP、工具编排、上下文与权限管理、人工接管、审计与回放 |
| **RAG 与评估** | LangChain、LangGraph、Dify、Milvus、FAISS、多源知识 ETL、Braintrust、LLM Judge、场景回归、提示词与工具契约优化 |
| **语音与工作流** | ElevenLabs、Twilio、Deepgram、实时转写、呼入/呼出、转接、通话后处理、Temporal 长流程 |
| **后端与数据** | Go、TypeScript/Node.js、Java、Python、Spring Boot、GraphQL Yoga、Kysely、PostgreSQL/Aurora、MySQL、Redis、Kafka、MQTT、TDengine |
| **平台与可观测性** | Docker、Kubernetes/EKS、Pulumi、GitHub Actions、Jenkins、Datadog、OpenTelemetry、Prometheus、Grafana、ELK |
| **Web 与自动化** | React、Next.js、Vue、Playwright、Cheerio、Stagehand、Steel |
| **远程协作工具** | Slack、Dash、Zoom、Google Meet、Microsoft Teams、Notion、Jira、Linear、GitHub Pull Requests、GitLab、飞书 |

---

## 💼 生产项目与交付

### 🎙️ Zingage · 企业级 AI Home Care Operations Platform

**Agent 软件工程师｜纽约公司 · 远程｜2026.01–2026.10**

面向美国居家护理机构的 AI 运营平台，将电话、短信和 EMR 事件转化为可追踪工单，由 Agent 完成信息理解、任务路由、人员匹配、外部联系和结果回写。

- **语音链路交付**：重点负责 ElevenLabs + Twilio + Deepgram 集成，覆盖呼入/呼出、拨号发起、状态跟踪、实时转写、转接及通话后处理，与 Temporal 工作流和 TypeScript 后端完成端到端衔接。
- **生产问题闭环**：结合应用日志、调用追踪和工作流状态定位跨服务故障，持续修复客户反馈与历史遗留问题，使人工投诉减少约 **50%**。
- **启动性能优化**：梳理运行时依赖、包边界与构建内容，在保持业务行为不变的前提下，将系统启动时间缩短 **80%**。
- **评估与回归**：参与构建覆盖 **167 个场景**的语音评估与 CI 回归流程，通过数据集和 LLM Judge 验证模型、提示词及链路变更。
- **远程工程协作**：按纽约时区晚间在线协作，保持日均约 **3 个 PR** 的交付节奏，参与 Agent 编排、多租户后端、EMR 集成及生产基础设施交付。

### 🚛 Titan · MCP 运维 Agent 与企业 RAG

**云平台开发工程师（AI 工程化方向）｜2024.01–2026.01**

将 Agent、知识检索与 Go 高并发后端应用于无人矿车生产场景。

- **MCP 运维巡检**：使用 Go 实现 MCP Server，封装服务器监控、日志拉取和钉钉告警工具，结合定时任务、上下文管理与异常模式匹配实现无人值守巡检；稳定运行 **6 个月**，处理 **200+ 条告警**，准确率超过 **95%**，异常响应时间缩短至 **3 分钟内**。
- **企业知识库**：构建 Jira、GitLab、飞书等多源数据的采集、清洗与向量化 ETL，结合 Milvus 提供检索；新人上手周期由 **4 周缩短至 2 周**，技术方案搜索效率提升 **60%**。
- **车云通信网关**：使用 Go + MQTT 重构通信服务，支撑 **1,000+ 矿车同时在线**，消息延迟低于 **200 ms**；通过协程池与 Channel 优化，资源占用较原 Java 版本降低 **40%**。
- **实时数据平台**：独立搭建 Kafka → TDengine 管道，处理 **200+ 类传感器指标**；存储成本较 MySQL 降低 **65%**，写入吞吐提升 **3 倍**。

---

## 🚀 开源项目

### 🪞 Multi-Agent Disease Diagnosis System

**面向海外美容医疗咨询的多智能体应用**

[![Repository](https://img.shields.io/badge/GitHub-Multi--Agent--Disease--Diagnosis--System-181717?style=for-the-badge&logo=github)](https://github.com/liu51949822/Multi-Agent-Disease-Diagnosis-System)

`TypeScript` · `LangGraph.js` · `ReAct` · `RAG` · `Gemini` · `SSE`

- **多智能体编排**：通过 Coordinator 路由与专业 Agent 分工，实现任务拆解、上下文传递和结果融合，减少重复检索与输出冲突。
- **领域知识建设**：使用 Playwright、Cheerio 采集并结构化处理医美知识、药品说明和合规案例，构建 RAG 领域语料。
- **完整工具链路**：围绕“诉求输入 → 病史分析 → 知识检索 → 合规校验 → 方案生成 → 风险告知”组织工具调用。
- **多模态与记忆**：结合照片分析、短期会话摘要、长期用户档案和向量语义回忆，支持连续咨询。
- **安全与质量**：引入 HITL 确认、确定性禁忌症核对、结构化输出校验、自反思及 Evals 评估。

> 用于咨询辅助与工程实践，不替代专业医疗诊断或治疗建议。

### 🏋️ Workout Routine Agent

**从单文件 CLI 演进的全栈 AI 健身教练**

[![Repository](https://img.shields.io/badge/GitHub-workout--routine--agent-181717?style=for-the-badge&logo=github)](https://github.com/liu51949822/workout-routine-agent)

`Python` · `FastAPI` · `LangGraph` · `FAISS` · `React Native / Expo`

- **RAG 工程链路**：文档加载、切块、FAISS 持久化、检索工具与 LangGraph Agent 集成。
- **流式交互**：FastAPI 提供 REST API 与 SSE Token 流式输出。
- **移动端产品**：覆盖 AI 教练、训练计划、练习库、周历、进度与个人档案等页面。
- **记忆与交付**：支持短期摘要、长期档案和向量回忆，结合自动化测试与 GitHub Actions 完成 Android APK / Web 构建。

### 📚 AI 云开发库与技术博客

**把项目经验沉淀为可复用的知识与工具**

- 独立开发 Next.js 全栈博客与 RAG 知识库问答系统。
- 将重复任务、业务流程和工程约束整理为 SOP / Markdown 文档，支持 AI 辅助研发与 Agent 协同。
- [Gitee · AI 云开发库](https://gitee.com/callmeprice/raglib) · [CSDN · 技术博客](https://blog.csdn.net/weixin_45530192)

---

## 🏗️ 后端与技术管理经历

### 中科大脑 · 技术经理

**2020.03–2024.01**

- **工程质量体系**：建设需求优先级、Jira 任务、代码需求 ID 到测试覆盖的端到端追溯，落地 Git Hooks、SonarQube、JaCoCo、OWASP ZAP 和 Code Review 质量门禁，将缺陷密度控制在 **0.5/千行以内**。
- **飞控平台**：负责多级账户、权限与数据隔离，交付 KML 航线处理、飞行任务调度及 Kafka + ELK 实时日志链路。
- **智慧城市交付**：主导核心服务后端建设，负责多租户隔离、权限体系与实时数据管道，并协调客户需求和多方交付。

### 杰克集团 · Java 开发工程师

**2017.01–2020.03**

- **MES 与工厂自动化**：参与黑灯工厂 MES 建设，打通下单、产线调度、AGV 搬运到取件的自动化链路，支持 **7×24 小时运行**。
- **AGV 调度**：使用 Netty 实现长连接调度，支持 **5 台小车并发无冲突运行**，任务分配效率提升 **30%**。
- **流程编排**：设计支持动态工序与条件触发的生产流程编排引擎。

---

## 🎓 教育背景

**苏州大学应用技术学院** · 本科 · 自动化 · 2017 年毕业

---

**让 Agent 不止能演示，更能接入业务、稳定运行、持续评估。**

*路虽远，行必至。* 🌟
