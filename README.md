# Copilot Workspace Instructions

This repository contains an engineering operating standard for use by GitHub Copilot for Python and data engineering work. Only for learning and experimentation

The single source of truth is:

- [.github/copilot-instructions.md](.github/copilot-instructions.md)

## Purpose

These instructions enforce consistent, production-minded behavior for:
- code structure and modularity
- type safety and explicit contracts
- data pipeline architecture and validation
- SQL/persistence boundaries
- testing, refactoring, reliability, and observability
- design pattern usage and failure semantics

## Who this is for

- Engineers using Copilot
- Teams that want repeatable implementation standards
- Projects where maintainability and deterministic behavior matter

## How Copilot should use this

1. Treat the instruction file as a strict operating standard.
2. Prefer the smallest safe change that solves root cause.
3. Preserve behavior unless a change is explicitly requested.
4. Keep architecture explicit, testable, and reversible.
5. Avoid unrelated edits and hidden side effects.

## Scope

The policy is optimized for:
- Python application code
- data engineering workflows (ingest → validate → transform → output)
- integrations with SQL/DB and external APIs
- CI/CD and code review quality gates

## Repository layout

```text
.github/
  [copilot-instructions.md](http://_vscodecontentref_/1)
