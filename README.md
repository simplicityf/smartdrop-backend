# SmartDrop backend

HTTP APIs, webhooks, and **indexing** for SmartDrop (planned). The current Heroku demo is served from the frontend repo; this repository is the home for future **Node** or **Rust** services that talk to **Horizon**, **Soroban RPC**, and your own database.

## Related repositories

| Repository | Role |
|------------|------|
| [**smart-frontend**](https://github.com/SmartDropLabs/smart-frontend) | Next.js static app |
| [**smartdrop-contracts**](https://github.com/SmartDropLabs/smartdrop-contracts) | Soroban Rust contracts |
| [**SmartDrop**](https://github.com/SmartDropLabs/SmartDrop) | Original monorepo (reference) |

## Status

No service implementation yet. Suggested first milestones: health check + Soroban RPC proxy, then event ingestion from contract `Topics`.
