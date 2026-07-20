# Needle Docs

Source for the [Needle](https://needle.so) documentation site, published at [docs.needle.so](https://docs.needle.so).

Needle is an AI-native applicant tracking system. These docs cover core workflows, candidate engagement, and integrations.

## Structure

- `index.mdx` — Getting started
- `jobs.mdx`, `pipeline.mdx`, `career-pages.mdx`, `screening.mdx` — Core workflows
- `sourcing.mdx`, `outreach.mdx` — Candidate engagement
- `slack.mdx`, `email-forwarding.mdx`, `mcp-server.mdx` — Integrations
- `feedback.mdx` — Resources
- `docs.json` — Site config (navigation, theme, logo)

## Local development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

Run the dev server from the repo root (where `docs.json` lives):

```bash
mint dev
```

Preview at `http://localhost:3000`.

## Publishing

Changes pushed to the default branch deploy automatically to [docs.needle.so](https://docs.needle.so) via the Mintlify GitHub app.

## Troubleshooting

- Dev server not running: `mint update` to get the latest CLI.
- 404 on a page: confirm you're running `mint dev` from the folder containing `docs.json`.

## Resources

- [Mintlify docs](https://mintlify.com/docs)
- [Needle](https://needle.so)