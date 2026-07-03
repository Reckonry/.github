# Contributing to LedgerForge

First of all, thank you for considering contributing to LedgerForge.

LedgerForge is an open-source engineering project focused on building verifiable digital asset accounting infrastructure.

Our goal is correctness, transparency and reproducibility over convenience.

---

# Project Philosophy

Before contributing, please understand the core principles of this project:

- Never invent financial data.
- Never silently ignore unknown information.
- Every generated number must be explainable.
- Every report must be reproducible.
- The canonical ledger is the single source of truth.
- Tax modules consume the ledger but never modify it.
- Correctness is always preferred over performance.

If a feature conflicts with these principles, it will most likely be rejected.

---

# Before Opening an Issue

Please check:

- existing Issues
- Discussions
- documentation
- ADRs

If you are proposing a new feature, explain:

- the problem
- why it matters
- possible implementation ideas

---

# Pull Requests

Every Pull Request should:

- solve a single problem
- include tests
- build successfully
- not introduce warnings
- update documentation when needed
- preserve backward compatibility whenever possible

Large PRs are discouraged.

---

# Coding Standards

- Follow existing architecture.
- Keep classes focused.
- Prefer composition over inheritance.
- Use immutable models whenever possible.
- Use `decimal` for financial values.
- Never use `double` for money or crypto amounts.
- Preserve source data.
- Never delete unknown information.

---

# Testing

Every contribution must include appropriate tests.

Before submitting a PR, run:

```bash
dotnet build LedgerForge.sln

dotnet test LedgerForge.sln
```

All tests must pass.

---

# Architecture

LedgerForge follows Clean Architecture.

Importers produce a canonical ledger.

Reports consume the ledger.

Tax modules consume the ledger.

Reconciliation never modifies the ledger.

Please read the Architecture Decision Records (ADRs) before changing core behavior.

---

# Security

Never commit:

- private exchange exports
- wallet addresses
- personal financial information
- generated reports
- secrets
- API keys

Use fake or anonymized data for tests.

---

# Documentation

If your contribution changes public behavior:

- update README
- update architecture documentation
- update ADRs if architectural decisions changed

---

# Discussions

Ideas are welcome.

Before implementing large changes, start a Discussion so the architecture can be reviewed first.

---

# Code of Conduct

By participating in this project you agree to follow the Code of Conduct.

---

# Thank You

Every contribution helps make LedgerForge a more trustworthy and transparent platform for digital asset accounting.

Build.
Verify.
Trust.
