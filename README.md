# Phoenix Program Integration (External Smart Contract)

## Overview

Scotty Pumpkin (SPUMP) integrates with **Phoenix Legacy**, an on-chain order book protocol built on Solana. Phoenix operates as a fully on-chain decentralized exchange (DEX) that enables atomic trade settlement without requiring an off-chain crank.

>  **Important:** Phoenix is **not developed or owned by this project**. It is an external Solana program developed by Ellipsis Labs that this token interacts with.

---

## About Phoenix

Phoenix Legacy is a Solana program (smart contract) that provides:

* Fully on-chain central limit order book (CLOB)
* Deterministic and atomic trade execution
* No crank or external keeper dependency
* High-performance trading primitives on Solana

This project uses Phoenix as part of its ecosystem for liquidity and/or trading functionality.

---

## Official Repository

The official Phoenix v1 source code is available here:

* https://github.com/Ellipsis-Labs/phoenix-v1

---

## Program Details

* **Program Name:** Phoenix Legacy
* **Program ID:** `PhoeNiXZ8ByJGLkxNfZRnkUfjvmuYqLR89jjFHGqdXY`
* **Network:** Solana Mainnet

---

## Build Verification

To verify that the deployed Phoenix program matches the official source code, use the Solana Verify CLI:

```bash
solana-verify verify-from-repo -um \
  --program-id PhoeNiXZ8ByJGLkxNfZRnkUfjvmuYqLR89jjFHGqdXY \
  https://github.com/Ellipsis-Labs/phoenix-v1
```

This process builds the program and checks that the resulting binary matches the on-chain deployment.

---

## Documentation

Official documentation and integration guides are available via Phoenix GitBook:

* Refer to the Phoenix documentation for instructions on interacting with the program

---

## Audits

Phoenix Legacy has undergone security auditing:

* Auditor: OtterSec
* Audit report available in the official repository (`audits/OtterSec.pdf`)

---

## License

Phoenix Legacy is licensed under the MIT License. See the official repository for details.

---

## Disclaimer

This repository does **not** include or claim ownership of the Phoenix program. All rights, code, and responsibilities belong to the original developers (Ellipsis Labs).

This project only interacts with the deployed Phoenix program for protocol-level functionality.

---
