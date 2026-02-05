# ai-reverse-toolkit

AI-assisted skills, rules and prompts for JavaScript/Web reverse engineering.

Works with Claude, GPT, Gemini and other LLMs.

## Structure

```
ai-reverse-toolkit/
├── skills/          # Task-oriented skills (find entry, algorithm restore, etc.)
├── rules/           # Background knowledge (obfuscation identification, tool reference, etc.)
└── prompts/         # Common prompt templates
```

## Usage

### For Claude Code

Copy to your project:

```bash
cp -r skills/* .claude/skills/
cp -r rules/* .claude/rules/
```

### For Other LLMs

Use the markdown files directly as system prompts or context.

## Skills

| Skill | Description |
|-------|-------------|
| `find-crypto-entry` | Locate encryption parameter generation entry point |

## Rules

| Rule | Description |
|------|-------------|
| `js-reverse.md` | JS reverse engineering guide and tool reference |

## Dependencies

- [js-reverse MCP](https://github.com/anthropics/anthropic-cookbook) - Browser debugging MCP tool (for Claude Code)

## License

MIT
