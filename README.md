# Jisr Pay

![Jisr Pay](https://raw.githubusercontent.com/jisr-pay/.github/main/assets/logo.svg)

Jisr Pay — جسر (bridge) — is a Testnet payment experiment on the Stellar network: a web client, an SDK of reusable payment primitives, and an internal settlement-tracking API.

## Repositories

| Repository | Purpose |
| --- | --- |
| [jisr-web](https://github.com/jisr-pay/jisr-web) | Consumer application on Stellar Testnet — wallet, cross-border corridors, receipts and history. |
| [jisr-sdk](https://github.com/jisr-pay/jisr-sdk) | Reusable payment primitives extracted from the web client. |
| [jisr-api](https://github.com/jisr-pay/jisr-api) | Internal Testnet transfer tracking and read-only reconciliation API. |
| [jisr-routing](https://github.com/jisr-pay/jisr-routing) | Indicative quote provider interface and exact comparison. |
| [payment-router-contract](https://github.com/jisr-pay/payment-router-contract) | Reference `route_payment` contract inspection and source-recovery notes. |
| [.github](https://github.com/jisr-pay/.github) | Organization defaults: profile, community health files, brand assets. |

## Brand

The brand assets (logo and icon) live in [assets](assets). The mark is a bridge arch between two anchors — violet `#7C3AED` on near-black, with gold `#F59E0B` anchor dots. Projects should reference `assets/logo.svg` from the `.github` repository: `https://raw.githubusercontent.com/jisr-pay/.github/main/assets/logo.svg`.

## Security

This is Testnet-only software. Do not use it with real funds. Report vulnerabilities per [SECURITY.md](SECURITY.md) and contribute per [CONTRIBUTING.md](CONTRIBUTING.md).