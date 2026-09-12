# Security

Jisr Pay is **Testnet-only** software. No private keys, seeds, or real funds
are involved — but it still exchanges transaction data with Stellar Testnet
services.

## Reporting a vulnerability

Please report security issues privately, not in public issues:

- Use GitHub **Security Advisories** (available in each repository under
  *Security → Report a vulnerability*), or
- Open a private issue titled `SECURITY:` and mention an organization owner.

Include a minimal reproducer and, if known, the affected components.

## Supported scope

- `jisr-web`, `jisr-sdk`, `jisr-api`, `jisr-routing`, `payment-router-contract`
  — current `main` branches only; drafts are pre-production and unsupported.

## Security principles

- No signing keys or signed transactions are ever stored server-side.
- Client-supplied uploads are never treated as settlement evidence.
- Amounts are compared as integers (stroops / base units), never floats.