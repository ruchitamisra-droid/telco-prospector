# 🔍 Telco Prospector

> AI-powered tool to find content partnerships, D2C mobile, and marketing contacts at any telco — built for biz dev teams.

🔗 **Live tool → [ruchitamisra-droid.github.io/telco-prospector](https://ruchitamisra-droid.github.io/telco-prospector)**

## What it does

Type in any telco company name and a region, and the agent surfaces relevant contacts across four teams:

- **Content Partnerships** — people who own app and media bundling deals
- **D2C Mobile** — digital subscription and direct-to-consumer leads
- **Digital Marketing** — growth and campaign decision makers
- **VAS** — value-added services and digital product managers

Each result links directly to a Google search for that person's LinkedIn profile.

## Why I built this

Doing biz dev outreach at a telco-facing company means spending hours researching who to contact at operators like Vodafone, Orange, or Deutsche Telekom. This tool cuts that research time to seconds using Claude AI.

## Built with

- **Claude API** (Anthropic) — `claude-sonnet-4` for contact generation
- **Vanilla HTML/JS** — no framework, single file, runs entirely in the browser
- **GitHub Pages** — zero infrastructure, instant deployment

## How to use

1. Open the [live tool](https://ruchitamisra-droid.github.io/telco-prospector)
2. Enter your Anthropic API key when prompted (stored in session only, never logged or shared)
3. Type a telco name (e.g. Vodafone) and region (e.g. UK)
4. Hit Search — contacts appear in seconds

## Security

Your API key is never hardcoded. The tool prompts on first load and stores the key in `sessionStorage` (clears on tab close) or `localStorage` (if you opt in). The repo contains no secrets.

---

*Part of a series of AI-powered biz dev tools. See also: [napster-prospect-agent](https://github.com/ruchitamisra-droid/napster-prospect-agent)*
