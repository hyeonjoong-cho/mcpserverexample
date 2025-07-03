# Installation steps

To install the 'add_tool' MCP server, run the following commands:
Add the following installation 

```json
{
  "mcpServers": {
    "add_tool": {
      "command": "/Users/raycho-mbp/.local/bin/uvx",
      "args": [
        "--from",
        "git+https://github.com/hyeonjoong-cho/mcpserverexample.git",
        "mcp-server"
      ]
    }
  }
}
```