> **AI agent instructions (organization-wide):** Before working on code, issues, or pull requests, read and follow the [organization `AGENTS.md`](https://github.com/atto-lang/.github/blob/main/AGENTS.md), including its **merge-first stealth-development policy**. Honor any repository-local `AGENTS.md`, explicit holds, and GitHub-enforced rules.

# atto-demos

Example applications showcasing AttoLang across platforms and use cases.

## Naming migration and language authority

This repository is maintained at [atto-lang/atto-demos](https://github.com/atto-lang/atto-demos); use `https://github.com/atto-lang/atto-demos.git` for Git remotes and canonical `.atto` source examples. The normative language contract is [atto-spec](https://github.com/atto-lang/atto-spec), with executable guest evidence tracked by [atto-platform-conformance](https://github.com/atto-lang/atto-platform-conformance). Follow current ownership, borrowing, effects, actor, and syntax rules there; do not infer implemented features from a README or unexecuted CI.

## What this project explores

A collection of practical reference programs and demonstrations across CLI, HTTP, actors, desktop and interop, with explicit backend feature gates.

## How to use these examples

1. Check the repository contents for `.atto` examples and target-specific project manifests.
2. Use the compiler/backend indicated by each example's actual files and scripts.
3. Run checked-in tests or example commands only where documented and verified.
4. Record compiler revision, expected output, and actual result when reporting an issue.

## Portability and status

These examples are intended to demonstrate AttoLang concepts. Examples may depend on unfinished language features or particular backends; their presence is not evidence that every listed feature executes on all targets. Unsupported features should be marked in the individual example's documentation.

## Links

- [AttoLang repositories](https://github.com/atto-lang)
- [Canonical language specification](https://github.com/atto-lang/atto-spec)
- [Backend conformance](https://github.com/atto-lang/atto-platform-conformance)

## Repository ownership and contribution routing

**Belongs here:** Curated cross-domain example applications, runnable manifests and links to individual domain-specific demo repos.

**Belongs elsewhere:** Single tiny introduction in atto-demo; isolated experiments in atto-proof-of-concepts; reusable libraries in library repos. Production-grade deployment and hosted tenant infrastructure, identity, marketplace and billing belong in separately governed product repositories, not in language demonstrations.

**Security and portability boundary:** Examples should use .atto where supported, preserve .ores legacy compatibility, list required permissions and exact verified compiler/runtime receipts.

AttoLang is the canonical project name; new source, examples and documentation use `.atto` and the `atto-lang` repository organization. This README defines scope, not feature readiness.

**Acceptance:** name exact source SHA/tree, runtime/toolchain, positive and negative checks and execution receipt before claiming support. Host-only tests and empty CI steps do not prove guest execution.

## Legacy compatibility and migration safeguards

The archived [Oreslang demos](https://github.com/ores-truffle-oreslang/oreslang-demos) are historical; this repository is the canonical AttoLang destination. Keep working `.ores` inputs, legacy package names and CLI paths until compiler-backed `.atto` compatibility is demonstrated for each relevant backend. Do not claim that a repository rename, copy or reopened PR establishes Git identity or feature parity.

Language examples, compilers, tooling and libraries belong in [atto-lang](https://github.com/atto-lang); hosted production infrastructure belongs in [atto-co](https://github.com/atto-co). For any future ownership transfer or product carve-out, obtain appropriate owner authorization and security review. Record repository ID, exact HEAD and tree, history, access, protection/rulesets, PRs, packages, releases, Actions runners and billing, secrets, webhooks, Apps, Pages, dependency URLs and rollback plan. Verify identity and security after the transfer and execute exact-head tests before changing consumer paths. Do not export private code without authorization. Empty or absent CI steps mean `NOT_EXECUTED`; host/reference checks do not establish guest execution.
