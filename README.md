# Samuel Osho — Maxx

**Solana protocol engineer.** Privacy infrastructure, real-time systems, technical writing.
I ship on-chain products and write about the stack underneath them.

Lagos, Nigeria · WAT (UTC+1) · remote worldwide · **[open to protocol engineering and developer-education roles](mailto:oshosamuel86@gmail.com)**

[Email](mailto:oshosamuel86@gmail.com) · [LinkedIn](https://linkedin.com/in/samuel-o-3809b42a9) · [Medium](https://medium.com/@fwmaxx) · [X](https://x.com/maxvrtx)

---

## What I'm building

Four things, all shipped, all readable. Where a project is devnet or testnet, it says so.

| Project | What it does | Stage | Stack |
|---|---|---|---|
| **[Vanta](https://github.com/maxxexee/vanta-mobile)** | Android wallet where payments move through a Zolana shielded pool, so amount and recipient aren't derivable from chain data. Four payment modes, biometric gate, encrypted backup (scrypt + XChaCha20-Poly1305). | devnet, signed APK | Kotlin, React, Solana Mobile |
| **[PulseLock](https://github.com/maxxexee/pulse-lock)** | Watches every Solana pool launch and trade live, scores each token 0–100 with a visible breakdown, alerts in ~100–400 ms. Read-only: no custody, no keys in the hot path. | **mainnet**, Fly.io | TypeScript, Yellowstone gRPC |
| **[BlackRail](https://github.com/maxxexee/blackrail)** | Merchant payment gateway where addresses die after one use, so a business's revenue isn't a public ledger competitors can read. Flutterwave and Paystack alongside on-chain rails. | live API + portal | TypeScript, Express, Supabase |
| **[Stakely](https://github.com/maxxexee/Stakely)** | Two people bet each other with no bookmaker. Funds lock in an Anchor escrow program and settle from a TxLINE proof verified on-chain, leaving an auditable receipt. | devnet, WC26 hackathon | Anchor, Rust, React |

Also: **[R3nzo](https://github.com/maxxexee/aml-compliance-agent)** — OFAC screening inside a Terminal 3 TEE, only the verdict leaves the enclave (testnet).
**[AttestRWA](https://github.com/maxxexee/rwas-interoperability)** — RWA ownership proven on Ethereum, acted on by a Creditcoin contract, no bridge to drain.

---

## How I work

- **Every claim is checkable.** Vanta's README has a "what this is not" section, because a privacy wallet that overstates itself is a liability. Its own code forbids the words *anonymous* and *untraceable*.
- **I audit my own releases before shipping.** I ran an adversarial self-audit against the live Vanta APK over CDP, tracked 15 findings (3 critical, 6 high), and mapped each to remediation or explicit disclosure.
- **I answer reviews line by line.** An unrequested external automated review of Vanta got a point-by-point response in the repo — real findings accepted, the rest disputed with file paths and line evidence.
- **Honest about timing.** PulseLock's call cards show price at call → price now → peak since call. Most alert tools only publish the wins.

---

## Stack

**Daily:** TypeScript, Node.js, React, Solana, Anchor, Git, REST API design, technical writing
**Strong:** Kotlin (Android), Solidity, Foundry, Express, Supabase/Postgres, OpenAPI + Zod, Docker, Vite
**Working knowledge:** Rust, Python, SQL, Yellowstone gRPC, Drizzle, Tailwind, Telegram bots, Fly.io, Railway, GitHub Actions

---

## Writing

Nine months on contract with the **Band Protocol** core team (Jul 2025 – Mar 2026), turning oracle data feeds, cross-chain integrity and Cosmos SDK architecture into material developers can actually use. Monthly cadence of long-form engineering breakdowns, held inside a KPI-driven trial framework.

Competitions: **1st of 29** (Atlas, by thirdweb), **2nd of 98** (Palm USD, Superteam UAE), **2nd of 24** (Superteam Germany).

---

## Elsewhere

[Medium](https://medium.com/@fwmaxx) for the long-form writing · [X](https://x.com/maxvrtx) for build logs · [LinkedIn](https://linkedin.com/in/samuel-o-3809b42a9) if you're hiring
