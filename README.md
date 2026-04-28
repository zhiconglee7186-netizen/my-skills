# my-skills

A curated collection of reusable AI agent skills for planning, development, frontend design, tooling, and knowledge work.

---

## Overview

This repository contains a growing collection of reusable skills designed to improve how I work with AI coding agents such as Codex, Cursor, Claude Code, and other development assistants.

The goal of this repository is to turn repeatable workflows into structured, reusable skills so that I do not need to rewrite the same long prompts again and again.

These skills are organized into five categories:

- **planning-design** — clarify requirements, shape plans, and define direction before implementation
- **development** — implement, debug, refactor, and improve code structure
- **frontend** — design, build, and refine frontend interfaces, web apps, and interactive UI artifacts
- **tooling-setup** — standardize engineering workflows and local project setup
- **writing-knowledge** — improve writing quality, terminology consistency, and knowledge organization

---

## Repository Structure

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
├─ frontend/
│  ├─ frontend-design/
│  └─ web-artifacts-builder/
├─ tooling-setup/
│  ├─ git-guardrails/
│  └─ setup-pre-commit/
├─ writing-knowledge/
│  ├─ edit-article/
│  ├─ ubiquitous-language/
│  └─ write-a-skill/
└─ README.md
```

---

## Skill Quick Reference

| Category | Skill | Purpose | When to Use |
| --- | --- | --- | --- |
| planning-design | `grill-me` | Stress-test an idea, requirement, or technical plan through focused questioning | When the requirement is still unclear or needs deeper thinking |
| planning-design | `request-refactor-plan` | Create a detailed refactor plan before touching code | Before large refactors or architecture cleanup |
| planning-design | `to-issues` | Break a PRD or plan into small, independent implementation issues | When turning a requirement document into actionable development tasks |
| planning-design | `to-prd` | Convert context, discussions, or rough ideas into a structured PRD | When preparing a feature or project for implementation |
| development | `improve-codebase-architecture` | Identify codebase architecture problems and propose structural improvements | When the project feels messy, duplicated, or hard to maintain |
| development | `tdd` | Use red-green-refactor workflow to implement or fix behavior through tests | When building reliable features or fixing bugs safely |
| development | `triage-issue` | Investigate a bug or issue and produce a clear root-cause and fix plan | When an issue needs analysis before coding |
| frontend | `frontend-design` | Create polished, practical, non-generic frontend UI designs and components | When building or improving pages, dashboards, landing pages, forms, and UI layouts |
| frontend | `web-artifacts-builder` | Build complex interactive web artifacts using modern frontend patterns | When creating React-style prototypes, interactive demos, dashboards, or multi-component UI experiences |
| tooling-setup | `git-guardrails` | Add safety rules and guardrails around Git usage | When avoiding dangerous Git operations or enforcing safer workflows |
| tooling-setup | `setup-pre-commit` | Configure pre-commit checks such as formatting, linting, type checks, and tests | When standardizing local development workflow |
| writing-knowledge | `edit-article` | Improve article structure, clarity, and expression | When editing long-form writing or technical articles |
| writing-knowledge | `ubiquitous-language` | Extract and maintain consistent domain terminology | When building shared vocabulary for a product, domain, or codebase |
| writing-knowledge | `write-a-skill` | Create or improve reusable AI agent skills | When adding new skills to this repository |

---

## Categories

### planning-design

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

---

### development

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

---

### frontend

Skills for frontend interface design, UI implementation, and interactive web artifact creation.

This category is focused on:

- frontend UI design
- React-style component planning
- dashboard and landing page design
- responsive layouts
- interactive web artifacts
- interface quality improvement
- turning rough requirements into usable screens

Current skills:

- `frontend-design`
- `web-artifacts-builder`

#### frontend-design

Use this skill when the goal is to create or improve a user-facing interface.

It is especially useful for:

- landing pages
- dashboards
- admin systems
- mobile-first pages
- forms and tables
- customer-facing product pages
- UI redesign tasks
- making interfaces feel more polished and less generic

Typical use cases:

- “Improve this frontend page based on the existing code.”
- “Redesign this dashboard to look more professional.”
- “Create a better layout for a customer detail page.”
- “Make this UI more suitable for US users.”
- “Turn this rough requirement into a clean frontend screen.”

#### web-artifacts-builder

Use this skill when the goal is to build a more complete interactive web experience.

It is especially useful for:

- interactive prototypes
- multi-component web apps
- frontend demos
- complex UI artifacts
- stateful interfaces
- dashboard prototypes
- design-to-code experiments

Typical use cases:

- “Build an interactive prototype for this feature.”
- “Create a frontend demo with multiple components.”
- “Turn this product idea into a working web artifact.”
- “Create a polished React-style interface from this requirement.”

---

### tooling-setup

Skills for project tooling and engineering guardrails.

This category is focused on:

- repository safety
- commit discipline
- local tooling setup
- workflow consistency
- pre-commit checks

Current skills:

- `git-guardrails`
- `setup-pre-commit`

---

### writing-knowledge

Skills for documentation, writing quality, and knowledge systems.

This category is focused on:

- article editing
- terminology consistency
- writing reusable skills
- knowledge organization
- documentation quality

Current skills:

- `edit-article`
- `ubiquitous-language`
- `write-a-skill`

---

## Recommended Workflow

This repository is designed to support a practical AI-assisted development workflow.

A typical flow looks like this:

```text
rough idea
  ↓
to-prd
  ↓
to-issues
  ↓
frontend-design / web-artifacts-builder
  ↓
tdd
  ↓
triage-issue / improve-codebase-architecture
  ↓
edit-article / ubiquitous-language
```

For frontend-heavy work, the recommended flow is:

```text
requirement or screenshot
  ↓
frontend-design
  ↓
web-artifacts-builder
  ↓
to-issues
  ↓
tdd
  ↓
triage-issue
```

For larger product or system work, the recommended flow is:

```text
idea or business need
  ↓
grill-me
  ↓
to-prd
  ↓
to-issues
  ↓
tdd
  ↓
improve-codebase-architecture
```

---

## Design Principles

This repository follows a few simple principles.

### Reusable

Each skill should solve a repeatable problem or workflow.

A good skill should be useful more than once, across more than one project.

### Focused

Each skill should have a clear purpose instead of trying to do everything.

A frontend design skill should not also become a backend architecture skill. A PRD skill should not also become a test runner.

### Actionable

A skill should tell the agent:

- what to do
- when to use it
- what to inspect
- what output is expected
- what constraints must be respected

### Maintainable

Skills should stay understandable and easy to improve over time.

Each skill should be easy to read, update, and reuse.

### Practical

The goal is not to collect prompts for decoration.

The goal is to create a real working system that helps with planning, coding, reviewing, documenting, and shipping projects.

---

## Why This Repository Exists

I use this repository as a personal skill library and workflow system.

Instead of relying on scattered prompts, I organize proven working patterns into reusable skills that can be improved, versioned, and reused across projects.

This repository is intended to become:

- a personal AI agent workflow library
- a reusable prompt-to-skill system
- a structured collection of development habits
- a long-term knowledge base for AI-assisted work
- a practical toolkit for using Codex, Cursor, Claude Code, and other coding agents more effectively

---

## Future Direction

This repository will continue to grow with more skills for:

- project planning
- frontend development
- backend development
- debugging and review
- refactoring and architecture
- documentation and communication
- AI-assisted code review
- team-oriented engineering practices
- product requirement management

---

# 仓库说明

这个仓库用于整理我在使用 Codex、Cursor、Claude Code 以及其他 AI 开发助手时反复使用的 skills。

核心目标是把高频、可复用、可标准化的工作流整理成结构化 skill，避免每次都重新编写很长的提示词。

当前仓库按五个方向进行分类：

- **planning-design**：在真正动手前先把需求、方案和方向理顺
- **development**：围绕编码实现、排障、重构和架构优化展开
- **frontend**：围绕前端页面设计、交互原型、UI 组件和 Web 应用构建展开
- **tooling-setup**：沉淀工程化配置、提交流程和本地开发规范
- **writing-knowledge**：整理文档、术语、文章和知识沉淀相关流程

---

## 中文分类说明

### planning-design

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

---

### development

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

---

### frontend

这一类 skill 用于“前端页面设计、UI 优化、交互原型和 Web 应用构建”。

主要适用于：

- 前端 UI 设计
- 页面改版
- Dashboard 设计
- 表单、表格、详情页设计
- 移动端优先页面
- React 风格组件设计
- 交互式 Web 原型
- 复杂前端 artifact 构建

当前包含：

- `frontend-design`
- `web-artifacts-builder`

#### frontend-design

适合在需要提升页面视觉质量和交互体验时使用。

例如：

- 优化一个后台管理页面
- 重新设计一个 Dashboard
- 改进一个客户详情页
- 让页面更符合美国用户习惯
- 把粗糙的功能需求转换成更清晰的前端页面方案
- 避免 AI 生成页面常见的模板化、廉价感和过度装饰

#### web-artifacts-builder

适合在需要构建更复杂的交互式前端原型时使用。

例如：

- 生成一个可交互的 Web 原型
- 构建多组件页面
- 制作 Dashboard demo
- 搭建产品功能演示界面
- 将需求转换成 React 风格的前端 artifact
- 构建有状态、有交互、有组件结构的前端页面

---

### tooling-setup

这一类 skill 用于“工程化配置和开发流程守护”。

主要适用于：

- Git 规范
- 提交流程约束
- 本地工具初始化
- 开发流程统一
- 项目安全护栏
- pre-commit 检查

当前包含：

- `git-guardrails`
- `setup-pre-commit`

---

### writing-knowledge

这一类 skill 用于“文档、写作与知识体系整理”。

主要适用于：

- 文档润色
- 术语统一
- skill 编写
- 知识沉淀
- 文章编辑

当前包含：

- `edit-article`
- `ubiquitous-language`
- `write-a-skill`

---

## 推荐使用流程

如果是普通功能开发，可以这样使用：

```text
原始想法
  ↓
to-prd
  ↓
to-issues
  ↓
tdd
  ↓
triage-issue
```

如果是前端页面开发或 UI 改版，可以这样使用：

```text
需求 / 截图 / 现有页面
  ↓
frontend-design
  ↓
web-artifacts-builder
  ↓
to-issues
  ↓
tdd
  ↓
triage-issue
```

如果是大型需求或系统设计，可以这样使用：

```text
业务想法
  ↓
grill-me
  ↓
to-prd
  ↓
to-issues
  ↓
tdd
  ↓
improve-codebase-architecture
```

---

## 设计原则

这个仓库中的 skill 尽量遵循以下原则。

### 可复用

优先沉淀高频且可重复使用的流程。

### 单一职责

每个 skill 聚焦解决一类明确问题，不追求大而全。

### 可执行

不仅要说明“做什么”，还要说明：

- 什么时候使用
- 需要检查什么
- 应该输出什么
- 需要遵守什么限制
- 如何判断任务完成

### 易维护

尽量让 skill 保持清晰、可读、可持续优化。

### 实用优先

这个仓库不是单纯保存提示词，而是沉淀真正能辅助项目推进的 AI 工作流。

---

## 为什么要做这个仓库

我把这个仓库当作个人的 skill 库和 AI 工作流沉淀仓库。

相比零散地保存提示词，我更希望把已经验证有效的方法整理成长期可维护、可版本化、可复用的 skill。

这个仓库会逐步成为：

- 我的个人 AI 工作流仓库
- 可复用的技能模板库
- 开发方法论沉淀库
- 前端、后端、文档、测试、架构等工作的辅助系统
- 长期演进的知识资产仓库

---

## 后续规划

后续可能会继续补充更多适用于以下场景的 skill：

- 项目需求规划
- 前端页面设计
- 前端组件开发
- 后端接口开发
- 编码与调试
- 代码审查与重构
- 架构治理
- 文档整理与沟通协作
- 更适合团队使用的工程实践

---

This repository will continue to evolve as my AI-assisted development workflow becomes more structured and practical.
