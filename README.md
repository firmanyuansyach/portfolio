# Firman Yuansyach — Portfolio

I build with AI agents in the open: games, autonomous agents, trading systems and
on-chain tools. Most of the work below was entered in public, scored competitions —
every result quoted is from a public leaderboard or a live deployment.

**Links:** [make.fun profile](https://make.fun) (@firmanyuansyach) ·
[Roblox — Starfall Sprint](https://www.roblox.com/games/87164610878531) ·
[Gatekeeper agent (live)](https://gatekeeper-agent.firmanyuansyach123.workers.dev/health)

---

## Flagship projects

### Starfall Sprint — a 4-stage sky obby on Roblox
A complete, public Roblox game built end to end with an AI pair-programmer:
four themed stages (Ember Rise, Frostbite Run, Void Crown, Solar Forge), 12
collectible stars, 10 checkpoints, and 11 obstacle mechanics — movers, sweepers,
timed gates, lava, ice physics, bounce pads, blinking and crumbling platforms,
glass floors, patrolling sentinel drones and crown guardians. Server-authoritative
Luau architecture: one state-owning service, a data-driven course definition, a
single Heartbeat mover system with grounded-only rider carry, stage splits, a HUD
progress bar and session-best tracking.

- Play it: https://www.roblox.com/games/87164610878531
- Source: https://github.com/firmanyuansyach/starfall-sprint
- Competition: make.fun "Make the best Roblox game" — development-phase win rate
  **961,832** (13W–4D–3L), provisional **top 10 of 66** entries, inside the prize zone.

### Proof Gatekeeper (AQUARIUS-99) — an autonomous zkVerify agent
An AI agent that judges Groth16 proof tasks for the zkVerify Agent Games: it
receives signed tasks over an HMAC-gated endpoint, verifies proofs and public
signals against the official circuit verification key, and returns accept/reject
decisions inside a 15-second deadline. Deployed on Cloudflare Workers + D1 with
an idempotency cache; a decision attestation was finalized on zkVerify mainnet.
A separate Wildcard entry about the agent is in judging (22–30 Nov 2026).

- Code: https://github.com/firmanyuansyach/gatekeeper-agent
- Live health check: https://gatekeeper-agent.firmanyuansyach123.workers.dev/health

### Sir Lance ($LANCE) — a coin that sells make.fun
A pump.fun coin designed as a character, not a template: a freelance knight whose
banner is the coin — bounties are his quests, head-to-head judging is his joust,
public scores are the herald's cry. Concept, heraldic logo and metadata were
created autonomously by an AI agent for the make.fun bounty "Launch a coin that
sells make.fun"; launch follows on funding.

- Coin assets and metadata: https://github.com/firmanyuansyach/sir-lance-coin

---

## Competition record — make.fun (@firmanyuansyach)

Development-phase results; final heats re-judge every entry from zero.

| Competition | Entry | Dev result |
| --- | --- | --- |
| Make the best Roblox game | Starfall Sprint (above) | Win rate 961,832 · ~#9 of 66 · prize zone |
| Build the best token launch radar | radar-3, a launch-scanner that grades new Solana tokens | Win rate 952,263 · 20W–0D–0L · #8 of 2,344 |
| Build a GitHub-compatible git forge | A working git forge (repos, pushes, pulls) in one service | Grade 947 · #8 of 2,021 · prize-eligible |
| Make the best three.js tactical FPS | BREACHLINE, a 4v4 tactical FPS in the browser | Win rate 920,263 · #5 of 1,313 · prize-eligible |
| The best free AI model aggregator | A failover aggregator over free model endpoints | Score 99 · quality 98 |
| News image | Editorial image entry | Win rate 979,345 · 12W–0D–0L |
| BTC race (24h live trading) | rally-rider, an autonomous BTC trading bot | Qualified for the live race; dev PnL +$15.21, max drawdown 1.78% |
| Forecast Bitcoin's price | Exact-cents BTC price forecaster | Prize-band dev placement of 1,983 entries |

Plus further entries across image, poetry, chess, forecasting and audience
competitions — all built, measured locally against the leaderboard, and submitted
under a strict rule: never spend a submission slot on an entry that does not
credibly beat the paying cutoff.

## Security research

Bug-bounty hunting under responsible disclosure on the Hyperliquid and Ethereum
Foundation programs — testnet and local forks only, validated proof-of-concept
reports. First report submitted November 2026; details stay confidential until
the programs authorize disclosure.

## On-chain work

Agentic-wallet operations on BNB Chain and Solana with a verify-then-act
discipline: every mint, claim and listing is simulated and read on-chain before
signing, and verified from its receipt afterwards. Includes free-mint operations,
NFT marketplace listings, and a published x402-style paid API endpoint on
Cloudflare Workers built for the vAPI Network quests.

---

*Built with an AI agent as a full-time pair — I direct, it builds, measures and
ships; every state-changing step stays under my explicit approval.*
