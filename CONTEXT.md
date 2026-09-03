# IBMa/equal-access context
> refreshed 2026-09-03 | upstream default: main-4.x @ 79c64ddffec2b27b4f4ac0d24c33d807d55a2848

## Identity & policies
- upstream: IBMa/equal-access, default branch main-4.x, primary language JavaScript/TypeScript (monorepo: engine, extension, node/CLI, karma/cypress/vitest wrappers, java, rule-server, report-react)
- English-first: yes (all docs/README in English)
- CLA/DCO: DCO (Developer's Certificate of Origin 1.1) — commits must carry `Signed-off-by`; no CLA bot, no contributor signup
- AI-assisted PR policy: unstated (no ban, no disclosure requirement) — fork PRs carry no AI mention
- signed commits required: no
- PR template: `.github/pull_request_template.md` (present) — fill verbatim; title format `chore(repo): ...` / `fix(engine|extension|node|karma|cypress): ...`; requires DCO comment on the PR
- external tracker: github

## Conventions (verified from merged PRs)
- branch naming: `issue-<number>` for issue-driven work; `chore(...)`/`fix(...)`/`feature(...)`/`deps`/`archive-...` for others; descriptive kebab for self-found work
- commit style: Conventional Commits (`fix(engine): ...`, `chore(repo): ...`, `build(deps): ...`)
- CI: GitHub Actions (test.yml, master.yml, publish.yml); substantive checks run on PRs
- merge: maintainers use LGTM; two LGTMs from maintainers of each affected component; recent external merges seen (samueldmeyer, nam-singh, shunguoy)

## Maintainer picture
- active maintainers: IBM accessibility team; responsive (multiple merges/day on main-4.x)
- areas actively worked: simulator, rule engine fixes, dependency updates, archives

## Issue-area health
- open issues include rule-engine correctness bugs (#2103, #2087, #2082) — not for trivial pass
- trivial/docs/typo PRs: no ban; CONTRIBUTING welcomes low-hanging fruit

## Gap ledger (dedupe — READ FIRST, never re-pick)
- `2026-09-03` trivial/minor-fix pass (typos/broken links/stale commands) — outcome: see tried-repos.jsonl — one-line lesson: docs-only, meaning-preserving, >=3 fixes, <=10 files

## Mined gaps (discovered, not yet attempted)
- none yet
