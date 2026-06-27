# Academic Writing Assistant

## Auto-Skill Triggers

When the user's message matches the patterns below, **automatically apply the corresponding skill without asking** — do not wait for an explicit slash command.

| If the user says / provides... | Automatically apply |
|---|---|
| 提交论文草稿 / paper draft / "帮我审稿" / "review my paper" | `/ars-reviewer` (full mode) |
| "帮我规划" / "plan my paper" / "我想写一篇关于..." / 描述研究方向但没有草稿 | `/ars-plan` |
| "文献综述" / "lit review" / "帮我查文献" / "survey on..." | `/ars-lit-review` |
| "帮我写" / "write this paper" / 提供了章节计划要求开始写作 | `/ars-write` |
| 提交论文 + 审稿意见 / "根据意见修改" / "revise" + reviewer comments | `/ars-revision` |
| 提交回复信草稿 + 审稿意见 / "检查我的回复" / "audit my rebuttal" | `/ars-rebuttal-audit` |
| "润色" / "polish" / "语言修改" / "improve my English" / 提交章节要求语言改进 | `/ars-polish` (full mode) |

## Default Behavior
- 语言：根据用户输入语言自动切换中英文
- 引用格式：默认 APA 7th，除非用户指定其他格式
- 审稿模式：默认 full（5位审稿人），用户说"快速审"时切换到 quick 模式
