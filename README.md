# William Edward Bodell III

**Software Engineer | Financial Systems, AI Integrations & Smart Contracts**

[LinkedIn](https://www.linkedin.com/in/webthethird/) · [USENIX Security '23 Publication](https://www.usenix.org/conference/usenixsecurity23/presentation/bodell)

I'm a software engineer with 5+ years of experience building financial applications, trading infrastructure, and blockchain protocols. My work spans full-stack product development, backend systems, smart contracts, and AI-agent integrations, including production experience at Wasabi Protocol and Increment Finance.

I also have a background in academic security research, with a first-author publication at USENIX Security 2023.

I'm particularly interested in building financial products that combine intuitive user experiences with sophisticated underlying systems, and in exploring how AI and programmable incentives can make those products more useful.

## Selected Work

### Financial Products & Trading Infrastructure

**Wasabot — Dkoda Labs** — Designed and built an integration with Virtuals' Agent Commerce Protocol, connecting AI agents to Wasabi's perpetuals trading infrastructure. Owned the Node.js services, smart contract architecture, and user-facing integration, taking the product from implementation through launch and iteration. The integration processed over **$80M in trading volume**.

**Wasabi Protocol — Dkoda Labs** — Developed and upgraded core smart contracts for a perpetuals trading protocol, including a migration involving hundreds of millions of dollars in vaulted assets. Also built backend infrastructure and product features spanning Solidity, Java/Spring Boot, MySQL, REST APIs, and React.

**Prop AMM — Dkoda Labs** — Led the smart contract implementation of an oracle-based proprietary automated market maker, incorporating size-dependent pricing, inventory skew, spreads, and volatility parameters. The AMM processed over **$100M in trading volume**.

**[Increment Finance — Peripheral Contracts](https://github.com/Increment-Finance/peripheral-contracts)** — Designed and implemented Solidity contracts for liquidity incentives, staking, slashing, protocol safety mechanisms, and auctions, with Foundry unit tests and invariant fuzzing. Translated mathematical reward-emission and distribution models into onchain accounting logic.

**Selected verified Wasabi contract implementations (Ethereum mainnet):**

- [WasabiLongPool](https://etherscan.io/address/0x8e19c040b4c1c8d2a63e6cb375f01ab65d2ddc04#code#F45#L1) — Long-position pool, including position accounting, interest, and liquidation logic.
- [WasabiShortPool](https://etherscan.io/address/0x61d0df7c0978d04071c6f1e94beba96e075ebe12#code#F45#L1) — Short-position pool, including position accounting, interest, and liquidation logic.
- [WasabiRouter](https://etherscan.io/address/0x0b38cbcc2a215c636d0c3890e64e2a21255f437e#code#F41#L1) — Signed orders, vault-funded trades, and token swaps.
- [PerpManager](https://etherscan.io/address/0xba5c5828f2fb77237b940187ec785ee4498d2683#code#F27#L1) — Access control, risk parameters, and vault upgrades.
- [WasabiVault](https://etherscan.io/address/0xf7855f37ee116a0736e3baa68ddc205467ae8153#code#F41#L1) — ERC-4626 lending vault with pool borrowing, yield strategies, and interest accounting.

*The original Wasabi development repository and commit history are private, but deployed contract implementations are publicly verified on Etherscan. I also used [@WEBthe3rd](https://github.com/WEBthe3rd) for professional development.*

### Independent Projects

**Takes / Serious Social — AI-Powered Social Finance & Mechanism Design**

Two iterations of an independent research and product project exploring how financial commitments can make online opinions more meaningful.

- **[Serious Social](https://github.com/Serious-Social/serious-social)** — Built and deployed a Farcaster mini app and Solidity contracts on Base mainnet, enabling users to stake USDC behind social-media opinions. Implemented time-weighted conviction, fee-funded rewards, and onchain staking without requiring objective resolution.

- **[Takes](https://github.com/webthethird/takes-classifier)** — Developed an LLM-based opinion-classification and semantic-clustering pipeline, Solidity opinion-market contracts, and a Next.js mini app. Currently experimenting with an automatically curated feed that identifies subjective, challengeable opinions from real social-media conversations.

**Technical focus:** TypeScript, React/Next.js, LLM classification, semantic embeddings, Solidity, Foundry, ERC-4626, and financial mechanism design.

[Serious Social Contracts](https://github.com/Serious-Social/serious-contracts) · [Takes Classifier](https://github.com/webthethird/takes-classifier) · [Takes Contracts](https://github.com/webthethird/takes-contracts) · [Takes Mini App](https://github.com/webthethird/takes-miniapp)

**[Habitat](https://github.com/webthethird/Habitat)** — An ETHGlobal Waterloo 2023 hackathon project rewarding regenerative activities through onchain attestations and NFT trees. Led a three-person team building a Next.js frontend and Solidity contracts using ERC-6551 token-bound accounts, Ethereum Attestation Service, and World ID.

**[FarmShare (2023)](https://github.com/FarmshareCSA/Farmshare)** — A modern prototype of my original community-supported agriculture concept, built for ETH Toronto 2023. Uses account abstraction, Safe multisigs, EAS attestations, and token incentives to coordinate contributions to local farms.

### Security Research & Tooling

**[Diffusc](https://github.com/crytic/diffusc)** — A differential fuzzing tool for upgradeable smart contracts, developed from my graduate research and subsequent work at Trail of Bits. Uses static analysis to generate Solidity test harnesses for fuzzing unintended behavioral changes between contract implementations. I also contributed to [Slither](https://github.com/crytic/slither), including upgradeability and static-analysis improvements.

My research on upgradeable smart contract security was published at **USENIX Security 2023**, where I was the first author.

## Background & Interests

My path into software engineering began in architecture. After discovering Ethereum in 2015, I started [FarmShare](https://github.com/webthethird/FarmShare), an early exploration of using blockchain technology to support local agriculture.

I later earned a Master of Computer Science from Illinois Institute of Technology, where I began researching smart contract security.

That multidisciplinary background continues to shape my interest in using programmable incentives and emerging technologies to solve problems beyond traditional finance.

**Current interests:** AI-enabled financial products, DeFi protocol architecture, smart contract security, full-stack and backend engineering, distributed systems, and cryptoeconomic mechanism design.
