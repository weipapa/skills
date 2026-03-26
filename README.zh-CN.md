# Skills

中文 | **[English](./README.md)**

Claude Code 技能集合，用于扩展 AI 编程代理的能力。

## 技能列表

| 技能 | 说明 |
|------|------|
| [longbridge](./longbridge/) | 美股 & 港股行情查询、交易执行与自选股管理 |
| [skill-vetter](./skill-vetter/) | 技能安装前的安全审计工具 |
| [find-skills](./find-skills/) | 发现并安装生态系统中的技能 |
| [opencli-rs](./opencli-rs/) | 通用网页命令行工具 — 将 55+ 网站变成 CLI |
| [summarize](./summarize/) | 总结网页、本地文件和 YouTube 视频字幕 |

## 安装

每个技能是一个包含 `SKILL.md` 文件的独立目录。将技能复制到 Claude Code 技能目录即可使用：

```bash
cp -r <技能名称> ~/.claude/skills/<技能名称>
```

也可以通过技能 CLI 安装（如可用）：

```bash
npx skills install <技能名称>
```

## 许可证

MIT
