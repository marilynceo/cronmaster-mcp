# cronmaster-mcp

Job scheduling and workflow orchestration for AI agents u2014 schedule, monitor, and orchestrate recurring jobs with dependencies, retries, logging, and alerting. SQLite-backed with zero external API costs.

## Quick Start

```bash
git clone https://github.com/marilynceo/cronmaster-mcp.git
cd cronmaster-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://cronmaster.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/cronmaster-mcp

# Or connect directly via MCP client
# Endpoint: https://cronmaster.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
