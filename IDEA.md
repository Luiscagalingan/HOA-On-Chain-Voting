# On-Chain Voting for HOAs

## Idea
- **Track:** Financial Inclusion / Social Impact
- **Idea #:** Custom
- **One-liner:** Secure, transparent, and token-weighted voting for Homeowners' Associations.

## Problem
HOA elections in subdivisions are frequently contested and lack transparency. Manual counting is slow, prone to errors, and often results in disputes among residents. Trust in local governance is low when the process isn't auditable.

## How it uses Stellar
- **Stellar Classic Assets:** Represent "House Tokens" or voting power. Each household is issued tokens (e.g., 1 token per unit) to ensure weighted voting.
- **Soroban Smart Contracts:** A voting contract handles the poll creation, vote tallying, and ensures that each token can only be used once per poll (or uses current balance at a snapshot).
- **Transparency:** All votes are recorded on the Stellar ledger, making them publicly auditable and immutable.

## What works in the demo
- [ ] Connect wallet (Freighter, testnet)
- [ ] Create a new poll (Soroban)
- [ ] Cast a token-weighted vote
- [ ] View real-time tallying results

## Setup / run
How a judge runs it locally:
- Network: **testnet**
- `cd web && npm install && npm run dev`
- Contract: `.\scripts\deploy.ps1`, then set `NEXT_PUBLIC_CONTRACT_ID` in `web/.env.local`

## Demo
- 2–4 min video link (show the core flow working on testnet):
- Public repo link:

## Submission checklist
- [ ] Public GitHub repo with a license (this scaffold ships MIT)
- [ ] README explains problem, Stellar usage, and setup
- [ ] Demo video (2–4 min)
- [ ] Submitted via the workshop's official GitHub issue template
