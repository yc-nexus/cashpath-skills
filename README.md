# CashPath Skills

为 Claude Code 打造的商业思考技能包。把实事求是的分析方法论，变成可复用的 AI 技能文件。

## 已包含技能

| 技能 | 用途 | 触发词 |
|------|------|--------|
| [矛盾分析法](.claude/skills/contradiction-analysis/SKILL.md) | 复杂问题诊断、方向选择、优先级排序 | "分析矛盾"、"卡住了"、"选哪个" |
| [简历定制师](.claude/skills/resume-tailor/SKILL.md) | JD 匹配分析、简历改写、投递策略 | "改简历"、"匹配JD"、"投这个岗位" |

## 安装

### 方法 1：npx skills（推荐）

```bash
npx skills add yc-nexus/cashpath-skills --skill contradiction-analysis -g -y
npx skills add yc-nexus/cashpath-skills --skill resume-tailor -g -y
```

### 方法 2：手动复制

```bash
cp -r .claude/skills/* ~/your-project/.claude/skills/
```

### 方法 3：Git Submodule

```bash
git submodule add https://github.com/yc-nexus/cashpath-skills.git .claude/skills/cashpath
```

## 使用

在 Claude Code 对话中自然触发：

```
我同时在追三个方向，不知道先做哪个，帮我分析一下主要矛盾
```

```
这是腾讯产品经理的 JD，这是我的简历，帮我匹配优化一下
```

## 更多技能

计划中的技能：调查研究法、实践认识论、批评与自我批评、集中兵力、星火燎原。

## 许可

MIT
