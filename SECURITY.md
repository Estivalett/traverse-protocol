# Security Policy

Traverse Protocol moves value across chains. Security is not a feature — it is the product. We take vulnerability reports seriously and appreciate the work of researchers who help keep the protocol and its users safe.

## Status

Traverse is currently on **testnet**. Smart contracts are under active development. An internal review has been completed (findings TRV-09 through TRV-12 remediated); an independent third-party audit is planned before mainnet. Until that audit is complete and published, treat all deployments as experimental.

## Supported Versions

| Version | Supported |
| ------- | --------- |
| `main` (testnet) | :white_check_mark: |
| Older tags / branches | :x: |

Security fixes are applied to `main`. We do not backport to historical branches during the testnet phase.

## Reporting a Vulnerability

**Please do not open a public GitHub issue for security vulnerabilities.**

Instead, report privately through one of the following:

- **Email:** security@traverseprotocol.io
- **GitHub:** use the *"Report a vulnerability"* button under the **Security** tab (private advisory)

When reporting, please include:

- A clear description of the issue and its impact
- Steps to reproduce, or a proof-of-concept
- The affected contract(s), file(s), and commit hash
- Any suggested remediation, if you have one

## What to Expect

- **Acknowledgement** within 3 business days.
- **Triage and severity assessment** within 7 business days, shared with you.
- **Coordinated disclosure** — we will work with you on a timeline and credit you publicly (if you wish) once a fix is deployed.

We ask that you give us reasonable time to remediate before any public disclosure.

## Scope

In scope:

- Smart contracts in this repository
- The solver reference implementation
- Settlement, staking, slashing, and fee-distribution logic
- Governance and timelock contracts

Out of scope:

- The marketing website and social accounts
- Third-party bridges, RPC providers, or dependencies (report those upstream)
- Issues requiring physical access or social engineering of the team
- Testnet token faucet abuse

## Bug Bounty

A formal bug bounty program is planned to launch alongside the third-party audit and mainnet. Until then, we recognize impactful reports publicly and prioritize them in our remediation queue. Watch `#announcements` in Discord for the bounty launch.

## A Note on Safety

The Traverse team will **never** DM you first, ask for your seed phrase or private keys, or ask you to connect your wallet outside our official links. Report impersonation to us directly.

- Site: https://traverseprotocol.io
- Discord: https://discord.gg/vCAyXMkjf
- X: https://x.com/TRVProtocol
