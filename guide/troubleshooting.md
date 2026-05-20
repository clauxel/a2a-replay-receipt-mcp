# Troubleshooting

## Public Website Does Not Load

Check the clean homepage first:

- https://a2areplayreceipt.clauxel.com/

Then use the tracked documentation link:

- https://a2areplayreceipt.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=a2areplayreceipt_public_docs&utm_content=troubleshooting_home

## Checkout Link Fails

Use the public checkout route and avoid adding private account information to GitHub issues.

- https://a2areplayreceipt.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=a2areplayreceipt_public_docs&utm_content=troubleshooting_checkout

## MCP Request Fails

- Confirm the endpoint is exactly `https://a2areplayreceipt.clauxel.com/mcp`.
- Confirm the request is POST JSON-RPC.
- Confirm the bearer token is stored outside public files.
