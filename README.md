## AI 智能体开发教程

> 一个从零开始学习 AI 智能体（AI Agent）开发的中文教程系列，通过循序渐进的案例，带你掌握提示词工程、大模型 API 调用、智能体应用构建以及 LangChain / LangGraph 等主流框架。此外，本教程还会以工程化项目为例，讲解 MCP、RAG、Milvus、RFF、Query Rewrite 等技术在 AI 智能体开发中的应用。

### 教程目录

>**说明**：内容仍在持续创作和更新中。

| 章节 | 标题 | 内容简介 |
| ---- | ---- | -------- |
| 01 | [AI 智能体开发入门](01.AI智能体开发入门.md) | 什么是 AI 智能体、适用业务场景分析、通过 API 接入大模型（以 DeepSeek 为例） |
| 02 | [提示词和 Skills](02.提示词和Skills.md) | 提示词工程核心技巧、Few-shot、思维链（CoT）、ReAct、Skills 等进阶玩法 |
| 03 | [大模型能帮我们做什么](03.大模型能帮我们做什么.md) | 文本概括、文本分类等实战案例，动手打造网页摘要生成助手 |
| 04 | [自己动手撸一个聊天机器人](04.自己动手撸一个聊天机器人.md) | 使用 Streamlit 构建可交互、可部署的对话式 AI 聊天机器人 |
| 05 | [使用 LangChain 构建 AI 智能体](05.使用LangChain构建AI智能体.md) | LangChain 生态体系、核心概念与工程化实践，系统构建可维护的智能体应用 |
| 06 | [LangGraph 快速上手指南](06.LangGraph快速上手指南.md) | 状态（State）、节点（Nodes）、边（Edges）、工具调用、多 Agent 协同等核心概念 |

### 技术栈

- **编程语言**：Python
- **大模型**：DeepSeek、Kimi 等
- **智能体框架**：LangChain、LangGraph
- **API 接口**：FastAPI
- **数据库**：PostgreSQL、Milvus、Redis、MongoDB 等
- **UI 框架**：Streamlit 等

### 环境准备

- 注册并获取大模型 API Key（如 [DeepSeek](https://platform.deepseek.com/)），参考教程第一章的申请步骤。
- 安装 Python 3.12 或 Miniconda 3，创建运行 Python 项目的虚拟环境。
- 按章节提示在虚拟环境中安装 `requests`、`streamlit`、`langchain`、`langgraph` 等依赖项。

### 项目结构

```text
AI-Agent-Engineering/
├── 01.AI智能体开发入门.md
├── 02.提示词和Skills.md
├── 03.大模型能帮我们做什么.md
├── 04.自己动手撸一个聊天机器人.md
├── 05.使用 LangChain 构建 AI 智能体.md
├── 06.LangGraph 快速上手指南.md
├── res/
├── code/
└── README.md
```

## 许可

本教程仅供学习交流使用。
