# FastMCP Weather Server with HTTP-Streaming Transport Example

Minimal FastMCP weather server using http-streaming transport example, exposing `get_alerts` and `get_forecast`.

Install and run:

```bash
uv sync
uv run fast-mpc-server
```

Then use an mcp client to connect to `http://127.0.0.1:8000/mcp`
