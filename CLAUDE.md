# CLAUDE.md

本文件为 Claude Code (claude.ai/code) 在此仓库中工作时提供指导。

## 项目概述

Python 项目，使用 Playwright MCP 进行浏览器自动化。目前处于早期/探索阶段。

## 工具

- **Playwright MCP** — 可通过 `mcp__playwright__*` 系列工具进行浏览器自动化操作（导航、截图等）。会话日志写入 `.playwright-mcp/` 目录。
- **Git** — 仓库已连接 GitHub（`origin` 远程仓库）。用户：FuSu1313。

## 架构

`demo.py` 是唯一的源文件（目前为桩代码）。尚未建立包结构、测试框架或构建系统。
