# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 常用命令

仓库内未提供统一的构建、测试或 lint 命令说明；README 主要是安装与使用说明。若需要补充，请在仓库根目录 README 或相应子目录 README 中添加。

## 仓库架构概览

- 根目录 README 介绍 Claude Code 的安装与使用方式，以及插件入口。
- `plugins/` 目录包含官方示例插件。插件通过 `.claude-plugin/plugin.json` 描述元数据，并可包含 commands/、agents/、skills/、hooks/ 等组件，体现 Claude Code 的插件扩展体系。
- `plugins/README.md` 汇总了各插件的功能与入口命令/技能，适合作为插件索引。
- `examples/` 目录包含设置文件示例（`examples/settings/`），展示不同安全与权限配置的组合。
- `scripts/` 与 `Script/` 目录包含仓库维护脚本。