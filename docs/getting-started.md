# Getting started

## Install

```
- uses: fitzyracing1/action-add-labels@v1
  with:
    labels: |
      bug
```

Inputs (`action.yml`): `github_token` (default `github.token`), `labels` (required, newline-separated), `repo` (default current), `number`. For the strictest setup, pin the release commit SHA.

## Usage

Change only the `uses:` line from `actions-ecosystem/action-add-labels@v1`. The inputs are the same and there are no outputs.

## Develop and test

```
npm ci
npm run typecheck && npm run format-check
npm run build    # ncc -> dist/ (commit dist)
npm test         # node --test test/*.test.mjs
```
