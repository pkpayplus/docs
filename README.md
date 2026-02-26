# PkPayPlus Documentation

This repository contains the official documentation for [PkPayPlus](https://merchant.pkpayplus.com/) — accept payments, manage products, and integrate with our APIs and SDKs.

The docs site is built with [Mintlify](https://mintlify.com) and deployed from this repo.

## What's in the docs

- **Getting started** — Introduction and overview
- **Features** — Products, payment links, customers, transactions, payouts, disputes, API keys, merchant ID
- **Integrations** — PHP SDK, Laravel, WordPress (and more coming)

## Development

### Prerequisites

- Node.js 18+
- [Mintlify CLI](https://www.npmjs.com/package/mint)

### Run locally

Install the Mintlify CLI (one-time):

```bash
npm i -g mint
```

From the root of this repo (where `docs.json` is):

```bash
mint dev
```

Open **http://localhost:3000** to preview the docs.

### Troubleshooting

- **`mint: command not found`** — Ensure `npm` global bin is in your `PATH`, or use `npx mint dev`.
- **404 on pages** — Run from the folder that contains `docs.json`.
- **Stale preview** — Run `mint update` to get the latest CLI.

## Publishing

Changes pushed to the default branch are deployed automatically when the [Mintlify GitHub app](https://dashboard.mintlify.com/settings/organization/github-app) is installed for this repo.

## Contributing

- Edit or add `.mdx` files for content; configure navigation in `docs.json`.
- See [Mintlify docs](https://mintlify.com/docs) for components and MDX usage.
- For AI-assisted writing: `npx skills add https://mintlify.com/docs`

## Links

- [PkPayPlus Merchant Dashboard](https://merchant.pkpayplus.com/)
- [Sign up](https://merchant.pkpayplus.com/sign-up)
- [API Keys](https://merchant.pkpayplus.com/dashboard/api-keys)
- [Support](mailto:support@pkpayplus.com)
