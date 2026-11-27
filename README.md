# Hi, I'm doctornanafushi 👋

Undergraduate engineering student  (Japan, 3rd year).
I build on blockchains — mostly **Solana**, plus some **EVM / Solidity** — and I like problems where math meets code: graph search, cryptography, mechanism design, and formal verification.

## 🏆 Hackathons

| Event | Project | Result |
|---|---|---|
| Colosseum **Crypto World's Fair** — Superteam Japan × enXross by Tokyo Dome side track (2026) | [OshiPool](https://github.com/doctornanafushi/oshipool) | **7th Prize** |
| XRPL Hackathon at Blockchain Kaigi 2026 (Tokyo) | — | Upcoming (Dec 2026) |

## 🛠 Projects

### [OshiPool](https://github.com/doctornanafushi/oshipool) — Sybil-resistant quadratic funding for live tipping (Solana)
Fans tip their favorite performers on Solana, and a matching pool is distributed with **quadratic funding**, so many small supporters count for more than one big wallet.
Since quadratic funding breaks if one person splits their money across many wallets, OshiPool adds an **ed25519 proof of attendance**: the venue signs each attendee's wallet address at the gate, and only tips carrying a valid venue signature are matched.
`TypeScript` `Solana` `ed25519` `Quadratic Funding`

### [HopGraph](https://github.com/doctornanafushi/hopgraph) — Minimum-fee cross-chain routing
Models chains and bridges as a graph and finds the cross-chain route with the lowest total fee.
`Graph search` `Cross-chain`

### [delay-certificate-NFT](https://github.com/doctornanafushi/delay-certificate-NFT) — Train delay certificates as NFTs (Solidity)
Issues a non-transferable NFT as an official certificate that a train was delayed.
Work in progress: formally verifying the contract — at both the Solidity and the **EVM bytecode** level — with Lean / Isabelle (no unauthorized mint, no double issuance, no transfer or burn, immutable data after issuance, etc.).
`Solidity` `ERC-721` `Formal verification`

## 📚 Interests

- Routing and graph algorithms for fragmented on-chain assets (spectral methods, graph Laplacians)
- Cryptographic primitives in practice (ed25519, signatures, Sybil resistance)
- Formal verification of smart contracts

## 🧰 Stack

`TypeScript` `Rust` `Solidity` `Python` `Solana` `EVM` `Linux` `LaTeX`
