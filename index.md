# A2A Replay Receipt

A2A Replay Receipt is a hosted remote MCP for A2A failure replay MCP.

This repository is a public documentation project for A2A Replay Receipt. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://a2areplayreceipt.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=a2areplayreceipt_public_docs&utm_content=readme_home
- Pricing: https://a2areplayreceipt.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=a2areplayreceipt_public_docs&utm_content=readme_pricing
- Checkout: https://a2areplayreceipt.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=a2areplayreceipt_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://a2areplayreceipt.clauxel.com/mcp
- Server card: https://a2areplayreceipt.clauxel.com/server-card.json
- Registry name: `com.clauxel.a2areplayreceipt/a2areplayreceipt-mcp`
- Tools: `replay_a2a_failure`, `classify_agent_error`, `suggest_retry_plan`, `issue_replay_receipt`, `export_failure_log`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

developer platform teams, release owners, AI engineering leads, and delivery reviewers.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: replay_a2a_failure
- MCP tool: classify_agent_error
- MCP tool: suggest_retry_plan
- MCP tool: issue_replay_receipt
- MCP tool: export_failure_log

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
