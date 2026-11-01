# Knacco plugins

Bring your Knacco library into your AI tool. Browse and search the skills, workflows, guides and tools you own, read each product's guide in the conversation, and get a secure, short-lived download link for its files. Sign in with your Knacco account, choose how long the connection lasts, and disconnect at any time from your account settings.

- **Sign-in:** the first time you use Knacco, your tool opens a Knacco sign-in page. You approve the connection and choose how long it lasts (30, 60 or 90 days, or no expiry).
- **Data use:** a connected tool has read-only access to the titles of the products you own, their guides and file names, and short-lived download links. It never sees payment details and cannot change your account. Details: https://knacco.com/en/policies/privacy
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
