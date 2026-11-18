<p align="center"><img src="logo.svg" width="96" alt="Sitecomb logo"></p>

# Sitecomb: website quality review for any website (MCP server)

Sitecomb checks any public website, including ones built with AI tools, and gives it a **website quality review** across six areas: Security, Privacy & legal, Page health, Phone friendly, Contact details, and Online visibility (including AI search). The review is scored out of 100 and shows the **areas that have problems**, with a count for each.

This is a **hosted, remote MCP server**. There is nothing to install or run, and no code in this repository: it holds the server description (`server.json`) and this page.

## Connect

- **Server URL:** `https://sitecomb.com/mcp` (Streamable HTTP, no sign-in needed)
- **Claude:** Settings → Connectors → Add custom connector → paste the URL above. Guide: https://sitecomb.com/claude
- **Other MCP clients:** add a remote server with the URL above.

## Tool

| Tool | What it does |
|---|---|
| `check_website` | Checks a public website the way a visitor's browser loads it. Returns a website quality review across six areas (Security, Privacy & legal, Page health, Phone friendly, Contact details, Online visibility): the areas that have problems, with a count for each, and an overall score out of 100. It only reads public pages; it never changes anything on the site. |

Checks are limited per person and per website each day. If a site is down or blocks automated checkers, Sitecomb says it couldn't check and gives no website quality review.

## Example

> "Check https://example.com for problems."

The full quality report, with a fix for every problem, is at https://sitecomb.com.

## About

Website: https://sitecomb.com · Contact: hello@sitecomb.com · Privacy: https://sitecomb.com/privacy · Terms: https://sitecomb.com/terms

## Licence

This repository (the README and the registry metadata) is MIT licensed: see [LICENSE](LICENSE).
