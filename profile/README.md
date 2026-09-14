# UCP Checker

### The independent validator and public directory for the Universal Commerce Protocol.

We build open infrastructure to help developers verify, debug, and monitor Agent Commerce readiness.

---

### 🚀 **Ecosystem Utilities**

| Utility | Description | Status |
| :--- | :--- | :--- |
| **[UCPChecker.com](https://ucpchecker.com)** | The community directory and live debugger. | 🟢 **Live** |
| **[UCP Score](https://ucpchecker.com/score)** | Agent-readiness grade. 0–100 score per domain across capability coverage, reliability, performance, and schema conformance. Embeddable SVG badges. | 🟢 **Live** |
| **[UCP Status](https://ucpchecker.com/status)** | Live verdict — Verified / Invalid / Blocked — for any domain, with shareable status pages. | 🟢 **Live** |
| **[Developer Tools](https://ucpchecker.com/developer-tools)** | The builder hub — APIs, SDKs, score badges, manifest endpoint reference, and downloadable datasets. | 🟢 **Live** |
| **[Playground](https://ucpplayground.com/)** | Interactive UCP Playground — browse catalogs, test checkout flows, and inspect MCP/REST transports against any UCP-enabled merchant. | 🟢 **Live** |
| **[Browser Extension](https://chromewebstore.google.com/detail/ucp-checker-agent-debugge/dbanbolebapmmjmeemhbddkelocjaolh?hl=en)** | UCP Checker & Agent Debugger — detect manifests, surface agent-readiness signals, and feed anonymous uptime stats to the community. | 🟢 **Live** |
| **[API & MCP Docs](https://ucpchecker.com/docs)** | Connect any agent in one snippet — keyless MCP server (check domains, find verified stores, search live catalogs, then shop at the store directly), REST API, ARD discovery, rate limits, score methodology & versioning. | 🟢 **Live** |
| **[MCP Server](https://ucpchecker.com/docs#mcp-server)** | `https://ucpchecker.com/mcp` — Model Context Protocol server: 8 tools reflected in the docs; listed in the official MCP Registry as `com.ucpchecker/ucp-checker` and on Smithery. | 🟢 **Live** |
| **[Agent Finder (ARD)](https://ucpchecker.com/docs#post-ard-search)** | Agentic Resource Discovery service over verified UCP storefronts — `POST /ard/search`, canonical /.well-known/ard.json; could add that it covers every verified storefront (~17k), labelled by evidence | 🟢 **Live** |
| **[CLI: ucp-check](https://github.com/ucpchecker/ucp-check)** | `npx ucp-check <domain>` — the same verdict as the status page, from a terminal or CI, as an exit code (`0` verified · `1` not · `2` usage · `3` API). Zero dependencies, no key; on [npm](https://www.npmjs.com/package/ucp-check). | 🟢 **Live** |
| **[Agent Skills](https://github.com/ucpchecker/ucp-checker-skills)** | `ucp-checker` (find and shop verified stores) and `ucp-agent-ready` (make a store agent-ready) — served live at `/.well-known/agent-skills/`, mirrored here, published on Smithery. | 🟢 **Live** |

### 📊 **Live Ecosystem Stats**
*Tracking the adoption of Agent Commerce.*

* **Verified Merchants:** 17,000+
* **Top Platform:** Shopify
* **Average Latency:** 142ms

[View full live statistics →](https://ucpchecker.com/stats)

---

### **About**
UCP Checker is an independent project dedicated to accelerating the adoption of the Universal Commerce Protocol. We provide neutral, third-party validation to ensure interoperability between any Agent platform and Merchants.

_Maintained by the UCP Checker Team._
