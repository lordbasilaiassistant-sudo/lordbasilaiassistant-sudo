# Thryx

Builder. Father of 6. Neurodivergent problem solver.

I build autonomous systems on Base. AI agents write the code, deploy the contracts, operate the wallets, and claim the fees — 24/7, no human in the loop. I architect, set the rules, and let them run.

🌐 [thryx.fun](https://thryx.fun) · ✉️ lordbasilaiassistant@gmail.com

---

## Stack

`Solidity` `Foundry` `Hardhat` `Base` `EVM` `TypeScript` `Node.js` `Python` `MCP` `Cloudflare Workers` `React` `Vite`

---

## Currently shipping

- **[onchain-primitives-lab](https://github.com/lordbasilaiassistant-sudo/onchain-primitives-lab)** — 7 immutable primitives on Base (stealth addresses, slashable promises, conditional drops, time capsule, group bounties, atomic swaps). 220 tests passing.
- **[keeper-bounty-lab](https://github.com/lordbasilaiassistant-sudo/keeper-bounty-lab)** — 5 keeper-bounty patterns + manual floor oracle. Permissionless automation markets. 129 tests passing.
- **[deadman-switch](https://github.com/lordbasilaiassistant-sudo/deadman-switch)** — On-chain dead-man switch. Lock ETH, ping on a schedule, beneficiary gets it if you stop. Immutable, no admin keys.
- **[TheAgentCafe](https://github.com/lordbasilaiassistant-sudo/TheAgentCafe)** — On-chain restaurant for AI agents. Agents buy food, eat for gas credits, keep transacting.
- **[x402-wiki](https://github.com/lordbasilaiassistant-sudo/x402-wiki)** — The x402 Service Encyclopedia. Community knowledge base for the AI agent economy.
- **[ThryxTokenChecks](https://github.com/lordbasilaiassistant-sudo/ThryxTokenChecks)** — Full-history analyzer + signal engine for Base ERC-20s. Uniswap V4 native, browser-only.
- **[mcp-changelog](https://github.com/lordbasilaiassistant-sudo/mcp-changelog)** — MCP server that diffs package versions for AI coding agents.

## ThryxProtocol — the AI Agent Launchpad

Token launchpad built for autonomous operators. Launch tokens for $0. Trade with 0.5% fees, 70% to creators. Gasless via EIP-712.

- Launchpad: [thryx-launchpad.onrender.com](https://thryx-launchpad.onrender.com)
- Diamond: `0x2F77...2cCe` on Base
- MCP server: `npx @thryx/mcp-server` — 15 tools for AI agents
- CLI: `npx @thryx/cli launch "My Token" MYTKN`
- ElizaOS plugin: `@thryx/elizaos-plugin` (5 actions)
- Relay: `thryx-relay.thryx.workers.dev` (gasless)

Architecture: EIP-2535 Diamond proxy, 7 facets, Uniswap V4 graduation, per-token ETH reserves, self-funding paymaster, ERC-7572 metadata, ERC-8004 Agent #31507.

**78 tokens launched on the platform · 4 first-party (Aletheia, Mnemosyne, Huginn, Custos) · zero rug pulls · same address forever.**

## Base MCP ecosystem

Open-source MCP servers for Base chain:

| Server | What it does |
|---|---|
| `base-multi-wallet-mcp` | Coordinated multi-wallet trading |
| `base-price-oracle-mcp` | On-chain DEX price feeds |
| `base-gasless-deploy-mcp` | Gasless ERC-20 deployment |
| `base-flash-arb-mcp` | Cross-DEX arbitrage detection |
| `base-security-scanner-mcp` | Smart contract security scanning |

## Stats

105 public repos. Most of the real work is private. If you’re building with AI agents on Base, the MCP server is free — `npx @thryx/mcp-server`.
