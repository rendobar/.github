<!--
  Rendobar — organization profile README
  Renders at https://github.com/rendobar
  To add a banner: drop logo-light.svg / logo-dark.svg in this repo's /assets
  folder and uncomment the <picture> block below.
-->

<div align="center">

<!--
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/logo-dark.svg">
  <img alt="Rendobar" src="./assets/logo-light.svg" width="280">
</picture>
-->

# Rendobar

### Video rendering infrastructure for developers and agents

Run FFmpeg as a hosted API. Submit a job, get back a rendered file — no servers, no queues, no GPU babysitting.

[![Website](https://img.shields.io/badge/website-rendobar.com-000?style=flat-square)](https://rendobar.com)
[![Docs](https://img.shields.io/badge/docs-rendobar.com%2Fdocs-000?style=flat-square)](https://rendobar.com/docs)
[![npm](https://img.shields.io/npm/v/@rendobar/sdk?style=flat-square&label=%40rendobar%2Fsdk)](https://www.npmjs.com/package/@rendobar/sdk)
[![License](https://img.shields.io/badge/license-MIT-000?style=flat-square)](https://github.com/rendobar)

</div>

---

## What is Rendobar?

**Rendobar is a platform for video rendering infrastructure.** Its first product is a hosted **FFmpeg API** — you send raw FFmpeg parameters over HTTP and Rendobar runs them on serverless compute, handling input fetching, execution, storage, and delivery. Built for developers integrating video processing into their apps, and for AI agents that need to render media without managing infrastructure.

## Start here

| You want to… | Go to |
| --- | --- |
| Call the API from code | **[@rendobar/sdk](https://www.npmjs.com/package/@rendobar/sdk)** · [SDK docs](https://rendobar.com/docs) |
| Render from your terminal | **[rendobar/cli](https://github.com/rendobar/cli)** — `curl rendobar.com/install.sh` |
| Wire Rendobar into an AI agent | **[rendobar/mcp](https://github.com/rendobar/mcp)** — Model Context Protocol server |
| Read the guides & API reference | **[rendobar.com/docs](https://rendobar.com/docs)** |

## Repositories

- **[cli](https://github.com/rendobar/cli)** — Serverless video processing from your terminal. Single binary, 5 platforms, auto-update.
- **[mcp](https://github.com/rendobar/mcp)** — Serverless media processing for AI agents. Published as `@rendobar/mcp` on npm.
- **[docs](https://github.com/rendobar/docs)** — Guides, API reference, and job-type recipes.

## Community & support

- 📖 Documentation — [rendobar.com/docs](https://rendobar.com/docs)
- 🐛 Found a bug? Open an issue on the relevant repo.
- 🔒 Security disclosures — see [SECURITY.md](https://github.com/rendobar/.github/blob/main/SECURITY.md)

## Built with Rendobar

Shipping something on Rendobar? Add the badge:

```md
[![Built with Rendobar](https://img.shields.io/badge/built%20with-Rendobar-000?style=flat-square)](https://rendobar.com)
```

[![Built with Rendobar](https://img.shields.io/badge/built%20with-Rendobar-000?style=flat-square)](https://rendobar.com)
