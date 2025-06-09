# Xero MCP Server

A Model Context Protocol (MCP) server for integrating Xero with GenAI applications.

## Overview

Cloud-based accounting software integration

## Features

- Comprehensive Xero API coverage
- Multiple authentication methods
- Enterprise-ready with rate limiting
- Full error handling and retry logic
- Async support for better performance

## Installation

```bash
pip install xero-mcp-server
```

Or install from source:

```bash
git clone https://github.com/asklokesh/xero-mcp-server.git
cd xero-mcp-server
pip install -e .
```

## Configuration

Create a `.env` file or set environment variables according to Xero API requirements.

## Quick Start

```python
from xero_mcp import XeroMCPServer

# Initialize the server
server = XeroMCPServer()

# Start the server
server.start()
```

## License

MIT License - see LICENSE file for details
