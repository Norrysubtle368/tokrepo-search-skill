# TokRepo Search Skill

Cross-platform TokRepo search skill for AI coding agents and MCP-aware tools.

This repo makes TokRepo easy to discover from GitHub for:

- Claude Code
- OpenAI Codex
- Cursor
- Gemini CLI
- Copilot / AGENTS-compatible tools

TokRepo is an open registry for AI assets:

- skills
- prompts
- MCP configs
- scripts
- workflows

## What This Repo Contains

- `AGENTS.md` for AGENTS-compatible tools
- `SKILL.md` at the repo root for direct skill discovery
- `claude-code/SKILL.md`
- `codex/tokrepo-search/SKILL.md`
- `codex/tokrepo-search/agents/openai.yaml`
- `cursor/tokrepo.mdc`
- `gemini/tokrepo/GEMINI.md`
- `gemini/tokrepo/gemini-extension.json`

## Quick Use

Search:

```bash
npx tokrepo search "mcp database"
npx tokrepo search "cursor rules typescript"
```

Install:

```bash
npx tokrepo install <uuid-or-name>
```

Add the TokRepo MCP server:

```bash
claude mcp add tokrepo -- npx tokrepo-mcp-server
codex --mcp-server tokrepo -- npx tokrepo-mcp-server
gemini settings mcp add tokrepo -- npx tokrepo-mcp-server
```

## Why This Helps Agents

Most AI assets are scattered across repos, awesome lists, blogs, and gists.
TokRepo gives agents one searchable registry with installable outputs and machine-readable conventions.

## Links

- Website: https://tokrepo.com
- CLI: https://www.npmjs.com/package/tokrepo
- MCP server: https://www.npmjs.com/package/tokrepo-mcp-server
- TokRepo quickstart gist: https://gist.github.com/henu-wang/6c65ad09ee3fa5f65d5dee4cb9d40c6e
