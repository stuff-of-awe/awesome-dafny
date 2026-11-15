<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->
# Awesome Dafny

Dafny is a verification-aware programming language whose verifier produces obligations for automated reasoning. Correctness claims remain relative to specifications, toolchain versions and trusted components.

**Status:** starter collection, initial review 2026-11-15. **Curator:** unassigned — contributions welcome. Entries are original short annotations of external sources, not endorsements or copies of their content. No tool was installed or executed for this initial list.

## Start here

- [Dafny official site](https://dafny.org/dafny/) — Choose an installation route and understand the verification workflow.
- [Dafny tutorials and resources](https://dafny.org/dafny/toc) — Study contracts, invariants, termination and proof structure.
- [Dafny quick start](https://dafny.org/) — Find the current official onboarding and documentation links.

## References and implementations

- [Dafny source](https://github.com/dafny-lang/dafny) — Track releases, verifier changes and bug reports.
- [Dafny reference material](https://dafny.org/dafny/toc) — Locate the language reference, verification optimization guidance and FAQs.

## Examples and community routes

- [Official Dafny examples](https://github.com/dafny-lang/dafny/tree/master/Source/IntegrationTests) — Study tests of the language and verification pipeline; their layout can change.
- [Dafny issue tracker](https://github.com/dafny-lang/dafny/issues) — Investigate version-sensitive behaviors and known limitations.

## First exercise (not yet execution-tested here)

Write a small precondition/postcondition example, deliberately break it, then restore the invariant; record verifier version and solver output.

## Assurance and interoperability

A passing verifier establishes only the specified obligations under its trusted assumptions. Distinguish proofs, program compilation, runtime behavior and unproven dependencies.

## Scope and upstream survey

This collection exists to offer a task-oriented route through Dafny, with explicit source-level and execution-evidence boundaries. A preliminary 2026-11-15 search identified broader alternatives such as [awesome-formal-verification](https://github.com/hohieuai/awesome-formal-verification) and [formal-verification-resources](https://github.com/astrio-labs/formal-verification-resources); a comprehensive upstream awesome-list survey is still required. We have not claimed uniqueness, tested these resources, or adopted upstream text. Related categories: [Stuff of Awe catalogue](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/CATALOGUE.adoc).

This list is community maintained, not a mirror or endorsement by any linked project. Please send link, licence, version and security corrections by [issue](https://github.com/stuff-of-awe/awesome-dafny/issues) or [PR](https://github.com/stuff-of-awe/awesome-dafny/pulls). Follow [curation policy](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/MAINTENANCE.adoc). Text in this repository is CC-BY-SA-4.0; upstream materials retain their own licences.
