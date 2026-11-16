# // obsidian-workflows · Alpha acceptance

Observed 2026-11-13: 92 tracked files; default `main`.

## Inventory
- CI: .github/workflows/check-dist.yml, .github/workflows/ci.yml, .github/workflows/codeql-analysis.yml, .github/workflows/docs-integrity.yml, .github/workflows/licensed.yml, .github/workflows/linter.yml, .github/workflows/release.yml
- Test-like files: __tests__/artifact-checks.test.ts, __tests__/build.test.ts, __tests__/catalog.test.ts, __tests__/dep-checks.test.ts, __tests__/deps.test.ts, __tests__/detect.test.ts, __tests__/lint.test.ts, __tests__/main.test.ts, __tests__/manifest.test.ts, __tests__/registry.test.ts, __tests__/release.test.ts, __tests__/repo-checks.test.ts
- Root README: yes
- SECURITY.md: yes

## Required before package or merge
- [ ] Accurate README with existing versus planned behavior, dependencies, setup, architecture and screenshots.
- [ ] Automated validation for important formats and boundary/negative cases, with CI evidence.
- [ ] Explicit security/privacy review and third-party license inventory.
- [ ] Fresh-checkout build/import on the correct platform or engine version.
- [ ] Versioned package, SHA-256 checksums, artifact provenance, release notes and rollback instructions.
- [ ] Confirm cross-repository API/schema or asset compatibility; avoid merging incompatible versions.

This is an evidence checklist, **not a passing test report**. Release remains blocked until tested.

BareBones Projects, Designed by: Justin Levesque-Welsch
