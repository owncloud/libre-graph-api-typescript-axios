# agents.md -- Libre Graph API TypeScript/Axios Client

## Repository Overview

Auto-generated TypeScript client for the Libre Graph API using Axios for HTTP transport. Licensed under Apache-2.0. Used by ownCloud Web.

## Architecture & Key Paths

- `api.ts` -- Generated API client code
- `base.ts` -- Base API class
- `common.ts` -- Shared utilities
- `configuration.ts` -- Client configuration
- `index.ts` -- Package entry point

## Development Conventions

- Generated code -- do not edit directly
- TypeScript with Axios HTTP client
- ES module format

## Build & Test Commands

```bash
# Build system: Not detected
# This repository contains auto-generated TypeScript source files with no package.json or build configuration.
```

## Important Constraints

- Licensed under Apache-2.0 (already at the OSPO target license). The broader ownCloud organization is migrating other repositories from copyleft licenses to Apache 2.0.
- This is generated code. Changes should be made in the libre-graph-api spec, not here.
- All contributions require a DCO sign-off.


## OSPO Policy Constraints

### GitHub Actions
- **Only** use actions owned by `owncloud`, created by GitHub (`actions/*`), verified on the GitHub Marketplace, or verified by the ownCloud Maintainers.
- Pin all actions to their full commit SHA (not tags): `uses: actions/checkout@<SHA> # vX.Y.Z`
- Never introduce actions from unverified third parties.

### Dependency Management
- Dependabot is configured for automated dependency updates.
- Review and merge Dependabot PRs as part of regular maintenance.
- Do not introduce new dependencies without discussion in an issue first.

### Git Workflow
- **Rebase policy**: Always rebase; never create merge commits. Use `git pull --rebase` and `git rebase` before pushing.
- **Signed commits**: All commits **must** be PGP/GPG signed (`git commit -S -s`).
- **DCO sign-off**: Every commit needs a `Signed-off-by` line (`git commit -s`).
- **Conventional Commits & Squash Merge**: Use the [Conventional Commits](https://www.conventionalcommits.org/) format where the repository enforces it. Many repos use squash merge, where the PR title becomes the commit message on the default branch — apply Conventional Commits format to PR titles as well. A reusable GitHub Actions workflow enforces this.

## Context for AI Agents

All TypeScript files are auto-generated from the OpenAPI spec. This package is used by ownCloud Web for Libre Graph API communication. Modifications require updating the OpenAPI spec and regenerating.
