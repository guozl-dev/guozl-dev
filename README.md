# 郭正立 · guozl-dev

**AI 应用 / Agent 工程方向 · 2026 届物联网工程本科**

用 Python 写后端与 AI 应用，也把 Agent 运行时的每一层拆开重写过一遍。
关注 LLM 应用工程化、Agent 运行时设计，以及「检索质量如何被度量」。

[mini-agent-harness](https://github.com/guozl-dev/mini-agent-harness) · [saltline-ext](https://github.com/guozl-dev/saltline-ext) · [邮箱](mailto:re_guozl@163.com)

---

## 精选项目

### [mini-agent-harness](https://github.com/guozl-dev/mini-agent-harness) — 从零手搓的轻量 Agent 运行时

[![CI](https://github.com/guozl-dev/mini-agent-harness/actions/workflows/ci.yml/badge.svg)](https://github.com/guozl-dev/mini-agent-harness/actions/workflows/ci.yml)
[![Secret Scan](https://github.com/guozl-dev/mini-agent-harness/actions/workflows/secret-scan.yml/badge.svg)](https://github.com/guozl-dev/mini-agent-harness/actions/workflows/secret-scan.yml)
![Python](https://img.shields.io/badge/python-3.11%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

不依赖 LangChain / LangGraph，直接回答 Agent 的四个问题：**loop 怎么转、状态放哪、上下文怎么裁、工具边界画在哪**。

- **可演示**：`python scripts/demo_self_repair.py` —— 给仓库自身注入 bug，AI 跑测试、读失败、改代码、重跑到全绿
- **可量化**：规划式召回 vs 朴素 top-k，Hit@3 由 14% 提升到 100%（8 篇语料 / 7 题的小样本回归，不代表线上效果）
- **可维护**：57 个测试、覆盖率 93%、ruff + CI 门禁 + gitleaks 密钥扫描

### [saltline-ext](https://github.com/guozl-dev/saltline-ext) — 浏览器 FPS 的扩展与汉化

单文件浏览器 FPS 的扩展版本：原版游戏逻辑零改动，全部新功能以独立模块追加——枪械配置切换、昼夜主题、准星自定义、伤害飘字、击杀信息流、战绩存档等 7 项。仅供学习研究。

---

## 技术栈

| 方向 | 在用 |
|---|---|
| 语言 | Python、Java、SQL、TypeScript（基础） |
| 后端 | FastAPI、Spring Boot、MySQL、Redis、RESTful API、Linux |
| AI 应用 | LLM API 接入、Prompt 设计、RAG、Function Calling；了解 Agent 编排（LangGraph）与端侧推理部署链路 |
| 测试与工程 | pytest、JMeter、Charles、Git、Jenkins、GitHub Actions、Docker（基础） |
| 嵌入式（课程实践） | STM32、Keil MDK / CubeMX、RT-Thread、Proteus 仿真 |

## 当前在做什么

- 继续打磨 mini-agent-harness：把自闭环修复接入 CI、扩充检索评测语料
- 补工程短板：TypeScript 深入、Docker 实战
- **求职中**：AI 应用 / 后端 / 测试方向，2026 届校招，可立即到岗

## 其他项目（未开源）

- **智慧工厂数据管理平台**：设备数据链路开发与联调——传感器数据模拟、断线重连、异常报文注入，实时推送延迟 < 200ms
- **基于内容推荐的二手交易网站**：推荐功能从需求到上线，F1 0.86，支撑日均万级请求
- **嵌入式课程实践**：STM32 外设实验；RT-Thread 中断管理、互斥量与优先级继承、消息队列

## 联系

- Email：[re_guozl@163.com](mailto:re_guozl@163.com)
- 仓库里的问题，欢迎直接开 Issue
