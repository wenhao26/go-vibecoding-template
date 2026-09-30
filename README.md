# Go AI Agent 开发规范与生产级脚手架模板

本项目提供了一套完整的生产级 Go 开发规范与 AI Agent（支持 OpenCode、Cursor、Claude Code 等）行为约束体系。

## 目录结构说明

- `AGENTS.md` - 根目录下的全局 AI 行为约束与修改工作流指南[cite: 1, 16]
- `docs/README.md` - 规范地图与文档路由索引[cite: 16]
- `docs/development/` - 涵盖架构、API、数据库、安全、日志、测试等 12 份工程细则[cite: 16]

## 快速使用

1. 点击本仓库右上角 **Use this template** 创建新项目。
2. 根据新项目的具体业务，快速微调：
   - `docs/development/domain.md` (业务词汇表与状态机)[cite: 14, 16]
   - `docs/development/dependencies.md` (依赖包白名单)[cite: 11, 16]
   - `docs/development/environment.md` (本地 Docker/Makefile 环境)[cite: 9, 16]
3. 直接使用 OpenCode 或 Cursor 开启高质高效的 Vibe Coding！
