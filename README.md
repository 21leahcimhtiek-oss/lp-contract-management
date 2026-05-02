# contract-management

AI-powered application from Aurora Market.

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
