# Security finding reference (tool isolation)

## Source
Global GitHub Security Advisory (not a repo-local code-quality finding).

| Field | Value |
|--------|--------|
| **GHSA** | [GHSA-jx74-cqjv-2c67](https://github.com/advisories/GHSA-jx74-cqjv-2c67) |
| **CVE** | CVE-2026-67426 |
| **Severity** | critical (CVSS 9.3) |
| **Summary** | Flyto2 Core: Unauthenticated flyto-verification `/run` callback_url SSRF and internal runner-secret exfiltration |
| **Ecosystem** | pip / `flyto-core` |
| **Patched** | 2.26.7 |

## Repo context (`sperez-source/build813`)
- Code scanning: no analysis found
- Dependabot alerts: disabled
- Secret scanning alerts: none open
- Code quality findings: not accessible (404/403)
- Repo security advisories: none
- Org security advisories (`XETesting`): not accessible (403)

## Related in-repo issue
Issue #10 — Viewer can still delete tasks via API (RBAC gap; not a CodeQL alert).

Disposable PR for GitHub security/tool isolation testing. Safe to close.
