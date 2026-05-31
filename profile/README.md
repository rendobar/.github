<div align="center">

<a href="https://rendobar.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.rendobar.com/assets/brand/logo-mark.svg">
    <img alt="Rendobar" src="https://cdn.rendobar.com/assets/brand/logo-mark-black.svg" width="96">
  </picture>
</a>

### Rendobar

Media processing API for developers and agents

<br>

<a href="https://rendobar.com">
  <img src="https://rendobar.com/brand/og-default.jpg" alt="Rendobar: media processing API for developers and agents" width="100%">
</a>

<br>
<br>

[![Website](https://raw.githubusercontent.com/rendobar/.github/main/assets/badge-website.svg)](https://rendobar.com)
[![Docs](https://raw.githubusercontent.com/rendobar/.github/main/assets/badge-docs.svg)](https://rendobar.com/docs)
[![npm](https://img.shields.io/npm/v/@rendobar/sdk?style=flat-square&label=%40rendobar%2Fsdk&color=059669)](https://www.npmjs.com/package/@rendobar/sdk)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/kAGqjBzx8N)
[![X](https://img.shields.io/badge/follow-%40rendobar-0A0A0A?style=flat-square&logo=x&logoColor=white)](https://x.com/rendobar)

</div>

---

## What is Rendobar?

Rendobar is a media processing platform for developers and agents. You send a job over one REST endpoint and get back a processed file. Rendobar runs the heavy work on managed serverless infrastructure, so there are no servers to provision, no queues to babysit, and no FFmpeg builds to maintain.

The platform exposes several products. Rendobar's FFmpeg API runs raw FFmpeg commands in a sandboxed container. Alongside it sit higher-level operations for captions, watermarks, transcoding, and more, all billed from a single credit balance. It is MCP-native, so AI agents can call it through the Model Context Protocol the same way a human calls the REST API.

## Start here

| You want to | Go to |
| --- | --- |
| Call the API from TypeScript | **[`@rendobar/sdk`](https://www.npmjs.com/package/@rendobar/sdk)** on npm |
| Process media from your terminal | **[`rendobar/cli`](https://github.com/rendobar/cli)** &nbsp;·&nbsp; `curl rendobar.com/install.sh` |
| Wire Rendobar into an AI agent | **[`rendobar/mcp`](https://github.com/rendobar/mcp)** &nbsp;·&nbsp; `npx -y @rendobar/mcp` |
| Read the guides and API reference | **[rendobar.com/docs](https://rendobar.com/docs)** |

## Public repositories

- **[cli](https://github.com/rendobar/cli):** the `rb` binary. Serverless media processing from your terminal. Single binary, five platforms, auto-update.
- **[mcp](https://github.com/rendobar/mcp):** `@rendobar/mcp`, a stdio MCP server that gives Claude, Cursor, and other agents direct access to the platform, including local file uploads.
- **[docs](https://github.com/rendobar/docs):** guides, API reference, and job-type recipes published at rendobar.com/docs.

## Community and support

- **Docs:** [rendobar.com/docs](https://rendobar.com/docs)
- **Discord:** [discord.gg/kAGqjBzx8N](https://discord.gg/kAGqjBzx8N)
- **Bugs:** open an issue on the relevant repository.
- **Security:** see [SECURITY.md](https://github.com/rendobar/.github/blob/main/SECURITY.md). Please report privately.

## Powered by Rendobar

Shipping on Rendobar? Add the badge to your README:

```md
[![Powered by Rendobar](https://raw.githubusercontent.com/rendobar/.github/main/assets/built-with-rendobar.svg)](https://rendobar.com)
```

<div align="center">

[![Powered by Rendobar](https://raw.githubusercontent.com/rendobar/.github/main/assets/built-with-rendobar.svg)](https://rendobar.com)

</div>
