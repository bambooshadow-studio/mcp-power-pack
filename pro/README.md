# Pro Tier — MCP Power Pack

**Thank you for your purchase!** This directory contains the full set of MCP configurations, Cursor rules, and agent skills.

## Contents

### 1. MCP Server Configurations (`mcp-servers/`)

**20+ pre-configured MCP servers**, ready to use with Cursor IDE or Claude Desktop.

All servers are defined in `mcp-servers.json`. To use:

1. Open Claude Desktop → Settings → Developer → Edit Config
2. Or open Cursor → Settings → MCP
3. Paste the server configuration from `mcp-servers.json`

**Included servers:**

| Server | Description |
|--------|-------------|
| Browser | Web browsing & scraping via Playwright |
| GitHub | Repository management & API access |
| Filesystem | Local file read/write |
| Fetch | Web content fetching |
| Notion | Notion workspace API |
| Slack | Slack messaging |
| Discord | Discord bot |
| PostgreSQL | Database queries & schema |
| SQLite | Local database operations |
| Redis | Cache & data structures |
| Docker | Container management |
| Kubernetes | Cluster management |
| Stripe | Payment processing |
| Supabase | Project management |
| Elasticsearch | Search & indexing |
| Memory | AI agent memory & knowledge graph |
| Brave Search | Web search API |
| Exa | AI-powered search |
| Firebase | Firestore operations |
| Sentry | Error tracking |
| Linear | Project management |
| Figma | Design file access |
| YouTube | Video transcripts |
| Weather | Forecast data |

### 2. Cursor Rules (`cursor-rules/`)

**15+ AI coding rules** to supercharge your Cursor IDE. Copy to `~/.cursor/rules/`:

```
cp pro/cursor-rules/*.mdc ~/.cursor/rules/
```

| Rule | Purpose |
|------|---------|
| ai-code-review.mdc | Automated code review on every PR |
| ai-test-generation.mdc | Generate tests for all code changes |
| ai-context-management.mdc | Manage long sessions with summaries |
| ai-documentation.mdc | Document APIs and complex logic |
| ai-security-review.mdc | Security vulnerability scanning |
| ai-mcp-development.mdc | MCP server development guidelines |

### 3. Agent Skills (`agent-skills/`)

**19 production-ready agent skills** for common development and business tasks.

Copy `skills-registry.json` to your AI agent configuration.

| Skill | Use Case |
|-------|----------|
| Code Reviewer | PR review, code quality |
| Security Auditor | Vulnerability scanning |
| Data Analyst | Insights & analysis |
| Debugger | Bug hunting |
| Content Creator | Blog & social media |
| Decision Helper | Trade-off analysis |
| Fact Checker | Source verification |
| Fullstack Developer | Web application build |
| UX Designer | UI/UX feedback |
| Project Planner | Roadmaps & milestones |
| Meeting Notes | Summaries & action items |
| Email Drafter | Professional emails |
| Technical Writer | Documentation |
| Academic Researcher | Literature review |
| Strategy Advisor | Business analysis |
| Editor | Proofreading |
| Deep Research | Multi-source investigation |
| Sprint Planner | Agile planning |
| Python Expert | Python optimization |

---

**Need help?** Open an issue at [github.com/bambooshadow-studio/mcp-power-pack](https://github.com/bambooshadow-studio/mcp-power-pack)
