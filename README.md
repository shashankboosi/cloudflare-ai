# Cloudflare

This repository contains the code to create an MCP server and deploy it on Cloudflare

## Pre-requisites

Before starting this workshop, please ensure you have the following installed:

Node.js (version 18 or later) - Download
Wrangler CLI - Install with `npm install -g wrangler`
A Cloudflare account for deployments

## Getting started

1. Create a new MCP Server using the Cloudflare template

```bash
npm create cloudflare@latest -- my-mcp-server --template=cloudflare/ai/demos/remote-mcp-authless
```

2. Navigate to the project directory

```bash
cd my-mcp-server
```

3. Run this MCP Server locally
   You can start your MCP Server by running the following command:

```bash
npm start
```

## Testing

Test your MCP Server using MCP inspector
To test your MCP Server, you can use the MCP inspector:

```bash
npx @modelcontextprotocol/inspector
```
