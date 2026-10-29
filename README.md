# 你好，我是qyqy

> 我是李卓凡（qyqy）。我做本地优先的 AI 系统：让模型能记住、能自洽，也能被评测。

GitHub：[@qyqy-1109](https://github.com/qyqy-1109) · [个人主页（李卓凡）](https://qyqy-1109.github.io/)

目前主要在做 **旧识 / old-acquaintance**：一个跑在本机的陪伴型对话助手。重点不是聊天界面，而是四层记忆系统——原文、滚动摘要、事实短句 + 向量、遗忘/作废，各自有明确的写入权限和退场方式。

## 现在在做什么

- **记忆写路径**：什么允许进记忆、谁有权改、旧记录怎么退场。
- **可证伪的评测**：规则层 + 裁判层，支持重复跑和离线重评。
- **本地优先**：数据留在本机；没有模型密钥时功能明确降级。

## 精选项目

两件主要作品，和一次 Electron 桌面壳研究。

### 旧识 · old-acquaintance

一个本机陪伴型对话助手，带四层记忆、写路径治理、人格卡片、跨会话搜索和可视化记忆页。

- 四层记忆：原文 → 摘要 → 事实短句 + 向量 → 遗忘/作废
- 世界书、状态槽位、约束、时间轴、生活线、关系与连续性话题
- 人格卡片：原生 JSON / SillyTavern v2 / PNG 角色卡
- 本地优先，SQLite + FastAPI，前端原生 HTML/CSS/JS

[Repository](https://github.com/qyqy-1109/old-acquaintance)

### QuoteLens · quote-lens

多平台 CNC 报价监测与 AI 决策层。

- STEP 上传与预检、原价比价、价格历史、定时监测
- 人工辅助登录，以及 L1 / L2a / L2b 站点接入探索
- 面向真实报价流程的数据采集与决策辅助

[Repository](https://github.com/qyqy-1109/quote-lens)

### Electron 研究 · deepseek-harness-desktop

一次桌面壳研究：验证自包含的 Windows 壳（Electron）如何自动启动本地 `dsh web` 服务，并试验一套 Codex 风格的主题机制。

[Repository](https://github.com/qyqy-1109/deepseek-harness-desktop)

### 其他仓库

更多公开仓库会自动列在 [个人主页](https://qyqy-1109.github.io/) 的 Repositories 区域。

## 工具

`Python` · `FastAPI` · `SQLite` · `OpenAI-compatible APIs` · `HTML / CSS / JS` · `GitHub Actions`

## 链接

- GitHub：https://github.com/qyqy-1109
- 作品集：https://qyqy-1109.github.io/
