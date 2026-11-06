# favicongenerator.io Agent Skills

Agent Skills for [favicongenerator.io](https://favicongenerator.io), a free favicon generator.

| Skill | What it does |
| --- | --- |
| [create-favicon](create-favicon/SKILL.md) | Add a complete favicon set and HTML head tags to a website via the free favicongenerator.io MCP server. |

## Install

```bash
npx skills add https://favicongenerator.io --skill create-favicon
```

The `skills` CLI needs Node.js 22.20 or later. You can also copy the `create-favicon/` folder into your agent's skills directory (for Claude Code, `~/.claude/skills/` or `.claude/skills/` in a project).

## What the skill uses

The skill calls the free, keyless, read-only favicongenerator.io MCP server at `https://favicongenerator.io/mcp` (Official MCP Registry name `io.github.7and1/favicon-generator`) or the matching REST API. No API key or account is needed.

## Source of truth

`create-favicon/SKILL.md` is a byte-identical copy of
<https://favicongenerator.io/.well-known/agent-skills/create-favicon/SKILL.md>
(discovery index: <https://favicongenerator.io/.well-known/agent-skills/index.json>).
`SHA256SUMS` records its hash. Check it with:

```bash
shasum -a 256 -c SHA256SUMS
```

## License

[MIT](LICENSE)
