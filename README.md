# 羊鸣天 · Yang Mingtian

**2027 届｜重庆邮电大学｜AI 应用开发 / Java 全栈**

用 Java / Spring Boot 构建业务后端，用 Python / LLM 开发 AI 应用与工具。关注文档智能、Agent 工具、订单库存一致性，以及有明确验证边界的工程交付。

[个人作品集](https://yoruming.cn/) · [在线简历](https://yoruming.cn/resume) · [项目列表](https://yoruming.cn/projects)

## 代表经历与项目

| 项目 | 角色与状态 | 重点 |
|---|---|---|
| [智能标书锚点解析系统](https://yoruming.cn/projects/ai-zhaobiao) | 邮莱特实习项目｜参与研发｜源码不公开 | LLM-first 信息抽取、OCR / PageIndex 证据定位、接口联调与回归验证 |
| SlotFlow | 个人项目｜限量预约业务原型 | Agent 查询与草稿、用户独立确认；订单与库存事务、幂等、Outbox / Inbox 及模拟供应商超时恢复 |
| [门诊管理平台](https://yoruming.cn/projects/nautilus-clinic) | 个人项目｜[公开仓库](https://github.com/Yorushikamimimi/nautilus-clinic) | 患者、处方发药与库存业务串联，聚焦 RBAC、条件库存扣减和事务一致性 |

SlotFlow 已完成本地业务验证与隔离云端后端的小规模验证，供应商为模拟实现。

## Agent Skills 与实用工具

| 项目 | 用途 |
|---|---|
| [system-mental-model](https://github.com/Yorushikamimimi/system-mental-model) | 从业务流程理解系统，用实际回答、变式和证据检查理解的学习 Skill |
| [docdoc](https://github.com/Yorushikamimimi/docdoc) | 面向 Codex 的 Word 文档局部修改 Skill 与 MCP，检查非目标内容的意外变化 |
| [codex-thread-handoff](https://github.com/Yorushikamimimi/codex-thread-handoff) | 基于权威来源恢复长期任务上下文，支持接管验证与验收后切换 |
| [Sunge](https://github.com/Yorushikamimimi/Sunge) | 用 Markdown / Obsidian 保存个人记录与目标，帮助 AI 对话从文件接续上下文的非官方框架 |
| [ai-context-vault](https://github.com/Yorushikamimimi/ai-context-vault) | 面向 Obsidian 与 AI 助手的个人上下文档案模板，按任务提供必要信息 |

另有自用的 macOS **文件整理助手**：选择来源、预览确认、按类型整理与会话多批撤销；已打包为依赖本机 Python / Tk 的 App，仓库保持私有。

## 更多公开工程

| 项目 | 工程定位 |
|---|---|
| [rag-nexus](https://github.com/Yorushikamimimi/rag-nexus) | Spring AI + pgvector 全栈 RAG 原型，包含多源注入、向量召回、SSE 流式问答与来源展示 |
| [nautilus-media-cloud](https://github.com/Yorushikamimimi/nautilus-media-cloud) | PostgreSQL `SKIP LOCKED` Pull 型异步任务调度，包含 Spring Boot 控制面与 Python Worker |
| [My Knowledge Base](https://github.com/Yorushikamimimi/My-Knowledge-Base) | 早期 Dify 知识库版本；后续本地 RAG 演进与验证边界见[作品集说明](https://yoruming.cn/projects/my-knowledge-base) |

## 技术关键词

- **AI 应用：** Python、FastAPI、LLM API、Spring AI、OCR、RAG、pgvector
- **业务后端：** Java、Spring Boot、MyBatis、MySQL、PostgreSQL、Redis、RabbitMQ
- **前端：** React / Vite、Vue、TypeScript
- **工程工具：** Docker、Linux、Git、REST API、MCP、Agent Skills

重视业务问题、实现依据和可重复验证；测试结果按具体环境与覆盖范围说明。
