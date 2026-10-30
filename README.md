## OpenWAF

A managed WAF, bot and AI-agent control, edge cache and authoritative DNS for every site you run. Edge nodes in Germany and Spain. Every change is checked, signed (Ed25519), versioned and one command from undo.

**Website:** [openwaf.dev](https://openwaf.dev) | **Docs:** [developers.openwaf.dev](https://developers.openwaf.dev) | **Contact:** support@openwaf.dev | **Security:** security@openwaf.dev

### Open source

| Repository | What it is |
|---|---|
| [**verify**](https://github.com/openwaf-dev/verify) | OpenWAF Verify: proof-of-work check for forms and API calls, served first party from your own host. Widget, protocol spec and siteverify clients for Go, Node.js and PHP. See [Verify open source](https://developers.openwaf.dev/waf/verify-open-source/). |
| [**egress**](https://github.com/openwaf-dev/egress) | Zero-trust outbound gateway for AI agents: prompt-injection shield, DLP, SSRF defense and live API-key injection from OpenBao / Vault. Single Go binary. |
| [**egress-action**](https://github.com/openwaf-dev/egress-action) | Egress for CI (beta): a GitHub Action that puts a job's outbound traffic, containers included, behind an allowlist in `.github/egress.yml`. Audit first, then enforce. See the [quickstart](https://developers.openwaf.dev/egress/ci/quickstart/) and the [Marketplace](https://github.com/marketplace/actions/openwaf-egress-ci) listing. |

### Build on OpenWAF

- **REST API:** zones, DNS records, edge settings, rules, analytics and AI agents. See the [API reference](https://developers.openwaf.dev/api/).
- **MCP server:** manage OpenWAF from Claude, ChatGPT or Cursor over OAuth 2.1. See [MCP](https://developers.openwaf.dev/mcp/).
- **CLI and SDKs:** see [CLI](https://developers.openwaf.dev/cli/) and [SDK](https://developers.openwaf.dev/sdk/).

Found a vulnerability? Please read our [disclosure policy](https://openwaf.dev/security/) and write to security@openwaf.dev.
