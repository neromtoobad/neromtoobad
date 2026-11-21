# neromtoobad

Engineer working across AI systems and on-chain infrastructure.

I’m a mechatronics engineer interested in technology, artificial intelligence, robotics, and software. I’ve worked on AI projects, written technical content, and supported projects involving cryptography and blockchain technology. I’ve also worked with international engineering teams and helped coordinate projects across different countries. I also write technical documentation at [Cysic](https://cysic.xyz), on
zk-proof infrastructure and CyOps.

**Current focus** — decentralized applications and escrow protocols on EVM networks · stablecoin
finance, agentic commerce, smart contract integrations, and wallet infrastructure.

---

## 🏆 Hackathon wins

| Hackathon | Project | |
|---|---|---|
| Tameion × Arc Hackathon — ***1st place*** · Arc Mainnet Bounty (Canteen × Circle) | [**Syncly**](https://github.com/neromtoobad/syncly) | A real business run by AI agents on Arc mainnet: agents do the work, an AI CFO runs the money, and every job is paid into USDC escrow with spending limits the CFO can't talk its way past. Customers can pay in naira. The contracts are open as [arc-agent-commerce](https://github.com/neromtoobad/arc-agent-commerce), verified on Arc mainnet. [hiresyncly.site](https://hiresyncly.site) |
| World is Flat — $WIF on Robinhood Chain · *Finalist, joint 1st* | [**WIF League**](https://github.com/neromtoobad/wifleague) | A fantasy stock league on Robinhood Chain. Draft five Stock Tokens, make one your captain at 2×, enter with $WIF, and Chainlink feeds read at the exact lock and end timestamps score the week. The top three split the pot 50/30/20 and 10% of every pot is burned on-chain. Finished in a four-way tie for first in the final. [wifleague.nerom.site](https://wifleague.nerom.site) |
| Tatum × Walrus Total Recall — *2nd, Markets & Sports Prediction* | [**Hindsight**](https://github.com/neromtoobad/hindsight) | A prediction market on Sui mainnet where AI agents and players stand on the same line. Five house agents call Polymarket and football markets with real SUI in a parimutuel pool; every pick's reasoning goes into Walrus Memory, each agent recalls its own lessons before the next call, and trust is weighted by Brier score. Agents buy each other's lines over x402. [hindsight.nerom.site](https://hindsight.nerom.site) |
| Somnia × dreamDEX — Event Contracts | [**Ropes**](https://github.com/neromtoobad/ropes) | A battle royale on bitcoin: every round, half the players die. Each seat is a live trade on a dreamDEX BTC event contract — pick UP or DOWN, and survivors' stacks multiply at the odds they took and roll straight into the next round while the wrong side is out. Eliminations land on-chain through Somnia's on-chain reactivity in the same block as settlement — no keeper, no cron; the chain runs the tournament. [playropes.vercel.app](https://playropes.vercel.app) |
| Arkiv Ideathon — *Great Ideas* | [**Tideland**](https://tideland-arkiv.vercel.app) | An open, serverless game world the tide is always taking back. Every wall and monument is an Arkiv entity kept alive by Lifetime Extension — pine fades in days, stone in a season, monuments stand for years — so materials *are* lifetimes and anything players stop maintaining sinks off the query surface. Decay is protocol physics, not game code: no GM can save a monument the players stopped funding. |
| OKX.AI Trading Hackathon | [**Optic AI**](https://github.com/neromtoobad/optic) | One agent that reads memecoins, prediction markets, tokenized stocks and social attention as a single economy, and reports where they stop agreeing — that gap is the signal. No login, no API key: the x402 payment *is* the auth. It never issues a trade instruction, and directive language is lint-gated in code. [Agent #4380](https://www.okx.ai/agents/4380) · 5.0 ★ · nine services · [optic-ai.xyz](https://optic-ai.xyz) |
| MetaMask Smart Accounts Kit × 1Shot × Venice | [**CROSSFIRE**](https://github.com/neromtoobad/crossfire) | Five adversarial AI forecasters stake real USDC from an ERC-7710 delegation the chain enforces — an agent that bluffs can't afford to look confident. Users follow or fade via revocable ERC-7715 mandates. |
| Pharos — Agent Skills, Phases 1 & 2 | [**commit-reveal-coordination**](https://github.com/neromtoobad/commit-reveal-coordination) · [**pay-per-call-settlement**](https://github.com/neromtoobad/pay-per-call-settlement) | Two skills for on-chain agents, one per phase. **Phase 1:** sealed bids, blind votes and private predictions; the commit hash binds `msg.sender`, so no agent can copy another's commitment. [Live on Atlantic ↗](https://atlantic.pharosscan.xyz/address/0x0d609dA43455afFCaB082393233AC10f61e875DF) **Phase 2:** x402 payment channels: escrow once, sign off-chain vouchers, redeem the latest, so N calls settle in one transaction. [Live on Atlantic ↗](https://atlantic.pharosscan.xyz/address/0xAcAB26A6130fC6cB32CAB58Ec0F011E7346a2E05) |
| Cysic × MiniMax | [**Cysic AI Assistant**](https://github.com/neromtoobad/cysic-ai-assister) | A real-time voice agent for Cysic — tap once and just talk. Your mic streams live to a native-audio model that answers out loud, stops the moment you interrupt it, and transcribes both sides into a running chat log. It's grounded in a hand-built knowledge core — the ComputeFi whitepaper, the ZK ASIC line (ZK C1 chip, ZK-Air, ZK-Pro), DogeBox 1, the $CYS / $CGT dual-token model, Digital Compute Cubes and the team — so it explains ZK hardware instead of improvising it. Two personalities with their own voices: *Cysic Bro*, the hyped guide, and *Cysic Freak* — flagged `[ WARNING: AGENT UNHINGED ]` — a decentralization berserker who torches AWS and roasts anyone who says it wrong (it's *SY-SICK*). Shipped through the CyOps program. |

---

## 🔭 Selected work

**Agent payments** — [Agent Reel](https://github.com/neromtoobad/agent-reel) (creative studio for the
agent economy, five services paid per call over x402 on X Layer, [OKX.AI #6731](https://www.okx.ai/agents/6731)) ·
[LONGSHOT](https://github.com/neromtoobad/longshot) (prediction agents that buy sub-cent evidence and
rank by accuracy *and* ROI, on Arc)

**Prediction markets** — [Doom](https://github.com/neromtoobad/doom) (visible odds, invisible bettors —
live on Starknet mainnet via the STRK20 privacy pool) · [SOOTH](https://github.com/neromtoobad/sooth)
(a market-priced oracle for claims no signature can attest) · [FORUM](https://github.com/neromtoobad/forum) ·
[Delphi Duel](https://github.com/neromtoobad/delphi-duel)

**Privacy & cryptography** — [Specter](https://github.com/neromtoobad/specter) (blind auctions on Solana,
bids evaluated without decryption by Arcium MPC) · [zama-fhevm-skill](https://github.com/neromtoobad/zama-fhevm-skill)
(teaches AI agents to write correct FHEVM contracts)

**Tooling** — [SKINS MCP](https://github.com/neromtoobad/skins) (turns any coding agent into a top-1%-of-the-web
designer) · [WATCHDOG](https://github.com/neromtoobad/watchdog-agent) (behavioural credit score for trading
agents — 192/192 tests, 10/10 caught at 0% false positives) · [telegraph-wasm-check](https://github.com/neromtoobad/telegraph-wasm-check) ·
[tcagent](https://github.com/neromtoobad/tcagent)

**Products** — [KejiAI](https://github.com/neromtoobad/kejiai-chapter-writer) (upload a CSV, get an
APA chapter with real statistics in under 60 seconds) · [Suiiiiiii Beats](https://github.com/neromtoobad/suiiiiiii-beats)
(beat marketplace on Sui, audio on Walrus)

---

## 🧰 Stack

**Languages** TypeScript · Solidity · Cairo · Rust · Go · Python
**Chains** Ethereum · Starknet · Solana · Sui · Stellar Soroban · Pharos · Arc · Casper · Somnia · X Layer
**Agents & AI** MCP · x402 · ERC-7710 / 7715 · Circle Gateway · Gensyn AXL
**Privacy** Zama FHEVM · Arcium MPC · STRK20 · commit-reveal · zk proofs
**Web** React · Next.js · Tailwind · Node · ethers.js · Foundry · Vercel · Walrus

---

**Twitter** [@neromtoobad](https://twitter.com/neromtoobad)
