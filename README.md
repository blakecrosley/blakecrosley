# Blake Crosley

Technical founder of [941 Apps](https://941apps.com). Previously VP of Product Design at ZipRecruiter (2012–2024, from about ten people to the NYSE) and CTO at Introl (2025–2026).

Since 2024 I have built ten App Store products and two web platforms alone, working with coding agents inside a harness I wrote to govern them: every tool call passes through hooks (drift detection, an evidence gate on completion claims, recursion limits, sandboxing, key-exposure guards), and nothing ships on the agent's own say-so. Operating those agents for a year turned into empirical work on how autonomous systems fail.

**Code**

- [appstore-connect-mcp](https://github.com/blakecrosley/appstore-connect-mcp): a read-only MCP server for the App Store Connect API, with a daily check that runs with no model; [what the API taught me](https://blakecrosley.com/blog/appstore-connect-mcp-read-only)
- [agent-harness-excerpts](https://github.com/blakecrosley/agent-harness-excerpts): the drift detector, evidence gate, recursion guard, and key-exposure guard from that harness, with tests and the seven-failure-modes doc

**Writing**

- [Agent security series](https://blakecrosley.com/writing/agent-security): incident analyses of sandbox escapes read as reward hacking, auto-mode classifiers as (non-)security boundaries, trust-dialog and MCP CVEs
- [Public comment to NIST CAISI on AI agent security](https://blakecrosley.com/blog/nist-agent-security-rfi), docket NIST-2025-0035, February 2026
- [Agent Architecture guide](https://blakecrosley.com/guides/agent-architecture) · [Loop Engineering guide](https://blakecrosley.com/guides/loop-engineering) · [Claude Code guide](https://blakecrosley.com/guides/claude-code), revised against each CLI release

**Products**: Reps · Randori · Kiradex · ResumeGeni · Ace Citizenship · Return · Get Bananas · 941 Tiles · Founder Camera · Tappy Color

**Stack**: Python (FastAPI), Swift 6 / SwiftUI / SwiftData / CloudKit, Postgres, Cloudflare Workers and D1, Claude Code and Codex CLI, MCP

[blakecrosley.com](https://blakecrosley.com) · blake@941apps.com
