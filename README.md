# Mintlify Docs Source

This folder contains the DealDash documentation content intended for `https://docs.drdj.me/`.

## Current state

The live site is served from the synced Mintlify docs repository. Changes here publish after they are pushed to `main` and `.github/workflows/docs-sync.yml` syncs this folder to `djasha/docs`.

## Publish this content

1. Merge changes to `main`.
2. Confirm `DOCS_REPO_PAT` is configured for the docs sync workflow.
3. Let `.github/workflows/docs-sync.yml` push `mintlify-docs/` into `djasha/docs`.
4. Verify navigation tabs/pages at `https://docs.drdj.me/`.

## Validate links locally (repo side)

```bash
pnpm docs:check
```
