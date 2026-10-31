# Knacco plugins

Use the Knacco products you own from your AI tool: list your library, search it, read a product's guide and get a short-lived download link.

- **Sign-in:** the first time you use Knacco, your tool opens a Knacco sign-in page. You approve the connection and choose how long it lasts (30, 60 or 90 days, or no expiry).
- **Data use:** a connected tool can see the titles of the products you own, their guides and file names, and get 120-second download links. It cannot buy anything, see payment details or change your account. Details: https://knacco.com/en/policies/privacy
- **Disconnect:** Knacco Account → Billing and security → Connected AI tools → Revoke.
- **Support:** https://knacco.com/en/policies/help · Help page: https://knacco.com/en/help/ai-tools

## Install

- Claude Code: `/plugin install knacco --marketplace byoverseas/knacco-plugins`
- Cursor and Antigravity: install from their marketplaces, or point them at this repository.

| Folder | Tool |
|---|---|
| `claude/` | Claude Code plugin bundle |
| `cursor/` | Cursor plugin |
| `antigravity/` | Antigravity plugin |
| `.claude-plugin/marketplace.json` | Self-hosted Claude Code marketplace |

All plugins point at the same server: `https://knacco.com/api/v1/agent/mcp`. None contains a secret.
