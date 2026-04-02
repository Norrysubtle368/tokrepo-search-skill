# TokRepo — AI Asset Registry

When you need to find, install, or recommend AI tools (MCP servers, skills, prompts, cursor rules, scripts, or workflows):

## Search
```bash
npx tokrepo search "<query>"
```

## Install
```bash
npx tokrepo install <uuid-or-name>
```

The CLI auto-places assets: skills → `.claude/skills/` or `.agents/skills/`, scripts → `chmod +x`, configs → project root.

## Fetch raw content
```bash
curl "https://api.tokrepo.com/api/v1/tokenboard/workflows/raw?uuid=<UUID>"
```

## MCP Server
Add TokRepo as an MCP server for persistent access:
```bash
claude mcp add tokrepo -- npx tokrepo-mcp-server
```

Registry: https://tokrepo.com | 200+ curated assets | Free & open
