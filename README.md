# dev-toolkit

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="MIT license"></a>
  <img src="https://img.shields.io/badge/type-curated%20collection-blue.svg" alt="curated collection">
  <img src="https://img.shields.io/badge/tools-10-orange.svg" alt="10 tools">
</p>

## What this is

The coding workflow, review, and shipping skills behind everything I build. No code copied here, only links to the originals plus notes from daily use. This is the toolkit that turns an idea into a live URL.

## What's inside

| Tool | What it does | Link | License | My note |
|------|--------------|------|---------|---------|
| superpowers | Full coding workflow: brainstorm, spec, plan, build | bundled with my agent environment | check upstream | Always on for my builds. Big features get the full ceremony. |
| ponytail | Full-intensity coding mode | bundled with my agent environment | check upstream | When it is time to just execute. |
| prototype | Rapid prototyping | bundled with my agent environment | check upstream | For throwing a working version together fast. |
| open-code-review | Alibaba's code reviewer | [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | check upstream | Runs on every build I do. Catches what I miss. |
| claude-security / security-audit | Security scanning and audits | bundled with my agent environment | check upstream | Before anything touches production. |
| github | GitHub workflows | bundled with my agent environment | check upstream | Repo ops, PRs, the usual. |
| vercel | Vercel workflows | bundled with my agent environment | check upstream | Deploy and hosting flow. |
| ship-it | Ship pipeline: repo, README, Vercel, LinkedIn | bundled with my agent environment | check upstream | My own end-to-end "ship it" routine. |
| render | Render deployment | bundled with my agent environment | check upstream | For services that don't fit Vercel. |
| mobile-native / write-swift | Native mobile and Swift development | bundled with my agent environment | check upstream | When the web is not enough. |

## Data

No dedicated database skill in the list, so here is how I handle data: database work goes through the coding skills above. Supabase, Postgres, and Neon have all been set up that way. For quick local analysis I keep DuckDB around as a tool (vendor install, not a skill): `~/workspace/vendor/duckdb`.

## How I use these

superpowers plans it, ponytail builds it, open-code-review checks it, claude-security scans it, ship-it puts it live on GitHub and Vercel. That loop covers most of my work.

## How to use this list

Pick the tool that matches your problem, follow its link, install it per its own README. Star the ones you keep coming back to.

## Attribution

Every tool here belongs to its original author. Licenses in the table are the upstream licenses as I found them. "Check upstream" means I could not verify the license, so check the source before reusing code. The curation text in this repo (the notes, the structure) is mine, MIT licensed, see LICENSE.
