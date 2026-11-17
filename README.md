# Knacco — AI skills and workflows in your tools

Bring your Knacco library into your AI tool. Browse and search the skills, workflows, guides and tools you own, read each product's guide in the conversation, and get a secure, short-lived download link for its files. Sign in with your Knacco account, choose how long the connection lasts, and disconnect at any time from your account settings.

- **Sign-in:** the first time you use Knacco, your tool opens a Knacco sign-in page. You approve the connection and choose how long it lasts (30, 60 or 90 days, or no expiry).
- **Data use:** a connected tool has read-only access to the titles of the products you own, their guides and file names, and short-lived download links. It never sees payment details and cannot change your account. Details: https://knacco.com/en/policies/privacy
- **Disconnect:** Knacco Account → Billing and security → Connected AI tools → Revoke.
- **Support:** https://knacco.com/en/policies/help · Help page: https://knacco.com/en/help/ai-tools

## Find a product for your work

[Explore the marketplace](https://knacco.com/en/marketplace) · [Browse all products](https://knacco.com/en/products) · [Start with free products](https://knacco.com/en/categories/free) · [Read practical guides](https://knacco.com/en/guides)

Knacco is an AI work library for creators, freelancers and small teams. Compare each product's purpose, compatibility, included files and examples on its product page. Add a product to your Knacco library, then connect a supported AI tool to use the materials you own.

The connector accesses your existing library. Product purchases and free claims take place on the Knacco website; the connector cannot buy products for you.

## Try your library

- “What is in my Knacco library?”
- “Search my library for a workflow.”
- “Open the guide for that product.”
- “Get a download link for that file.”

Download links expire after 30 seconds. Request another link when needed. Course lessons are not available through this connector; software and plugin products may provide file links without a guide.

## Install

- Claude Code: `/plugin install knacco --marketplace byoverseas/knacco-plugins`
- Cursor and Antigravity: use the configuration in this repository or follow the [connection guide](https://knacco.com/en/help/ai-tools).
- Other MCP clients: connect to `https://knacco.com/api/v1/agent/mcp` using OAuth. See the connection guide for supported clients.

Directory availability depends on each platform’s review. This repository does not imply that every marketplace listing has been approved.

| Folder | Tool |
|---|---|
| `claude/` | Claude Code plugin bundle |
| `cursor/` | Cursor plugin |
| `antigravity/` | Antigravity plugin |
| `.claude-plugin/marketplace.json` | Self-hosted Claude Code marketplace |

All plugins point at the same server: `https://knacco.com/api/v1/agent/mcp`. None contains a secret.
