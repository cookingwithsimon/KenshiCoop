# Fork notes

This repository is a GitHub fork of [nhoral/KenshiCoop](https://github.com/nhoral/KenshiCoop),
taken at upstream `v0.51` (`5a761e1`). It stays AGPL-3.0 and keeps the upstream credits.
Fixes made here are sent back upstream as pull requests, one bug per branch, opened
from this fork against `nhoral/KenshiCoop:main`.

## Working with upstream

```bash
git remote add upstream https://github.com/nhoral/KenshiCoop
git fetch upstream
git merge upstream/main
```

## Game identity

Record the build before trusting any offsets or hooks.

| | |
|---|---|
| Store and build | Steam, Kenshi 1.0.65 (upstream target); local build: unknown |
| `kenshi_x64.exe` SHA-256 | unknown |
| RE_Kenshi version | unknown (0.3.1+ required) |

## Private state

Install paths, logs, saves and notes about a specific PC go in `local/`, which git
ignores.

## Known gaps in upstream docs

- `docs/BUILD_SETUP.md` points to `resources/BUILD_SETUP.md`, which upstream does not
  publish (`resources/` is gitignored), so the full toolchain guide is missing.
