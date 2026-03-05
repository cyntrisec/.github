# Org Maintenance Checklist

Manual steps that should be verified after profile or positioning updates.

## Pin Core Repos

1. Open https://github.com/cyntrisec
2. Click `Customize your pins`
3. Pin these 4 repos (in order):
   - `EphemeralML`
   - `air-v1`
   - `confidential-ml-transport`
   - `confidential-ml-pipeline`
4. Keep Labs repos unpinned:
   - `cyntrisec-cli`
   - `clawprint`

## MCP Marketplace Claim / Verification

The CLI is published in the Official MCP Registry as `io.github.cyntrisec/cyntrisec`, and appears in MCP Marketplace as an imported listing.

1. Open the listing page: `https://mcp-marketplace.io/server/io-github-cyntrisec-cyntrisec`
2. Click `Claim with GitHub` from that page (or use `https://mcp-marketplace.io/signup?claim=io-github-cyntrisec-cyntrisec`)
3. In the GitHub OAuth screen, verify:
   - App name is `MCP Marketplace`
   - Requested scopes are minimal and expected for identity/ownership verification
4. Do not approve broad/unrelated scopes (write/admin over repos/org) unless there is a clear, documented need
5. After claim, verify listing metadata:
   - Repository: `https://github.com/cyntrisec/cyntrisec-cli`
   - MCP name: `io.github.cyntrisec/cyntrisec`
   - Description aligns with current README positioning

## Profile Render Check

1. Push updates to the `.github` organization-profile repository (`profile/README.md`)
2. Open https://github.com/cyntrisec and verify:
   - `Core Product` appears first
   - `Labs / Tools` appears second
   - All links resolve
