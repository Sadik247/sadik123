# Dynatrace for AI

Skills from https://github.com/Dynatrace/dynatrace-for-ai (commit 5dbfd57, Apache-2.0) live in `.claude/skills/`.
The Dynatrace MCP server is configured in `.mcp.json` and reads `DT_ENVIRONMENT` and `DT_PLATFORM_TOKEN` from the environment.

Setup: `cp .env.example .env`, fill in tokens, then `set -a; source .env; set +a` before starting Claude Code.
Use the included `dt-*` skills for observability-related questions.
