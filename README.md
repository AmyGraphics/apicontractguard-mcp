# 🔌 APIContractGuard MCP

Safe live API contract validation, drift detection and release gating.

APIContractGuard parses OpenAPI JSON, probes read-only endpoints, compares expected behavior, detects contract drift and creates a release gate. Mutating methods are never automatically called.

## Tools

- `api.architect`
- `contract.parse`
- `endpoints.probe_live`
- `schema.validate_live`
- `contract.drift_live`
- `api.health_report_live`
- `release.gate`

## Quick start

```json
{
  "mcpServers": {
    "apicontractguard": {
      "url": "https://apicontractguard68-api.agentweb-hub.workers.dev/mcp"
    }
  }
}
```

Start free — 10 requests/day, no signup, no card.

Gumroad: https://amygraphics.gumroad.com/l/mcp-pro — $7.99 single or $14.99 all-access.

Solana USDC:

```text
8sDLX3okSV974wdjdeKhN9uWLZDr45DeGCJ28zgTLEdJ
```
