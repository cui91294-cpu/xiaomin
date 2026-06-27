# Academic Research Skills — Claude Code Commands

期刊论文写作与审稿全流程 slash commands，基于 [academic-research-skills](https://github.com/Imbad0202/academic-research-skills) 核心设计思路实现。

## 命令列表

| 命令 | 功能 | 适用场景 |
|---|---|---|
| `/ars-plan` | Socratic 对话式规划论文结构 | 开始写作前，梳理研究问题和章节框架 |
| `/ars-lit-review` | 文献综述生成 | 撰写文献综述章节，含标注书目 + 主题合成 |
| `/ars-write` | 论文写作全流程 | 逐节撰写期刊论文正文 |
| `/ars-reviewer` | 同行审稿模拟（5位审稿人） | 投稿前预审，发现潜在问题 |
| `/ars-revision` | 根据审稿意见修改稿件 + 回复信 | 收到 Major/Minor Revision 后使用 |
| `/ars-rebuttal-audit` | 回复信质量审计 | 检查已写好的回复信有无遗漏或弱点 |

## 推荐使用顺序

```
/ars-plan → /ars-lit-review → /ars-write → /ars-reviewer → /ars-revision → /ars-rebuttal-audit
```

## 快速使用示例

**规划论文：**
```
/ars-plan
我想写一篇关于大语言模型在医疗诊断中的应用的论文，目标期刊是 Nature Medicine。
```

**模拟审稿（默认 full 模式，5位审稿人）：**
```
/ars-reviewer
[粘贴论文全文或草稿]
```

**只做快速预审（EIC 视角）：**
```
/ars-reviewer quick
[粘贴论文摘要+引言]
```

**修改稿件并生成逐条回复：**
```
/ars-revision
[粘贴原稿] + [粘贴审稿意见]
```
