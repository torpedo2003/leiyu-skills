# leiyu-skills

A collection of agent skills. Each skill lives in its own folder under `skills/` with a `SKILL.md`.

个人维护的 AI agent skill 合集。每个 skill 是 `skills/` 下的一个目录，核心文件是 `SKILL.md`。

## Skills

| Skill | 说明 |
|---|---|
| [academic-writing](skills/academic-writing/SKILL.md) | 撰写和修改英文学术论文及其图表的规范：论证、用词、标点句式、实验分析、交叉引用、图表标题、图表绘制、修改原则 |

## 使用方法

**Claude Code**：把需要的 skill 目录复制到 `~/.claude/skills/`（全局）或项目的 `.claude/skills/` 下。

```bash
git clone https://github.com/torpedo2003/leiyu-skills.git
cp -r leiyu-skills/skills/academic-writing ~/.claude/skills/
```

**其他 agent**（Codex、Cursor、Gemini CLI 等）：`SKILL.md` 是普通 Markdown。把它放进项目，并在 `AGENTS.md`、`.cursor/rules` 或对应的指令文件中引用，或直接把内容粘贴进去。

## 添加新 skill

1. 在 `skills/` 下新建目录，目录名即 skill 名（小写、用连字符）。
2. 在目录中写 `SKILL.md`，开头的 frontmatter 包含 `name` 和 `description`。
3. 在上方表格中加一行。
