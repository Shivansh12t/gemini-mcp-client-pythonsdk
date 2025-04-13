# Gemini MCP Client

## Prerequisites
1. `uv` package manager
2. Gemini API Key
3. A MCP Server using `stdio` transport

## QuickStart
1. Clone the Respository
```bash
git clone https://github.com/Shivansh12t/gemini-mcp-client-pythonsdk gemini-client
cd gemini-client
```
2. Create a `.env` as per `template.env`
```bash
echo "GEMINI_API_KEY=<YOUR_API_KEY_HERE>" > .env
```
3. Use `uv` package manager to run the client with the server path
```bash
uv run client.py <PATH-TO-MCP-SERVER>
```

**Note**: MCP Server must be created using PythonSDK & must be Using `stdio` transport

**Note**: It is recommended to run the server using unix based platforms, since asyncio is not very stable in windows, i personally recommend using `wsl` for windows users.


## Credits
youtube tutorial - [theailanguage](https://github.com/theailanguage/mcp_client)