# ⚒ Token Forge

> Deploy OP-20 tokens on Bitcoin Layer 1. Instantly launch a faucet. No code required.

Built for the [vibecode.finance](https://vibecode.finance) Week 1 challenge — **Bitcoin Activated**.

## 🔗 Live Demo
Deploy to Vercel and your link goes here.

## ✨ Features

- **Token Deployer** — Deploy OP-20 tokens to Bitcoin L1 via OP_NET with a clean form UI
- **Faucet Creator** — Optionally launch a faucet contract alongside your token (set claim amount, cooldown, reserve)
- **Shareable Faucet Links** — Auto-generates `?faucet=<address>` URLs to share with your community
- **Faucet Claim UI** — Anyone can claim tokens from a faucet by pasting the contract address
- **My Tokens Dashboard** — See all tokens you've deployed, with links to OPScan

## 🏗 Tech Stack

- Plain HTML / CSS / JavaScript (no build step, zero dependencies)
- OP_NET / OP_WALLET browser extension integration
- Deploys instantly to Vercel

## 🚀 Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project → Import your repo
3. Framework preset: **Other** (static site)
4. Click Deploy — done!

## 🔌 OP_NET Integration

Wallet connection supports:
- **OP_WALLET** (recommended) — [Install from Chrome Web Store](https://chromewebstore.google.com/detail/opwallet/pmbjpcmaaladnfpacpmhmnfmpklgbdjb)
- **UniSat**
- **Xverse** (coming soon)

For full on-chain deployment, install OP_WALLET and connect to Bitcoin Mainnet. Without a wallet extension, the app runs in demo mode showing the full UI flow.

## 📁 Structure

```
token-forge/
└── index.html    # Everything — single file app
```

## 🔗 Ecosystem

- [OP_NET](https://opnet.org)
- [OPScan](https://opscan.org)
- [Docs](https://docs.opnet.org)
- [vibecode.finance](https://vibecode.finance)

---

Built on Bitcoin L1 · Powered by OP_NET · #opnetvibecode
