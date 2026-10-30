# Changelog

## [Unreleased]

### CLAUDE.md keeps this repo's own rules

- The rules every rljson repo shares (coverage, pinning, docs, releases,
  reviews) come with the rljson DNA: `doc/guides/rljson-guide.md` and
  `doc/guides/for-ai/rljson-review-guide.md`. `CLAUDE.md` no longer repeats
  them and no longer describes the old `gg one` workflow.

## [0.0.20]

### Developed in gg tickets

- **Developed in gg tickets.** The rljson DNA (`@rljson/dna-rljson`) is raised to gg's current workflow: the `/gg-*` skills, the development guide and the quick check.
- **Pull requests are checked by the quick check** (`gg one did commit`: every commit went through gg's local lint, tests and coverage). `Build and Test` runs on `main` after the merge.
- **vitest also runs `test/**/*.test.ts`,** where gg's release writes the version test.
- **Dependencies raised to their newest versions** (TypeScript 6 among them).

## [0.0.1]

Initial commit.
