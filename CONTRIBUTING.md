# Contributing (Transport Repo)

This repository is a **distribution layer only**.

## What is allowed
- Typos in README files
- Formatting fixes
- Broken links
- Release-index corrections (only if backed by hash receipts)

## What is not allowed
- Adding “mechanisms,” “tooling,” “pipelines,” or “how-to” content
- Adding internal paths, ledgers, operational scripts, or archive mechanics
- PRs that change scope, intent, or interpretive framing
- PRs that re-sequence or “summarize” papers

## Integrity rule
All releases are **hash-anchored**.  
If a proposed change references a release, it must include:
- the `bundle_sha256`, and
- a pointer to the release manifest within this repo.

## Process
1. Open an issue describing the change.
2. Keep the change minimal and scoped.
3. No refactors. No “cleanup PRs.”
4. Maintainers may close PRs without discussion if scope expands.

PAU