# William Edward Bodell III

**Smart Contract Engineer | Protocol Design | Security Research**

[LinkedIn](https://www.linkedin.com/in/webthethird/) · [USENIX Security '23 Publication](https://www.usenix.org/conference/usenixsecurity23/presentation/bodell)

I'm a software engineer specializing in Ethereum smart contracts, DeFi protocols, and security-sensitive systems. My experience spans production Solidity development, backend engineering, and academic security research, including a first-author publication at USENIX Security 2023.

I'm particularly interested in the intersection of **protocol architecture, security, and mechanism design** — building systems that are not only technically sound, but also have well-designed economic incentives.

## Selected Work

### Security Research & Tooling

**[Diffusc](https://github.com/crytic/diffusc)** — A differential fuzzing tool for upgradeable smart contracts, developed from my graduate research and subsequent work at Trail of Bits. It uses static analysis to generate fuzzing tests that identify unintended behavioral changes between contract implementations. I also contributed to [Slither](https://github.com/crytic/slither).

My research on upgradeable smart contract security was published at **USENIX Security 2023**.

### Production DeFi Engineering

**[Increment Finance — Peripheral Contracts](https://github.com/Increment-Finance/peripheral-contracts)** — Designed and implemented Solidity contracts for liquidity incentives, staking, slashing, protocol safety mechanisms, and auctions, with Foundry unit tests and invariant fuzzing.

**Wasabi Protocol (Dkoda Labs)** — Developed and upgraded core smart contracts for a perpetuals trading protocol, including a migration involving hundreds of millions of dollars in vaulted assets. Also built backend infrastructure and integrations spanning Solidity, Java/Spring Boot, MySQL, and React.

**Selected verified contract implementations (Ethereum mainnet):**

- [WasabiLongPool](https://etherscan.io/address/0x8e19c040b4c1c8d2a63e6cb375f01ab65d2ddc04#code#F45#L1) — Long-position pool, including position accounting, interest, and liquidation logic.
- [WasabiShortPool](https://etherscan.io/address/0x61d0df7c0978d04071c6f1e94beba96e075ebe12#code#F45#L1) — Short-position pool, including position accounting, interest, and liquidation logic.
- [WasabiRouter](https://etherscan.io/address/0x0b38cbcc2a215c636d0c3890e64e2a21255f437e#code#F41#L1) — Signed orders, vault-funded trades, and token swaps.
- [PerpManager](https://etherscan.io/address/0xba5c5828f2fb77237b940187ec785ee4498d2683#code#F27#L1) — Access control, risk parameters, and vault upgrades.
- [USDC WasabiVault](https://etherscan.io/address/0xf7855f37ee116a0736e3baa68ddc205467ae8153#code#F41#L1) — ERC-4626 lending vault with pool borrowing, yield strategies, and interest accounting.

Built **Wasabot**, an integration with Virtuals' Agent Commerce Protocol that processed over $80M in trading volume.

*The original Wasabi development repository and commit history are private, but deployed contract implementations are publicly verified on Etherscan. I also used [@WEBthe3rd](https://github.com/WEBthe3rd) for professional development.*


### Independent Projects

**[Takes](https://github.com/webthethird/takes-contracts)** — An experimental on-chain opinion market exploring economic incentives for expressing and challenging subjective beliefs. The project spans three repositories:

- [takes-contracts](https://github.com/webthethird/takes-contracts) — Solidity markets, time-weighted staking, ERC-4626 yield accounting, and invariant tests
- [takes-classifier](https://github.com/webthethird/takes-classifier) — LLM classification and semantic clustering of opinions
- [takes-miniapp](https://github.com/webthethird/takes-miniapp) — Next.js/Farcaster application integrating the classification pipeline with on-chain markets

**[Serious Social](https://github.com/Serious-Social/serious-social)** — The intellectual predecessor to Takes, exploring how economic incentives can encourage more thoughtful online discourse. Built around *Belief Markets*, where users stake USDC to support or challenge opinions on Farcaster, signaling conviction without requiring objective resolution. The system uses time-weighted staking and fee-funded rewards rather than winner-take-all settlement. Deployed on Base mainnet.

- [serious-social](https://github.com/Serious-Social/serious-social) — Next.js/Farcaster mini app with cast-linked markets, personalized feeds, and on-chain staking
- [serious-contracts](https://github.com/Serious-Social/serious-contracts) — Solidity belief markets, USDC custody, time-weighted conviction, and constant-time reward accounting

*The broader research question behind both Takes and Serious Social is how economic mechanisms might improve online discourse without relying on traditional prediction-market resolution.*

**[Habitat](https://github.com/webthethird/Habitat)** — An ETHGlobal Waterloo 2023 hackathon project rewarding regenerative activities through on-chain attestations and NFT trees. Built with ERC-6551 token-bound accounts, Ethereum Attestation Service, World ID, and Solidity.

**[FarmShare (2023)](https://github.com/FarmshareCSA/Farmshare)** — A modern prototype of my original community-supported agriculture concept, built for ETH Toronto 2023. Uses account abstraction, Safe multisigs, EAS attestations, and token incentives to coordinate contributions to local farms.

## Background & Interests

My path into software engineering began in architecture. After discovering Ethereum in 2015, I started [FarmShare](https://github.com/webthethird/FarmShare), an early exploration of using blockchain technology to support local agriculture.

I later earned a Master of Computer Science from Illinois Institute of Technology, where I began researching smart contract security.

That multidisciplinary background continues to shape my interest in using programmable incentives to solve problems beyond traditional finance.

**Current interests:** DeFi protocol architecture, smart contract security, distributed systems, backend engineering, and cryptoeconomic mechanism design.
