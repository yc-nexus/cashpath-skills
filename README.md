# CashPath Skills

为 Claude Code 打造的商业思考技能包。把实事求是的分析方法论，变成可复用的 AI 技能文件。

## 已包含技能

| 技能 | 用途 | 触发词 |
|------|------|--------|
| [矛盾分析法](.claude/skills/contradiction-analysis/SKILL.md) | 复杂问题诊断、方向选择、优先级排序 | "分析矛盾"、"卡住了"、"选哪个" |

## 安装

将 `.claude/skills/` 目录复制到你项目的 `.claude/` 下即可。

```bash
# 方法1：直接复制
cp -r .claude/skills/contradiction-analysis ~/your-project/.claude/skills/

# 方法2：作为 git submodule
git submodule add https://github.com/yc-nexus/cashpath-skills.git .claude/skills/cashpath
```

## 使用

在 Claude Code 对话中自然触发：

```
我同时在追三个方向，不知道先做哪个，帮我分析一下主要矛盾
```

## 更多技能

计划中的技能：调查研究法、实践认识论、批评与自我批评、集中兵力、星火燎原。

## 许可

MIT
