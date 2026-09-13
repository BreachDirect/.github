# BreachDirect

We build developer tooling for security and verifiability — scanners,
provenance, and contract-testing harnesses that slot into CI.

The tools ship as CLIs and GitHub Actions, report in SARIF / JSON / Markdown,
and come with tests, CI, and security checks enabled from day one.

## Projects

| Project | What it does |
|---|---|
| [sorseal](https://github.com/BreachDirect/sorseal) | Provenance + security scanning for WASM artifacts. Rebuild, hash, and seal deployed bytecode to a signed manifest, verify the deployed contract matches the source, and scan source + binary for 16 vulnerability patterns. Rust CLI + GitHub Action. |
| [stellargate](https://github.com/BreachDirect/stellargate) | DevSecOps gate — contract scanning, API contract locking, and secrets scanning as one CLI with a single pass/fail report. |
| [RytScan](https://github.com/BreachDirect/RytScan) | Zero-config static security scanner for smart contracts, with SARIF output and a CI merge gate. |
| [stellar-pathfinder](https://github.com/BreachDirect/stellar-pathfinder) | Cross-border remittance route finder for Stellar anchors, ranked by compounded fee and time. |
| [schemalock](https://github.com/BreachDirect/schemalock) | Declarative API contract test harness — one YAML file locks error envelopes, auth boundaries, and status code contracts across releases. |
| [shieldscan](https://github.com/BreachDirect/shieldscan) | Practical web vulnerability assessment for small businesses — automated scanning with plain-English remediation guidance. |
| [vaultsweep](https://github.com/BreachDirect/vaultsweep) | Secrets scanner for repos and CI that catches leaked keys, tokens, and default credentials before merge. |