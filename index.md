## VERT Litepaper

### 1. Overview

VERT is a decentralized NFT minting protocol built on the Base network. Users mint unique "Vertical" NFTs with a chance to win VERT tokens instantly based on rarity. Each NFT is AI-generated in real-time and stored on IPFS, with provable rarity determined on-chain.

> **Tagline:** Mint a Vertical. Win VERT.

### 2. How It Works

#### Minting Process

* Users can mint NFTs by paying:

  * **0.5 VIRTUAL** (ecosystem token)
  * **500 VERT** (project token)
* Payment method is selected via button or terminal-style input (type 1 or 2).

#### Rarity System

Each mint has a rarity outcome:

* Common — 70%
* Rare — 20%
* Epic — 7%
* Legendary — 2.5%
* Mythical — 0.5%

#### Prize Pool Mechanics

* 75% of VERT payments go to the **prize pool**
* 25% go to the **treasury** (which is staked indefinitely)
* Prize pool automatically pays out based on rarity odds

#### Instant Payouts

Winners receive VERT tokens automatically based on rarity tier:

* Rare: 3% of prize pool
* Epic: 7%
* Legendary: 15%
* Mythical: 40%

> No claiming needed. Rewards appear in your wallet instantly.

#### Staking Boosts

Staking VERT improves your odds of pulling rarer NFTs:

* Bronze: 10k+ VERT — +15% boost
* Silver: 50k+ VERT — +25% boost
* Gold: 100k+ VERT — +40% boost

### 3. Frontend Overview

The VERT site is a terminal-style interface with 7 main modules:

1. **Prize Pool Terminal** — Displays live prize pool in VERT
2. **VERT Stats Terminal** — Shows total minted, total staked, and VERT paid out
3. **Mint Button Terminal** — Wallet-connected mint interface, supports 1-key typing
4. **Mint Feed Terminal** — Reveals your NFT and prize result in real time
5. **Staking Odds Terminal** — Shows rarity odds based on staking tier
6. **Tier Status Terminal** — Displays your active staking tier
7. **Leaderboard Terminal** — Displays top 10 minters + your own rank if outside top 10

### 4. Tokenomics

**Total Supply:** 1,000,000,000 VERT

#### Distribution:

| Category                           | %     |
| ---------------------------------- | ----- |
| Public Sale                        | 37.5% |
| Liquidity Pool (LP)                | 12.5% |
| Prize Pool Reserve (vested)        | 10.0% |
| Prize Pool Injection — Round 1     | 5.0%  |
| Prize Pool Injection — Round 2     | 4.0%  |
| Prize Pool Injection — Round 3     | 3.0%  |
| Prize Pool Injection — Round 4     | 2.0%  |
| Strategic Project Fund             | 5.0%  |
| Team / Development                 | 5.0%  |
| Marketing / Strategic Partnerships | 2.0%  |
| Project Operational Costs          | 2.0%  |
| VERT Stakers                       | 2.0%  |
| Vader Stakers                      | 2.0%  |
| Virtual Stakers                    | 2.0%  |
| Leaderboard Rewards — Round 1      | 1.0%  |
| Leaderboard Rewards — Round 2      | 0.33% |
| Leaderboard Rewards — Round 3      | 0.33% |
| Leaderboard Rewards — Round 4      | 0.33% |

> Leaderboard resets monthly. Top minters earn proportionate rewards from allocation.

### 5. Technology

* **Network:** Base
* **NFT Metadata:** On-chain with IPFS image storage via Pinata
* **Image Generation:** Real-time via Replicate + DreamShaper XL Turbo
* **Smart Contracts:** Solidity — handles rarity, payouts, staking boosts, admin controls
* **Frontend:** Tailwind + RainbowKit + Framer Motion — custom terminal UI

### 6. Marketplace Integration

All minted NFTs are:

* Viewable and tradable on OpenSea and other marketplaces
* Include rarity metadata
* Treasury receives a **5% royalty** on all secondary sales

### 7. Roadmap

**Phase 1:** Launch

* Minting, prize payouts, staking tiers, rarity odds
* Live dashboard with terminals and stat feed

**Phase 2:** Ecosystem Expansion

* Prize pool reserve injections (vested)
* Strategic mint events and partner campaigns

**Phase 3:** Community & Governance

* Expanded leaderboard incentives
* Airdrops to stakers and community holders
* Governance discussion (non-binding via Snapshot)

### 8. Get Started

1. Connect wallet
2. Approve VERT or VIRTUAL token
3. Click Mint or type 1/2
4. Wait for generation (60–100 sec on first mint)
5. See your NFT + reward in your wallet

> Follow us on X: \[@VerticalOnBase]
> Website: vertnft.com
> Contract links, Opensea, and more: added post-launch
