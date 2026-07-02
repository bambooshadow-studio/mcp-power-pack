# Free MCP Servers

These servers are free to use with any MCP-compatible client (Cursor, Claude Desktop, etc.).

## Browser (Playwright)
Web browsing and scraping.
```bash
npx @playwright/mcp@latest
```

## GitHub
Repository management and GitHub API access.
```bash
export GITHUB_PERSONAL_ACCESS_TOKEN=your_token_here
npx -y @modelcontextprotocol/server-github
```

## Notion
Notion workspace integration.
```bash
npx -y @modelcontextprotocol/server-notion
```

## Filesystem
Read, write, and manage local files.
```bash
npx -y @modelcontextprotocol/server-filesystem /path/to/allowed/dir
```

## Fetch
Fetch and process web content.
```bash
npx -y @modelcontextprotocol/server-fetch
```
