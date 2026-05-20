# Evaluation Guide

Use this page to evaluate whether A2A Replay Receipt fits a real workflow.

## What To Test

- A2A failure replay MCP
- A2A Replay Receipt
- A2A Replay Receipt documentation
- A2A Replay Receipt remote MCP
- a2areplayreceipt server card

## Expected Evidence

- Open A2A Replay Receipt and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://a2areplayreceipt.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call replay_a2a_failure with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://a2areplayreceipt.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=a2areplayreceipt_public_docs&utm_content=evaluation_checkout
