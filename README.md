<p align="center"><img src="logo.svg" width="96" alt="Sitecomb logo"></p>

# Sitecomb: website check-ups for small businesses (MCP server)

Sitecomb checks a public small-business website and gives a **score out of 100** and the **most important problems** (up to three), each with a line on why it matters. It looks at six areas: security, privacy and legal notices, quality, phones, getting customers, and AI visibility.

This is a **hosted, remote MCP server**. There is nothing to install or run, and no code in this repository: it holds the server description (`server.json`) and this page.

## Connect

- **Server URL:** `https://sitecomb.com/mcp` (Streamable HTTP, no sign-in needed)
- **Claude:** Settings → Connectors → Add custom connector → paste the URL above. Guide: https://sitecomb.com/claude
- **Other MCP clients:** add a remote server with the URL above.

## Tool

| Tool | What it does |
|---|---|
| `check_website` | Checks a public website the way a visitor's browser loads it. Returns a score out of 100 and up to three main problems. It only reads public pages; it never changes anything on the site. |

Free checks are limited per person and per website each day. If a site is down or blocks automated checkers, Sitecomb says it couldn't check and gives no score.

## Example

> "Check https://example.com for problems."

The full report, with a fix for every problem, is available at https://sitecomb.com.

## About

Sitecomb is a product of Sahbis Limited, a company registered in Ireland (No. 821013). Website: https://sitecomb.com · Contact: hello@sitecomb.com · Privacy: https://sitecomb.com/privacy · Terms: https://sitecomb.com/terms
