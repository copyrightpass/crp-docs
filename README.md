# CopyrightPass (CRP) Documentation

Official documentation, litepapers, contract addresses, and public records for CopyrightPass (CRP).

CopyrightPass (CRP) is a digital tool token designed for IP licensing, PLR/PPR rights verification, DAO governance, and Merkle Tree asset records on BNB Smart Chain.

CRP connects certified real-world intellectual property rights with on-chain verification, production-right records, and governance-controlled protocol infrastructure.

---

## What CRP Solves

Traditional IP licensing is often expensive, slow, opaque, and difficult for small businesses to use. Many licensing models depend on long authorization periods, minimum guarantees, manual contract review, and unclear production-right tracking.

CRP is designed to make IP licensing more accessible and verifiable by introducing:

- Production-quantity based IP licensing
- PLR / PPR rights verification
- Certified IP asset records
- Merkle Tree based asset verification
- DAO governance and timelock-controlled protocol operations
- City Pass ecosystem integration for real-world commercial use

CRP does not represent equity, profit distribution, revenue sharing, or royalty income rights.

---

## Litepaper

The official CRP Litepaper v3.0 is available through both the CopyrightPass website and this GitHub repository.

| Version | Website | GitHub |
|---|---|---|
| English v3.0 | https://copyrightpass.org/docs/CopyrightPass_CRP_Litepaper_v3.0_EN.pdf | [View / Download](./litepaper/CopyrightPass_CRP_Litepaper_v3.0_EN.pdf) |
| Chinese v3.0 | https://copyrightpass.org/docs/CopyrightPass_CRP_Litepaper_v3.0_CN.pdf | [View / Download](./litepaper/CopyrightPass_CRP_Litepaper_v3.0_CN.pdf) |

---

## Current PLR Asset Pool

CRP has introduced an initial certified PLR asset pool containing 20 IP licensing-production assets.

These assets are intended to demonstrate how CRP can connect certified IP rights, PLR production eligibility, and verifiable on-chain records.

Current asset pool focus:

| Item | Description |
|---|---|
| Asset Type | IP / PLR licensing-production assets |
| Initial Pool Size | 20 PLR assets |
| Verification Method | Certified records + Merkle Tree asset records |
| Use Case | IP licensing, production-right verification, and commercial ecosystem integration |
| Ecosystem Connection | CopyrightPass and City Pass |

For the latest PLR asset pool information, please refer to the official CopyrightPass website:

https://copyrightpass.org

---

## Core Protocol Architecture

CRP is built around a six-contract architecture on BNB Smart Chain.

| Layer | Contract | Purpose |
|---|---|---|
| Token Layer | CopyrightPass (CRP) | Core BEP-20 token used for protocol participation, licensing access, and ecosystem interaction |
| Voting Layer | VotingEscrow | Converts CRP locking into voting power for governance participation |
| Governance Layer | CRPGovernor | Handles governance proposals, voting, and protocol decision-making |
| Protocol Control Layer | ProtocolTimelock | Applies a 7-day delay to major protocol-level operations |
| Operational Control Layer | OperationalTimelock | Applies a 2-day delay to operational updates |
| Registry Layer | CRPEcosystemRegistry | Records ecosystem-level certification, PLR, and protocol registry data |

---

## Core Contracts on BNB Smart Chain

| Contract | Address | BscScan |
|---|---|---|
| CopyrightPass (CRP) | `0x2059b3cdb31abaeBc9E313246795b754F8A2784c` | [View](https://bscscan.com/address/0x2059b3cdb31abaeBc9E313246795b754F8A2784c) |
| VotingEscrow | `0xf34376DED6806afD98fc5CA164582459D0A62bF3` | [View](https://bscscan.com/address/0xf34376DED6806afD98fc5CA164582459D0A62bF3) |
| CRPGovernor | `0x7F115028C2E1f70cb4A8E84062e1803e8AfA080b` | [View](https://bscscan.com/address/0x7F115028C2E1f70cb4A8E84062e1803e8AfA080b) |
| ProtocolTimelock | `0x955262f7ED80708d09643195c2a4Cf45abdee3eC` | [View](https://bscscan.com/address/0x955262f7ED80708d09643195c2a4Cf45abdee3eC) |
| OperationalTimelock | `0xea9B9a25532481cd89236Ec5612282dA8d6E6305` | [View](https://bscscan.com/address/0xea9B9a25532481cd89236Ec5612282dA8d6E6305) |
| CRPEcosystemRegistry | `0x152E93dE6c1e02a726f11C672B641FDf4e3179C8` | [View](https://bscscan.com/address/0x152E93dE6c1e02a726f11C672B641FDf4e3179C8) |

## Contract Verification

The official CRP BscScan verification bundle is published in the CRP contracts repository:

https://github.com/copyrightpass/crp-contracts/releases/tag/bsc-mainnet-verification-v1.0.0

---

## Network Information

| Item | Value |
|---|---|
| Chain | BNB Smart Chain Mainnet |
| Chain ID | 56 |
| Token Standard | BEP-20 |
| Token Symbol | CRP |
| Token Name | CopyrightPass |

---

## Governance and Security Model

CRP is designed around governance-controlled protocol operation rather than single-wallet discretionary control.

Key governance and security components include:

| Component | Description |
|---|---|
| DAO Governance | Protocol decisions are handled through governance proposals and voting |
| VotingEscrow | CRP holders can lock CRP to participate in governance |
| ProtocolTimelock | Major protocol actions are delayed by 7 days |
| OperationalTimelock | Operational updates are delayed by 2 days |
| Merkle Tree Records | Asset records can be verified through Merkle-based records |
| Treasury Safe | Treasury management is handled through Safe multi-signature infrastructure |

---

## City Pass Ecosystem

City Pass is the commercial ecosystem connected to CRP.

It is designed to connect merchants, consumers, Business Miners, CRP Fragments, City Credits, and real-world commercial scenarios.

Official City Pass website:

https://citypass.hk

---

## Additional Documentation

| File | Description |
|---|---|
| [BNB Smart Chain Contract Addresses](./contracts/bsc-mainnet-addresses.md) | Official CRP mainnet contract address list |
| [Token Information](./token/token-info.md) | CRP token metadata and utility summary |
| [Litepaper Folder](./litepaper/) | English and Chinese CRP Litepaper v3.0 files |

---

## Official Links

| Channel | Link |
|---|---|
| Website | https://copyrightpass.org |
| City Pass | https://citypass.hk |
| GitHub | https://github.com/copyrightpass |
| Discord | https://discord.gg/ZXxm9CStAF |
| X | https://x.com/copyrightpass |
| Instagram | https://www.instagram.com/copyrightpass/ |
| LinkedIn | https://www.linkedin.com/company/copyrightpass |

---

## Contact

| Purpose | Email |
|---|---|
| Developer / audit contact | dev@copyrightpass.org |
| Support | support@copyrightpass.org |
| Legal | legal@copyrightpass.org |
| DAO governance | dao@copyrightpass.org |
| Business cooperation | business@copyrightpass.org |
