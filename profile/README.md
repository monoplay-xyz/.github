# MonoPlay

Multi-chain game launcher and publishing platform powered by Monolythium.

## Repositories

| Repo | Description |
|------|-------------|
| [monoplay-contracts](https://github.com/monoplay-xyz/monoplay-contracts) | Smart contracts (GameRegistry, ReleaseRegistry, LicenseRegistry, SeederRewards) |
| [monoplay-backend](https://github.com/monoplay-xyz/monoplay-backend) | Backend API gateway (catalog, licenses, auth, submissions) |
| [monoplay-indexer](https://github.com/monoplay-xyz/monoplay-indexer) | Chain event indexer (Monolythium blockchain) |
| [monoplay-launcher](https://github.com/monoplay-xyz/monoplay-launcher) | Desktop game launcher (Tauri 2 + React 19) |
| [monoplay-dev-console](https://github.com/monoplay-xyz/monoplay-dev-console) | Developer/publisher portal (Next.js) |
| [monoplay-admin-console](https://github.com/monoplay-xyz/monoplay-admin-console) | Admin moderation console (Next.js) |
| [monoplay-scanner](https://github.com/monoplay-xyz/monoplay-scanner) | Security scanning service (Python + YARA) |

## Architecture

```
Launcher (Desktop)  <-->  Backend API  <-->  PostgreSQL
                              |
Dev Console (Web)   <-->      |
Admin Console (Web) <-->      |
                              |
Scanner (Python)    <-->      |
                              |
Chain Indexer       <-->  Monolythium Blockchain
```

## Links

- Website: [monoplay.xyz](https://monoplay.xyz)
- Part of the [Monolythium](https://github.com/monolythium) ecosystem
