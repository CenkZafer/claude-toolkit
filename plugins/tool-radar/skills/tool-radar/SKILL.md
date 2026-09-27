---
name: tool-radar
description: Cenk's short list of tools Claude already researched and recommended. Use whenever a new project is started, a repo is opened for the first time, a stack is chosen, tooling is added, security/payment code is involved, or the user asks which plugin, MCP, skill or tool to use.
---

# Tool Radar

Suggest only tools from this list that fit the project. Max 5, free first, one short line each in simple language. Never install without the user's OK. Suggest once per session.
Only recommended tools are listed here; do not suggest tools that are not on this list.

## Plugins
- claude-code-setup (free) — every new project, install first: `/plugin install claude-code-setup@claude-plugins-official`
- security-guidance (free) — any code with user input, shell, HTML or auth
- claude-security (paid plan) — payment / POS / auth code: `/claude-security`
- Superpowers — bigger features: plan → test → review
- Caveman — long sessions, saves tokens

## Skills
- TDD — writing tests first
- Matt Pocock Skills — TypeScript projects
- UI/UX Pro Max, Web Quality — websites and store fronts
- Remotion — videos with React
- Humanizer — product / marketing texts

## Other tools
- Ollaya (ollaya.dev) — free local decision/classification models, Jev-compatible; laya:multilingual for Turkish
- Avibe — scheduled or monitored agent jobs with Telegram alerts; test in isolation first

## Updating
When the user says "add X to the radar", add one line here, bump version in plugin.json, commit and push.
