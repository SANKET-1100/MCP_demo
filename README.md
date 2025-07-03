# MCP Server Example - weather forecast for states and cities in USA

This is a example of a Model Context Protocol (MCP) server implementation that demonstrates core functionality including tools and resources.

## Setup Steps

1. Initialize the project (Go to any local folder and launch powershell or cmd):
```bash
uv init DEMO
cd DEMO
```

2.  # Create virtual environment and activate it
```bash
  uv venv
  .venv\Scripts\activate
  ```

3. Install dependencies:
```bash
uv add "mcp[cli]"
```
or 
```bash
uv add -r requirements.txt
```




## Running the Server

To run the server with the MCP Inspector for development: It will ask to download MCP Inspector click Yes and it will get dowloaded. Open the MCP inspector in browser and Connect it with server and Click on list tools you will find weather tool then select it and you are good to go. ask the queries and it will respond accordingly.
```bash
uv run mcp dev server/weather.py
```
