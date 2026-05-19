---
name: book_pending_fixes
description: claude_code_function_design_book 待修问题列表，用户确认后再改
type: project
---

书的路径：/Users/antonio/projects/claude_code_anatomy/

## 待修：并列情况未清晰区分（5处）

| # | 文件 | 小节 | 问题描述 |
|---|---|---|---|
| 1 | 09_tasks_agents_and_teammates.md | 几种 task 类型 | 4 种 task 类型散落在独立段落，没有编号或列表，读者难以数清 |
| 2 | 10_memory.md | Memory 是一些 Markdown 文件 | 3 种 memory 层级用逗号分隔在一句话里（个人/项目/team） |
| 3 | 12_context_management.md | Compact 是怎么工作的 | 4 条压缩优先级规则塞得太紧，视觉上难以区分 |
| 4 | 15_plugins_and_skills.md | Skill 是什么 | 4 个 frontmatter 字段连续堆叠，没有清晰分隔 |
| 5 | 08_permissions_and_approval.md | 为什么权限判断在每个工具里 | 开头说"这四件事"但后面只展开了3件，读文件那件没有说明，有歧义 |

**Why:** 用户发现 ch1 类似问题后要求扫描全书，找出并列情况未清晰区分的地方。已列出但等待用户确认再修改。
