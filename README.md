# my-skills

A curated collection of reusable AI agent skills for planning, development, tooling, and knowledge work.

---
### Overview

This repository contains a growing collection of reusable skills designed to improve how I work with AI coding agents such as Codex, Cursor, and other development assistants.

The goal of this repository is to turn repeatable workflows into structured, reusable skills so that I do not need to rewrite the same long prompts again and again.

These skills are organized into four categories:

- **planning-design** — clarify requirements, shape plans, and define direction before implementation
- **development** — implement, debug, refactor, and improve code structure
- **tooling-setup** — standardize engineering workflows and local project setup
- **writing-knowledge** — improve writing quality, terminology consistency, and knowledge organization

### Repository Structure

```text
.
├─ planning-design/
│  ├─ grill-me/
│  ├─ request-refactor-plan/
│  ├─ to-issues/
│  └─ to-prd/
├─ development/
│  ├─ improve-codebase-architecture/
│  ├─ tdd/
│  └─ triage-issue/
├─ tooling-setup/
│  ├─ git-guardrails/
│  └─ setup-pre-commit/
├─ writing-knowledge/
│  ├─ edit-article/
│  ├─ ubiquitous-language/
│  └─ write-a-skill/
└─ README.md
```

### Categories

#### planning-design

Skills for thinking before building.

This category is focused on:
- requirement clarification
- PRD creation
- task breakdown
- design direction
- refactor planning

Current skills:
- `grill-me`
- `request-refactor-plan`
- `to-issues`
- `to-prd`

#### development

Skills for implementation and code improvement.

This category is focused on:
- test-driven development
- issue triage
- refactoring
- architecture improvement
- development execution

Current skills:
- `improve-codebase-architecture`
- `tdd`
- `triage-issue`

#### tooling-setup

Skills for project tooling and engineering guardrails.

This category is focused on:
- repository safety
- commit discipline
- local tooling setup
- workflow consistency

Current skills:
- `git-guardrails`
- `setup-pre-commit`

#### writing-knowledge

Skills for documentation, writing quality, and knowledge systems.

This category is focused on:
- article editing
- terminology consistency
- writing reusable skills
- knowledge organization

Current skills:
- `edit-article`
- `ubiquitous-language`
- `write-a-skill`

### Design Principles

This repository follows a few simple principles:

#### Reusable
Each skill should solve a repeatable problem or workflow.

#### Focused
Each skill should have a clear purpose instead of trying to do everything.

#### Actionable
A skill should tell the agent what to do, when to do it, and what kind of output is expected.

#### Maintainable
Skills should stay understandable and easy to improve over time.

### Why This Repository Exists

I use this repository as a personal skill library and workflow system.

Instead of relying on scattered prompts, I organize proven working patterns into reusable skills that can be improved, versioned, and reused across projects.

This repository is intended to become:
- a personal agent workflow library
- a reusable prompt-to-skill system
- a structured collection of development habits
- a long-term knowledge base for AI-assisted work

### Future Direction

This repository will continue to grow with more skills for:
- project planning
- coding workflows
- debugging and review
- refactoring and architecture
- documentation and communication
- team-oriented engineering practices

---

### 仓库说明

这个仓库用于我在使用 Codex、Cursor 以及其他 AI 开发助手时反复使用的技能（skills）。

核心目标是把高频、可复用、可标准化的工作流整理成结构化 skill，避免每次都重新编写冗长提示词。

当前仓库按四个方向进行分类：

- **planning-design**：在真正动手前先把需求、方案和方向理顺
- **development**：围绕编码实现、排障、重构和架构优化展开
- **tooling-setup**：沉淀工程化配置、提交流程和本地开发规范
- **writing-knowledge**：整理文档、术语、文章和知识沉淀相关流程

### 仓库结构

```text
.
├─ planning-design/
│  ├─ grill-me/
│  ├─ request-refactor-plan/
│  ├─ to-issues/
│  └─ to-prd/
├─ development/
│  ├─ improve-codebase-architecture/
│  ├─ tdd/
│  └─ triage-issue/
├─ tooling-setup/
│  ├─ git-guardrails/
│  └─ setup-pre-commit/
├─ writing-knowledge/
│  ├─ edit-article/
│  ├─ ubiquitous-language/
│  └─ write-a-skill/
└─ README.md
```
## Skill 速查表

| Skill | 用途 | 注意点 |
| --- | --- | --- |
| `tdd` | 红绿重构，用行为测试驱动开发或修 bug | 强调“一个测试、一个实现”，测试公共接口，不测实现细节 |
| `triage-issue` | 调查 bug 根因，生成带 TDD 修复计划的 GitHub issue | 假设可用 `gh issue create`，会写 GitHub issue |
| `qa` | 交互式 QA，把用户报告的问题整理成 GitHub issue | 要求 issue 不写文件路径/行号，偏用户行为描述 |
| `github-triage` | GitHub issue 标签状态机 triage | 会读写 issue、评论、标签；要求所有 AI 评论带 disclaimer |
| `to-prd` | 把当前上下文合成 PRD 并提交为 GitHub issue | 要求先理解代码库，不做长访谈 |
| `to-issues` | 把 PRD/计划拆成可独立领取的垂直切片 issue | 强调 AFK/HITL、依赖关系、验收标准 |
| `request-refactor-plan` | 访谈式生成细粒度重构计划，再提交 GitHub issue | 适合大重构前先规划，不直接改代码 |
| `improve-codebase-architecture` | 找架构改进点，尤其浅模块合并为深模块 | 依赖 `REFERENCE.md`，会倾向创建 refactor RFC issue |
| `design-an-interface` | 为模块/API 生成多个差异化接口设计并比较 | 原文要求并行子代理；我会按当前 Codex 权限规则适配 |
| `grill-me` | 对方案或设计进行高强度追问 | 一次问一个问题，适合需求不清时 |
| `domain-model` | 用 DDD 术语审问方案，并维护 `CONTEXT.md`/ADR | 会写文档；带 `disable-model-invocation: true` |
| `ubiquitous-language` | 从对话中提取领域词汇表到 `UBIQUITOUS_LANGUAGE.md` | 会创建或更新本地文档 |
| `zoom-out` | 要求从更高层解释代码区域和调用关系 | 很短的辅助 skill，也有 `disable-model-invocation: true` |
| `migrate-to-shoehorn` | 把测试里的 `as` 断言迁移到 `@total-typescript/shoehorn` | 只用于测试代码；安装依赖需要网络和权限 |
| `setup-pre-commit` | 配置 Husky、lint-staged、Prettier、typecheck/test hook | 会改配置、安装依赖，甚至提交 commit，使用前要明确授权 |
| `git-guardrails-claude-code` | 给 Claude Code 加阻止危险 git 命令的 hook | Claude Code 专用；脚本依赖 bash 和 `jq` |
| `scaffold-exercises` | 按课程/练习结构创建 exercise 目录 | 会创建文件夹/readme，并运行 `pnpm ai-hero-cli internal lint` |
| `write-a-skill` | 创建新的 skill 目录和 `SKILL.md` | 和当前系统里的 `skill-creator` 类似，但更简洁 |
| `edit-article` | 编辑文章结构和表达 | 会先按标题分段并确认结构 |
| `obsidian-vault` | 管理 Obsidian vault 笔记 | 原路径是 WSL 风格 `/mnt/d/...`，当前 Windows 环境换成 `D:\...` |
| `caveman` | 极简压缩沟通模式 | 一旦触发会持续，直到用户说停止或恢复正常 |


### 分类说明

#### planning-design

这一类 skill 用于“先想清楚，再开始做”。

主要适用于：
- 需求澄清
- PRD 整理
- 任务拆解
- 方案规划
- 重构前分析

当前包含：
- `grill-me`
- `request-refactor-plan`
- `to-issues`
- `to-prd`

#### development

这一类 skill 用于“真正开始开发、排查和优化代码”。

主要适用于：
- TDD 开发
- 问题排查
- 重构执行
- 架构改进
- 开发流程推进

当前包含：
- `improve-codebase-architecture`
- `tdd`
- `triage-issue`

#### tooling-setup

这一类 skill 用于“工程化配置和开发流程守护”。

主要适用于：
- Git 规范
- 提交流程约束
- 本地工具初始化
- 开发流程统一
- 项目安全护栏

当前包含：
- `git-guardrails`
- `setup-pre-commit`

#### writing-knowledge

这一类 skill 用于“文档、写作与知识体系整理”。

主要适用于：
- 文档润色
- 术语统一
- skill 编写
- 知识沉淀

当前包含：
- `edit-article`
- `ubiquitous-language`
- `write-a-skill`

### 设计原则

这个仓库中的 skill 尽量遵循以下原则：

#### 可复用
优先沉淀高频且可重复使用的流程。

#### 单一职责
每个 skill 聚焦解决一类明确问题，不追求大而全。

#### 可执行
不仅要说明“做什么”，还要说明“怎么做”“何时做”“产出什么”。

#### 易维护
尽量让 skill 保持清晰、可读、可持续优化。

### 为什么要做这个仓库

我把这个仓库当作个人的 skill 库和 AI 工作流沉淀仓库。

相比零散地保存提示词，我更希望把已经验证有效的方法整理成长期可维护、可版本化、可复用的 skill。

这个仓库会逐步成为：
- 我的个人 AI 工作流仓库
- 可复用的技能模板库
- 开发方法论沉淀库
- 长期演进的知识资产仓库

### 后续规划

后续可能会继续补充更多适用于以下场景的 skill：
- 项目需求规划
- 编码与调试
- 代码审查与重构
- 架构治理
- 文档整理与沟通协作
- 更适合团队使用的工程实践

---


 
后续会不断补充新 skill，并持续优化已有 skill。
