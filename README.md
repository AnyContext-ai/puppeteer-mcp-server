# puppeteer-mcp-server
A Model Context Protocol server that provides browser automation capabilities using Puppeteer. This server enables LLMs to interact with web pages, take screenshots, and execute JavaScript in a real browser environment.

### Build and run
```
docker build -t puppeteer-mcp-server .

docker run --rm -p 8000:8000 puppeteer-mcp-server
```