# ⚽ Claude Football Agent — FIFA World Cup 2026 Blogging Agent

![License](https://img.shields.io/badge/license-MIT-green)

An AI agent definition (system prompt) for a **FIFA World Cup 2026 content creator and social media strategist**. Load it into any agent runtime that supports custom agent configs (Claude Code, OpenCode, …) to generate football content for Twitter/X, LinkedIn, and Threads.

## What the agent does

As defined in [`.opencode/agent/worldcup2026-blogger.md`](.opencode/agent/worldcup2026-blogger.md):

- **Match analysis & previews** — tactical breakdowns, player matchups, predicted XIs, set-piece patterns
- **News aggregation & daily digests** — official announcements, injury reports, squad news, venue/VAR updates
- **Historical context & stats** — head-to-head records, milestone tracking, tournament records, "on this day" moments
- **Fan engagement content** — predictions with confidence levels, polls, reaction templates
- **Content style guidelines** — per-platform formatting for Twitter/X (280 chars, hooks, hashtags), LinkedIn, and Threads

## Usage

Point your agent runtime at the agent file:

```text
.opencode/agent/worldcup2026-blogger.md
```

Example with OpenCode: place this repo's `.opencode/` directory in your project and invoke the `worldcup2026-blogger` agent. With Claude Code or similar tools, paste the file's contents as a custom system prompt / subagent definition.

The agent is configured with web search and web fetch permissions so it can pull in current news, scores, and stats — always verify time-sensitive facts (lineups, injuries, scores) against an official source before publishing.

## Disclaimer

Generated content should be reviewed by a human before publishing. Match facts, statistics, and news change quickly — the agent's outputs are only as current as the sources it can reach.

## License

MIT License — see [LICENSE](LICENSE) for details.
