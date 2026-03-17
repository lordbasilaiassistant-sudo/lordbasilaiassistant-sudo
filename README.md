# Clawbster

Builder. Father of 6. Neurodivergent problem solver.

I build autonomous systems on Base chain. My AI agents write code, deploy contracts, and operate protocols — 24/7, no human in the loop.

---

### ThryxProtocol — The AI Agent Launchpad

The first token launchpad built for autonomous operators. Launch tokens for $0. Trade with 0.5% fees (70% to creators). Gasless via EIP-712.

**Live now:**

| | |
|---|---|
| **Launchpad** | [thryx-launchpad.onrender.com](https://thryx-launchpad.onrender.com) |
| **Diamond** | [`0x2F77...2cCe`](https://basescan.org/address/0x2F77b40c124645d25782CfBdfB1f54C1d76f2cCe) on Base |
| **MCP Server** | [`@thryx/mcp-server`](https://www.npmjs.com/package/@thryx/mcp-server) — 15 tools for AI agents |
| **CLI** | [`@thryx/cli`](https://www.npmjs.com/package/@thryx/cli) — `npx @thryx/cli launch "My Token" MYTKN` |
| **ElizaOS** | [`@thryx/elizaos-plugin`](https://www.npmjs.com/package/@thryx/elizaos-plugin) — 5 actions |
| **Relay** | [thryx-relay.thryx.workers.dev](https://thryx-relay.thryx.workers.dev/health) — gasless launches |

**Architecture:** EIP-2535 Diamond proxy, 7 facets, Uniswap V4 graduation, per-token ETH reserves, self-funding paymaster, ERC-7572 metadata, ERC-8004 Agent #31507.

78 tokens launched. Zero rug pulls. Same contract address forever.

---

### How I Build

Claude Code writes the contracts, deploys them, operates the wallets, claims fees, and routes gas — autonomously. I architect the system, set the rules, and let the agents execute.

```
Solidity → Hardhat → Base mainnet
Node.js → ethers.js v6 → Multicall3
React → Vite → Render
Cloudflare Workers → gasless relay
MCP → any AI agent can operate the protocol
```

---

### Base MCP Ecosystem

Open-source MCP servers for Base chain:

| Server | What it does |
|--------|-------------|
| [base-multi-wallet-mcp](https://github.com/lordbasilaiassistant-sudo/base-multi-wallet-mcp) | Coordinated multi-wallet trading |
| [base-price-oracle-mcp](https://github.com/lordbasilaiassistant-sudo/base-price-oracle-mcp) | On-chain DEX price feeds |
| [base-gasless-deploy-mcp](https://github.com/lordbasilaiassistant-sudo/base-gasless-deploy-mcp) | Gasless ERC-20 deployment |
| [base-flash-arb-mcp](https://github.com/lordbasilaiassistant-sudo/base-flash-arb-mcp) | Cross-DEX arbitrage detection |
| [base-security-scanner-mcp](https://github.com/lordbasilaiassistant-sudo/base-security-scanner-mcp) | Smart contract security scanning |

---

### Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=lordbasilaiassistant-sudo&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=lordbasilaiassistant-sudo&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9)

---

<sub>79 public repos. Most of the real work is private. If you're building with AI agents on Base, the MCP server is free — just `npx @thryx/mcp-server`.</sub>
