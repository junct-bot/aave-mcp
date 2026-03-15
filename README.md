# Aave MCP Server

MCP server for Aave. Agent-ready API for Aave.

Hosted at [aave.mcp.junct.dev/mcp](https://aave.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for web3.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "aave": {
      "url": "https://aave.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Aave API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints.

- **Protocol:** Aave
- **Endpoint:** `https://aave.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [aave.mcp.junct.dev/llms.txt](https://aave.mcp.junct.dev/llms.txt)

## Links

- [Junct Dashboard](https://junct.dev/servers/aave)
- [llms.txt](https://aave.mcp.junct.dev/llms.txt)
- [agents.md](https://aave.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://aave.mcp.junct.dev/openapi.json)

Keywords: Aave, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol
