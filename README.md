# MCP DNS

A Model Context Protocol (MCP) tool that provides DNS querying capabilities. This tool allows you to perform DNS lookups for various record types through a standardized MCP interface.

<a href="https://glama.ai/mcp/servers/@glucn/mcp-dns">
  <img width="380" height="200" src="https://glama.ai/mcp/servers/@glucn/mcp-dns/badge" alt="DNS MCP server" />
</a>

## Features

- DNS querying for various record types (A, AAAA, MX, TXT, CNAME, NS, etc.)
- Simple and standardized MCP interface
- Built with TypeScript for type safety
- Uses Node.js native DNS module

## Usage

The tool provides a `dns-query` command that accepts two parameters:

- `name`: The domain name to query
- `type`: The DNS record type (A, AAAA, MX, TXT, CNAME, NS, etc.)

## Development

### Prerequisites

- Node.js (latest LTS version recommended)
- npm

### Setup

1. Clone the repository:

```bash
git clone https://github.com/glucn/mcp-dns.git
cd mcp-dns
```

2. Install dependencies:

```bash
npm install
```

3. Build the project:

```bash
npm run build
```

### Project Structure

- `src/` - Source code directory
  - `server.ts` - Main server implementation
- `build/` - Compiled JavaScript output
- `package.json` - Project configuration and dependencies

## Dependencies

- [@modelcontextprotocol/sdk](https://www.npmjs.com/package/@modelcontextprotocol/sdk) - MCP SDK for server implementation
- [zod](https://www.npmjs.com/package/zod) - TypeScript-first schema validation
- TypeScript - For type safety and modern JavaScript features