# contract-management

AI-powered application from Aurora Rayes ecosystem.

## Domain
https://auroramarket.org

## Features
- Premium-only AI tools
- No free tier
- Subscription required

## Deployment (Vercel)
This repository is configured for static deployment on Vercel.

1. Import this repository in Vercel.
2. Keep the Framework Preset as **Other**.
3. Leave the Build Command empty.
4. Deploy from the repository root.

## Environment Variables
Copy `.env.example` to `.env` and configure:

- `NEXT_PUBLIC_APP_URL`
- `NODE_ENV`
- `STRIPE_SECRET_KEY`
- `STRIPE_WEBHOOK_SECRET`
- `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY`
- `DATABASE_URL`
- `OPENAI_API_KEY`

## License
See LICENSE file for details.

## Aurora Ecosystem Positioning
This project is positioned as part of the Aurora ecosystem and is ready for Aurora-aligned workflows and automation.

### No-Key-First Operation
This repository supports a no-key-first setup for local evaluation and onboarding, with optional credentials only for advanced integrations.

<!-- AURORA:README:START -->
## Aurora Rayes alignment

**Aurora Raye Lp Contract Management** is the preferred human-readable product name for generated Aurora Rayes collateral. The repository slug stays unchanged unless a separate rename process is approved.

- Keep README messaging grounded in verified capabilities already present in this repo.
- Prefer no-key-first evaluation and onboarding paths when the repo supports them.
- Keep SELL.md and MARKETING.md aligned with the actual setup, deployment, and feature surface documented here.
<!-- AURORA:README:END -->

