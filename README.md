# Installation Steps

To install the 'Myadd' MCP server, run the following command to your MCP client

```json
{
"mcpServers": {
    "Myadd":{
      "command": "uvx",
      "args": [
      "--from",
      "git+https://github.com/tguenon/mcpserverexample.git",
      "mcp-server"
      ]
    }
  }
}
  ```

  This will fetch and set-up the 'mcp-server' from the specified GitHub repository.