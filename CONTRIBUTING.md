# Contributing to mfeflow

Thanks for helping. mfeflow is early, so the best contributions right now are
issues: bugs, rough edges, and what you need from a micro-frontend platform.

## Setup

```bash
git clone https://github.com/mfeflow/mfeflow.git
cd mfeflow
corepack enable
pnpm install
pnpm run ci
```

## Pull requests

- One change per PR. The PR title is the commit on `main` (squash merge), so
  it must follow [Conventional Commits](https://www.conventionalcommits.org/):
  `feat: …`, `fix: …`, `docs: …`, `chore: …`.
- `pnpm run ci` passes locally: format, lint, typecheck, test, build.
- New code comes with tests next to it (`*.test.ts`); coverage stays ≥ 80%.
- A change to a published package needs a changeset: `pnpm changeset`.
- `starter` and the generated parts of `examples` are produced by the CLI.
  Change the templates in `mfeflow/mfeflow`, not the generated files.

## Reporting security issues

Do not open a public issue. See [SECURITY.md](SECURITY.md).
