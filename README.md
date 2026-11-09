# piktcg-ucp-test

Public hosting for a minimal [UCP](https://ucp.dev) (Universal Commerce
Protocol) platform agent profile — a small JSON document a UCP-speaking
business (e.g. a Shopify store) fetches via `meta.ucp-agent.profile` during
MCP negotiation.

This exists purely so the file has a genuinely public, anonymously
fetchable HTTPS URL, with no auth required — needed for a one-off live test
confirming whether `search_catalog` actually works once a valid profile is
supplied, as part of evaluating UCP as a product-discovery source for
[PikTCG](https://github.com/NeuroMint/PikTCG) (private repo). See
`src/experimental/ucp/README.md` there for the full context.

**Not a production endpoint.** This repo is test infrastructure, kept
separate from PikTCG's own codebase deliberately — see that repo's
`src/experimental/ucp/` module, which is itself explicitly isolated from
any production retailer tracking.

Raw file: `https://raw.githubusercontent.com/NeuroMint/piktcg-ucp-test/main/agent-profile.json`
