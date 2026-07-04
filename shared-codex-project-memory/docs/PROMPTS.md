# Shared Prompts

Use these prompts to keep the three Codex accounts aligned.

## Start a New Thread

```text
先阅读 AGENTS.md、docs/AI_CONTEXT.md、docs/SOURCE_INDEX.md、docs/DECISIONS.md 和 docs/TASK_LOG.md。
这些文件是三个 Codex 账号共享的项目记忆。阅读后请总结你理解到的项目背景、当前目标、关键限制和下一步建议，然后继续执行我的任务。
任务结束时，请更新 docs/TASK_LOG.md；如果产生长期决策，请更新 docs/DECISIONS.md；如果新增资料，请更新 docs/SOURCE_INDEX.md。
```

## Add New Materials

```text
我会给你一批项目资料。请不要只在当前聊天里记住它们。
请把资料整理进共享项目记忆：
1. 原始资料或链接登记到 docs/SOURCE_INDEX.md。
2. 关键摘要写到 docs/research/summaries/。
3. 稳定、长期有效的结论合并进 docs/AI_CONTEXT.md。
4. 如果资料改变了项目方向，请更新 docs/DECISIONS.md。
```

## Handoff to Another Account

```text
请阅读 docs/TASK_LOG.md 的最新记录，并基于 AGENTS.md 和 docs/AI_CONTEXT.md 接手当前任务。
请先说明你认为当前状态是什么、有哪些未完成事项，然后继续工作。
```

## End a Task

```text
请收尾本次任务：
1. 更新 docs/TASK_LOG.md，记录你完成了什么、改了哪些文件、下一步是什么。
2. 如有长期决策，更新 docs/DECISIONS.md。
3. 如有新增资料，更新 docs/SOURCE_INDEX.md。
4. 如有稳定背景变化，更新 docs/AI_CONTEXT.md。
```
