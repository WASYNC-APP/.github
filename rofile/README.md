<p align="center">
  <img src="https://github.com/wasync-app.png" width="96" alt="WASync" />
</p>

<h1 align="center">WASync</h1>

<p align="center"><strong>WhatsApp for your CRM.</strong><br/>
Send and receive WhatsApp messages where your deals live — Bitrix24 and Pipedrive today, a Platform API and an MCP server for everything else.</p>

<p align="center">
  <a href="https://wasync.app">Website</a> ·
  <a href="https://wasync.app/features">Features</a> ·
  <a href="https://wasync.app/pricing">Pricing</a> ·
  <a href="https://cloudapi.wasync.app/docs">API docs</a> ·
  <a href="https://www.bitrix24.com/apps/app/tdacrm.wasync/">Bitrix24 Marketplace</a> ·
  <a href="https://www.youtube.com/@Wasync">YouTube</a>
</p>

---

## What it does

- **Two ways to connect a number** — scan a QR code with the WhatsApp you already use, or connect an official WhatsApp Business API account. [Which one is right for you →](https://wasync.app/whatsapp-qr-vs-business-api)
- **Messages inside the CRM** — every conversation lands on the lead, deal or contact it belongs to; your team replies from the CRM, with history, files, voice notes and templates.
- **Automations** — CRM robots and no-code chat flows that send, route and answer on WhatsApp.
- **A unified inbox** — all numbers, all operators, one screen, in 20 languages.
- **Platform API + MCP** — an OAuth2 REST API for your own product, and a hosted MCP server so an AI agent can read and send WhatsApp messages on your behalf.

## For developers

**REST API** — OpenAPI spec at [`cloudapi.wasync.app/openapi.json`](https://cloudapi.wasync.app/openapi.json), docs at [cloudapi.wasync.app/docs](https://cloudapi.wasync.app/docs).

**MCP server** — connect any MCP-capable client (Claude, Cursor, and others) to your WhatsApp numbers:

```json
{
  "mcpServers": {
    "wasync": {
      "url": "https://cloudapi.wasync.app/api/mcp"
    }
  }
}
