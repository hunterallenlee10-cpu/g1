# CLAUDE.md

Guidance for Claude Code when working in this repository.

## Workflow rules (set by the repo owner)

- **One request = one pull request.** Every change the owner asks for, no matter how small, goes on its own fresh branch with its own PR against the default branch. Never bundle multiple requests into one PR.
- **Always send the PR link** after opening it so the owner can review and merge it themselves. Do not merge PRs unless the owner explicitly asks.
- **Base every new branch on the latest tip of the default branch** so PRs stay independent and conflict-free.

## Repo and hosting notes

- The site is a single static `index.html`.
- The live site deploys via Vercel (`template-eight-alpha-75.vercel.app`), connected to this repo. Merging a PR into the default branch is what publishes changes.
