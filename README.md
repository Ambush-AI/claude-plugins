# Ambush AI plugins for Claude Code

Official Ambush AI plugins for Claude Code.

This repository is the Claude plugin marketplace. For standalone agent-skill
installation through skills.sh, use
[`Ambush-AI/ambush-stream-skills`](https://github.com/Ambush-AI/ambush-stream-skills)
instead. The stream-management skill is mirrored here only so the Claude plugin
can bundle it with the Ambush OAuth MCP server.

## Available plugins

- [`ambush-streams`](plugins/ambush-streams): create, review, and manage
  personalized Ambush news streams through the production OAuth MCP server.

## Install

Add the Ambush AI marketplace and install Ambush Streams:

```sh
claude plugin marketplace add Ambush-AI/claude-plugins
claude plugin install ambush-streams@ambush-ai
```

Start a new Claude Code session or run `/reload-plugins`. Open `/mcp` to connect
your Ambush account with OAuth.

## Validate locally

```sh
claude plugin validate --strict .
claude plugin validate --strict ./plugins/ambush-streams
```
