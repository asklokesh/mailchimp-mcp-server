# Mailchimp MCP Server

A Model Context Protocol (MCP) server for integrating Mailchimp with GenAI applications.

## Overview

Email marketing and automation platform

## Features

- Comprehensive Mailchimp API coverage
- Multiple authentication methods
- Enterprise-ready with rate limiting
- Full error handling and retry logic
- Async support for better performance

## Installation

```bash
pip install mailchimp-mcp-server
```

Or install from source:

```bash
git clone https://github.com/asklokesh/mailchimp-mcp-server.git
cd mailchimp-mcp-server
pip install -e .
```

## Configuration

Create a `.env` file or set environment variables according to Mailchimp API requirements.

## Quick Start

```python
from mailchimp_mcp import MailchimpMCPServer

# Initialize the server
server = MailchimpMCPServer()

# Start the server
server.start()
```

## License

MIT License - see LICENSE file for details
