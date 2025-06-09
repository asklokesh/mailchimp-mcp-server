# Mailchimp MCP Server

<div align="center">

# Mailchimp Mcp Server

[![GitHub stars](https://img.shields.io/github/stars/LokiMCPUniverse/mailchimp-mcp-server?style=social)](https://github.com/LokiMCPUniverse/mailchimp-mcp-server/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/LokiMCPUniverse/mailchimp-mcp-server?style=social)](https://github.com/LokiMCPUniverse/mailchimp-mcp-server/network)
[![GitHub watchers](https://img.shields.io/github/watchers/LokiMCPUniverse/mailchimp-mcp-server?style=social)](https://github.com/LokiMCPUniverse/mailchimp-mcp-server/watchers)

[![License](https://img.shields.io/github/license/LokiMCPUniverse/mailchimp-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/mailchimp-mcp-server/blob/main/LICENSE)
[![Issues](https://img.shields.io/github/issues/LokiMCPUniverse/mailchimp-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/mailchimp-mcp-server/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/LokiMCPUniverse/mailchimp-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/mailchimp-mcp-server/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/LokiMCPUniverse/mailchimp-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/mailchimp-mcp-server/commits)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-DC143C?style=for-the-badge)](https://modelcontextprotocol.io)

[![Commit Activity](https://img.shields.io/github/commit-activity/m/LokiMCPUniverse/mailchimp-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/mailchimp-mcp-server/pulse)
[![Code Size](https://img.shields.io/github/languages/code-size/LokiMCPUniverse/mailchimp-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/mailchimp-mcp-server)
[![Contributors](https://img.shields.io/github/contributors/LokiMCPUniverse/mailchimp-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/mailchimp-mcp-server/graphs/contributors)

</div>

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
