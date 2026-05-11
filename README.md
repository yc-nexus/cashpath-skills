# CashPath Skills

为 Claude Code 打造的实用技能包。把经验和思考，变成可复用的 AI 技能文件。

## 已包含技能

| 技能 | 用途 | 触发词 |
|------|------|--------|
| [矛盾分析法](.claude/skills/contradiction-analysis/SKILL.md) | 复杂问题诊断、方向选择、优先级排序 | "分析矛盾"、"卡住了"、"选哪个" |
| [技术文档精读助手](.claude/skills/tech-doc-reader/SKILL.md) | 英文技术文档/论文/API 文档解析 | "读文档"、"分析论文"、"解读" |
| [Landing Page 文案助手](.claude/skills/landing-copywriter/SKILL.md) | 竞品文案分析 + A/B 版英文文案生成 | "写文案"、"landing page"、"产品介绍英文" |
| [出海 SaaS 客服英语](.claude/skills/saas-support-english/SKILL.md) | 英文客服回复、退款/投诉/功能请求处理 | "客服邮件"、"英文回复"、"退款邮件" |

## 安装

### 方法 1：npx skills（推荐）

```bash
npx skills add yc-nexus/cashpath-skills --skill contradiction-analysis -g -y
npx skills add yc-nexus/cashpath-skills --skill tech-doc-reader -g -y
npx skills add yc-nexus/cashpath-skills --skill landing-copywriter -g -y
npx skills add yc-nexus/cashpath-skills --skill saas-support-english -g -y
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
帮我解读这篇 React 18 的官方升级指南，提取关键变化
```

```
分析 veed.io 的 Landing Page 文案，给我的产品写一版英文介绍
```

```
用户发邮件说要退款，原因是觉得太贵了，帮我写一封英文回复挽留一下
```

## 更多技能

计划中：英语学习、SEO 分析、调研访谈。

## 许可

MIT
