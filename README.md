# agenticweb-schemas

Open JSON Schemas, executable front-door origin probe rules, controlled facet vocabulary, and Model Context Protocol (MCP) tool definitions published by **[Agentic Web Wiki](https://agenticweb.wiki)** (Belgravia Labs).

## Contents (MIT License)

| Path | Live Canonical Endpoint | Description |
|---|---|---|
| [`schema/`](./schema/) | [`https://agenticweb.wiki/data/schema/`](https://agenticweb.wiki/data/schema/) | JSON Schemas for protocol, instance, glossary term, digest, probe, and vocabulary records |
| [`probes.json`](./probes.json) | [`https://agenticweb.wiki/data/probes.json`](https://agenticweb.wiki/data/probes.json) | 37 executable RFC 8615 / RFC 9309 front-door origin probe rules powering [`/check/`](https://agenticweb.wiki/check/) |
| [`vocab.json`](./vocab.json) | [`https://agenticweb.wiki/data/vocab.json`](https://agenticweb.wiki/data/vocab.json) | 9-step lifecycle model and controlled facet vocabulary |
| [`mcp-tools.json`](./mcp-tools.json) | [`https://agenticweb.wiki/mcp`](https://agenticweb.wiki/mcp) | Tool schemas for the public Streamable HTTP MCP server |
| [`server.json`](./server.json) | [`https://agenticweb.wiki/mcp/server-card`](https://agenticweb.wiki/mcp/server-card) | MCP Registry server descriptor (`wiki.agenticweb/probe`) |

## Per-Record Machine Twins & Live Endpoints

Every standard, comparison, and glossary page on [`agenticweb.wiki`](https://agenticweb.wiki) serves HTML, a Markdown twin (`<page>/index.md` or `Accept: text/markdown`), Open Knowledge Format (`/okf/protocols/<id>.md`), and structured JSON (`/data/protocols/<id>.json`) under **CC BY 4.0** (attribution: *Agentic Web Wiki (by Belgravia Labs)* with a link to `https://agenticweb.wiki/`). Full schema & licensing details: <https://agenticweb.wiki/data/>.

## Corrections & Issue Tracker

Found a false-negative probe rule, schema bug, or outdated specification version?
- Open an issue in this repository, use <https://agenticweb.wiki/submit/>, or email `contact@agenticweb.wiki`.
