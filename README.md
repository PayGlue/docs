# PayGlue Docs

Documentation for [PayGlue](https://payglue.io), published at **[docs.payglue.io](https://docs.payglue.io)**.

Built with [Mintlify](https://mintlify.com).

## What you'll find here

- **Get started** — how PayGlue works and quick answers to common questions
- **Ghost** — connecting your Ghost site and understanding what PayGlue sets up
- **Providers** — setup guides for Polar, Lemon Squeezy, Stripe, and PayPal
- **Mappings** — connecting payment products to Ghost membership tiers
- **Buy Buttons / Paywall / Pricing table** — embed options for your Ghost site
- **Troubleshooting** — common errors and diagnostic steps
- **Account & Security** — billing, team members, and how credentials are stored
- **Open Source** — about the PayGlue-OS repository and the BUSL 1.1 license

## Local preview

Install the Mintlify CLI:

```bash
npm i -g mint
```

Run at the root of this repo (where `docs.json` lives):

```bash
mint dev
```

Preview at `http://localhost:3000`.

## Contributing

Found something wrong or out of date? Open a pull request or an issue — corrections and clarifications are welcome.

For security issues, please follow the responsible disclosure process described in the [Security overview](https://docs.payglue.io/security/overview) rather than opening a public issue.

## Deployment

Changes merged into `main` are deployed to [docs.payglue.io](https://docs.payglue.io) automatically via the Mintlify GitHub integration.
