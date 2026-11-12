# OBTO plugin for Claude and Codex

Build, deploy and operate apps on the [OBTO platform](https://app.obto.co) from Claude or Codex. One MCP connection (`https://app.obto.co/ms/mcp`, Google sign-in), a `/obto:start` command, and skills for building, deploying, uploads, the app database, reviewer feedback, memory and troubleshooting.

## Install

**Claude app or claude.ai:** Customize > Plugins > Add > Add marketplace > `obto-inc/obto-plugin`, then install **OBTO**. Turn on "Sync automatically" to get new versions.

**Claude Code:**

```
claude plugin marketplace add obto-inc/obto-plugin
claude plugin install obto@obto
```

Update later with `claude plugin marketplace update obto` and `claude plugin update obto@obto`.

**Codex:**

```
codex plugin marketplace add obto-inc/obto-plugin
codex plugin add obto@obto
codex mcp login obto
```

Update later with `codex plugin marketplace upgrade`.

Details: [plugins/obto/README.md](plugins/obto/README.md) (Claude), [plugins/obto-codex/README.md](plugins/obto-codex/README.md) (Codex).
