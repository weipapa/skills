# Skills

**[中文](./README.zh-CN.md)** | English

A collection of Claude Code skills for extending AI coding agent capabilities.

## Skills

| Skill | Description |
|-------|-------------|
| [longbridge](./longbridge/) | US & HK stock market data, trading, and watchlist management via CLI |
| [skill-vetter](./skill-vetter/) | Security-first vetting for skills before installation |
| [find-skills](./find-skills/) | Discover and install skills from the ecosystem |
| [opencli-rs](./opencli-rs/) | Universal web interface CLI — 55+ sites as command-line tools |
| [summarize](./summarize/) | Summarize URLs, local files, and YouTube transcripts |

## Installation

Each skill is a self-contained directory with a `SKILL.md` file. To use a skill with Claude Code, copy it into your skills directory:

```bash
# Copy a skill to your Claude Code skills directory
cp -r <skill-name> ~/.claude/skills/<skill-name>
```

Or install via the skills CLI (if available):

```bash
npx skills install <skill-name>
```

## License

MIT
