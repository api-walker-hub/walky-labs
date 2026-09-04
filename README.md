# Walky Labs — Website

Marketing site for **Walky Labs**, a digital lab building solutions in agentic AI, MCP gateways, model gateways, API management and web3.

## Stack

Pure static site — a single `index.html` with embedded CSS/JS. No build step, no dependencies.

- Fonts: Fraunces, Instrument Sans, IBM Plex Mono (Google Fonts)
- Hosting: DigitalOcean App Platform (static site), spec in `.do/app.yaml`

## Local preview

```bash
npx serve .
```

## Deploy

The site auto-deploys from the `main` branch via DigitalOcean App Platform (`deploy_on_push`). To create the app the first time:

```bash
doctl apps create --spec .do/app.yaml
```
