# Project AI Collaboration Guide

This file is the shared instruction layer for every Codex account working on this project.

## Start Here

At the beginning of every new Codex thread, read these files first:

1. `docs/AI_CONTEXT.md`
2. `docs/SOURCE_INDEX.md`
3. `docs/DECISIONS.md`
4. `docs/TASK_LOG.md`

If the task involves requirements, research, product decisions, or external materials, check the relevant files under `docs/requirements/` and `docs/research/` before making changes.

## Working Rules

- Treat the files in `docs/` as the project memory shared across all Codex accounts.
- Do not rely on private chat history from one account as the source of truth.
- When a task changes the understanding of the project, update the relevant shared context file.
- When a decision is made, add it to `docs/DECISIONS.md`.
- When a task is completed, add a short entry to `docs/TASK_LOG.md`.
- When new materials are added, register them in `docs/SOURCE_INDEX.md`.
- Prefer small, traceable changes over broad rewrites.
- Preserve user edits unless explicitly asked to replace them.

## End-of-Task Checklist

Before finishing a task, decide whether to update:

- `docs/TASK_LOG.md` for work performed and next steps.
- `docs/DECISIONS.md` for durable decisions.
- `docs/AI_CONTEXT.md` for stable project background.
- `docs/SOURCE_INDEX.md` for newly added or referenced materials.

## Recommended Prompt

Use this when starting a new Codex thread:

```text
先阅读 AGENTS.md、docs/AI_CONTEXT.md、docs/SOURCE_INDEX.md、docs/DECISIONS.md 和 docs/TASK_LOG.md。
这些文件是三个 Codex 账号共享的项目记忆。阅读后请基于当前共享上下文继续工作，并在任务结束时更新相关上下文文件。
```
