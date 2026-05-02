# mmcp-generator

**Paste a GitHub repo URL → instantly generate Alice · Bob · MMCLI Space instructions.**

This is your automated MMCP inbox/outbox system setup tool. Every time you create a new repo, open this tool, paste the link, and get ready-to-paste Space instructions for all three agents.

## What it does

- Pre-loaded with all your existing repos from `nothinginfinity`
- Paste any `github.com/nothinginfinity/repo-name` URL → generates instructions for Alice, Bob, and MMCLI
- One-click copy for each agent's Space instructions
- All mailboxes route through `studio-brainstorm` as the central bus
- Light + dark mode, works on mobile

## How to use

1. Open `mmcp-generator.html` locally or via GitHub Pages
2. Paste a GitHub repo URL into the sidebar
3. Click the agent tab (Alice / Bob / MMCLI)
4. Hit **Copy & ready to paste into Perplexity Space**
5. Open Perplexity → New Space → paste as the Space instructions

## Adding a new repo

Just paste the GitHub link. The tool parses the repo name automatically and generates all three sets of instructions instantly. No config needed.

## The network

All mailboxes live in [`studio-brainstorm`](https://github.com/nothinginfinity/studio-brainstorm/tree/main/spaces) under:
```
spaces/{repo-name}/alice/inbox.md
spaces/{repo-name}/alice/outbox.md
spaces/{repo-name}/bob/inbox.md
spaces/{repo-name}/bob/outbox.md
spaces/{repo-name}/mmcli/inbox.md
spaces/{repo-name}/mmcli/outbox.md
```

## Agents

| Agent | Role |
|-------|------|
| **Alice** | Product thinker, UX strategist, feature prioritization |
| **Bob** | Engineer, architecture, implementation |
| **MMCLI** | Coordinator, inter-agent routing, pipeline state |
