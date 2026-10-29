# web-search-toolkit

Nebflow / Stand plugin package — standalone repository for version history.

- **Version:** 1.0.0 (tag `v1.0.0`)
- **Import commit:** `da68e9b` (5 files)
- **Import date:** 2026-10-29
- **Content source:** engine seed, `src/main/resources/seed/plugins/web-search-toolkit`
  in the Stand monorepo (seed last touched by commit `5fe4309c6 (2026-10-20 03:56:00 +0800)`)

## Editing

This repository is the place to change the package: commit here, tag releases as
`v<plugin.json version>`, and mirror the result back into the engine seed
(`src/main/resources/seed/plugins/web-search-toolkit`) so freshly installed instances receive it.

## Layout

```
plugin.json    manifest (name / version / description)
Plugin.md      package guide, injected as the agent prompt on plugin assignment
skills/        one directory per skill, each with SKILL.md
mcp.json       (optional) MCP server declarations
scripts/       (optional) helper scripts
```
