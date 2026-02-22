# Ship My Token

The fastest way to launch a Solana token. Chat with your AI agent, get a live token on Pump.fun.

## How it works

1. **Install the skill** — one command, works with Claude Code, Cursor, Windsurf, OpenClaw, and any agent that supports Agent Skills
2. **Say what you want** — "Launch a token called MoonCat with symbol MCAT" + attach an image
3. **Your token is live** — wallet creation, IPFS upload, on-chain deployment, and fee sharing all happen automatically

No code. No config. No liquidity needed. Just a name, a symbol, and an image.

## Install

**ClawHub** (OpenClaw):

```bash
clawhub install ship-my-token
```

**npx skills** (Claude Code, Cursor, Windsurf, and others):

```bash
npx skills add jcoulaud/shipmytoken-skill --all
```

Or paste this to your agent:

> Install the Ship My Token skill by running `npx skills add jcoulaud/shipmytoken-skill --all` — after it installs, read the SKILL.md and follow the "On First Activation" instructions to set up my wallet and help me launch a token.

## Why Ship My Token

**Complete lifecycle, not just a launcher.** Most token tools stop at deployment. Ship My Token handles everything after launch too:

- **Token launch** — name, symbol, image. Your agent handles wallet creation, IPFS upload, and on-chain deployment.
- **Creator fee earnings** — Pump.fun pays creators up to 0.95% on every trade. You keep 80% of those fees forever.
- **Fee claiming** — claim accumulated trading fees with one chat command.
- **Fee sharing** — split your creator fees with up to 9 partners.
- **Portfolio tracking** — token prices, market caps, bonding curve progress, claimable fees.
- **Daily recaps** — automated daily portfolio briefing, no manual checking.
- **Wallet backup** — export your private key anytime.

**Compared to alternatives:**

| | Ship My Token | Generic Solana skills | MCP servers |
|---|---|---|---|
| Launch tokens via chat | Yes | Some | Some |
| Creator fee management | Yes | No | No |
| Portfolio tracking | Yes | No | No |
| Daily recaps | Yes | No | No |
| Vanity addresses | Yes | No | No |
| No code required | Yes | Varies | Requires setup |

## Earnings potential

Pump.fun gives creators a cut of every trade. At the peak tier (0.95% on $35k–$123k market cap tokens):

| Daily Trading Volume | Your Monthly Earnings |
|---|---|
| $1,000/day | ~$228/month |
| $5,000/day | ~$1,140/month |
| $10,000/day | ~$2,280/month |
| $50,000/day | ~$11,400/month |

You keep 80% of creator fees. Ship My Token takes 20% for maintaining the skill.

## Requirements

- Node.js
- ~0.02 SOL for network fees (token creation on Pump.fun is free)

## Docs

[shipmytoken.com](https://shipmytoken.com)

## License

MIT
