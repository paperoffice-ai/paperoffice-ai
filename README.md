<div align="center">

<img src="https://paperoffice.ai/images/logos/logo_paperoffice_ai.webp" alt="PaperOffice AI" width="200">

# PaperOffice AI

**Enterprise Document AI & API Platform**

357+ AI-powered API Tools · MCP-first · Zero-Friction API

[![Website](https://img.shields.io/badge/Website-paperoffice.ai-00bcd4?style=for-the-badge&logo=globe&logoColor=white)](https://paperoffice.ai)
[![API](https://img.shields.io/badge/API_Docs-Postman-ff6c37?style=for-the-badge&logo=postman&logoColor=white)](https://api.paperoffice.ai/dev/docs/postman)
[![MCP](https://img.shields.io/badge/MCP_Server-Live-8b5cf6?style=for-the-badge&logo=zap&logoColor=white)](https://paperoffice.ai/en/developer/mcp/)

</div>

---

## What is PaperOffice AI?

PaperOffice AI is an enterprise-grade document AI platform with 357+ API tools for OCR, IDP, document classification, e-signatures, knowledge graphs, AI agents, and more.

**One API. One MCP connection. Every AI tool you need.**

## Quick Start

### MCP (Recommended)

Connect your AI coding assistant — Claude, Cursor, Windsurf, or any MCP client:

```json
{
  "mcpServers": {
    "paperoffice": {
      "url": "https://mcp.paperoffice.ai/mcp"
    }
  }
}
```

> Full MCP Setup Guide: [github.com/paperoffice-ai/paperoffice-mcp-setup](https://github.com/paperoffice-ai/paperoffice-mcp-setup)

### REST API

```bash
curl -X POST https://api.paperoffice.ai/dev/job/add \
  -F "file=@invoice.pdf" \
  -F "tool_id=po_aiocr_analyze"
```

> No SDK needed. REST + JSON. Works with every language.

## Developer Resources

| Resource | Description |
|----------|-------------|
| [Postman Collection](https://api.paperoffice.ai/dev/docs/postman) | 357+ endpoints, fully documented |
| [MCP Setup](https://github.com/paperoffice-ai/paperoffice-mcp-setup) | Client configs for Claude, Cursor, Windsurf |
| [AI Cookbook](https://paperoffice.ai/en/developer/cookbook/) | Production-ready recipes & prompts |
| [Get API Key](https://app.paperoffice.ai) | Free account, instant access |
| [Partner Program](https://paperoffice.ai/en/partner/) | Up to 40% LIFETIME commission |

## Platform Highlights

- **Document AI** — OCR, IDP, classification, data extraction, bounding boxes
- **Agent AI** — RAG, knowledge base, semantic search, custom agents
- **Automation** — Workflows, webhooks, auto-responses, rules engine
- **Security** — E-signatures, anonymization, fraud detection, audit trails
- **MCP Server** — 357+ tools via natural language, OAuth 2.1 & Bearer auth

## Connect

- [paperoffice.ai](https://paperoffice.ai)
- [info@paperoffice.ai](mailto:info@paperoffice.ai)
- Pamplona, Spain · EU Datacenter · GDPR compliant

---

<div align="center">
<sub>PaperOffice AI — Enterprise Document Intelligence since 2002</sub>
</div>
