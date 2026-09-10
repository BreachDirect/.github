# BreachDirect

Open-source security infrastructure for the Stellar / Soroban ecosystem.

We build tooling that makes Soroban development more secure, verifiable, and
auditable — for contract teams and the exchanges, wallets, and custodians they
deploy to.

## Projects

| Project | What it does |
|---|---|
| [sorseal](https://github.com/BreachDirect/sorseal) | Provenance + security scanner for Soroban/WASM artifacts. Rebuild, hash, and seal deployed bytecode to a signed manifest; verify on-chain; scan source and WASM for 16 known vulnerability patterns (missing auth, reentrancy, oracle manipulation). Rust CLI + GitHub Action. |
| [stellargate](https://github.com/BreachDirect/stellargate) | Unity DevSecOps gate for Stellar projects — contract scanning, API contract locking, and secrets scanning as one CLI with a single pass/fail report. |
| [stellar-pathfinder](https://github.com/BreachDirect/stellar-pathfinder) | Cross-border remittance route finder for Stellar anchors, ranked by compounded fee and time. |
| [RytScan](https://github.com/BreachDirect/RytScan) | Zero-config static security scanner for Soroban smart contracts with SARIF output and a CI merge gate. |
| [schemalock](https://github.com/BreachDirect/schemalock) | Declarative API contract test harness for Stellar backends. |
| [shieldscan](https://github.com/BreachDirect/shieldscan) | AI-assisted web vulnerability assessment for small businesses. |
| [vaultsweep](https://github.com/BreachDirect/vaultsweep) | Stellar-aware secrets scanner for repos and CI. |

## Wave 9

Part of the [Stellar Drips Wave 9](https://www.drips.network/wave/stellar)
program. The fastest ways to get involved:

1. Pick a [`good-first-issue`](https://github.com/BreachDirect/sorseal/labels/good-first-issue) — small, scoped, guided.
2. Run `sorseal analyze` against your own contract and report what you find.
3. Add a detection rule — new Soroban issue classes are great intermediate tasks.

Every project here ships with CI, tests, and security checks enabled.