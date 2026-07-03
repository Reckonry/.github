# Security Policy

Thank you for helping keep Reckonry secure.

Reckonry is designed to process financial and accounting data. Because of this, security and responsible disclosure are extremely important.

---

# Supported Versions

| Version | Supported |
|---------|:---------:|
| Latest stable | ✅ |
| Previous stable | ✅ |
| Older versions | ❌ |

---

# Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub Issues.**

Instead:

- Open a private GitHub Security Advisory if available.
- If private reporting is not available yet, contact the maintainers using the project's security contact once published.

Please include as much information as possible:

- Reckonry version
- Operating System
- .NET version
- Steps to reproduce
- Expected behavior
- Actual behavior
- Screenshots (if applicable)
- Logs (after removing sensitive information)

---

# Sensitive Information

Never include:

- Exchange API keys
- Wallet private keys
- Seed phrases
- Personal financial information
- Tax reports
- Exchange exports
- Personally identifiable information (PII)

If possible, reproduce the issue using anonymized or synthetic data.

---

# Security Principles

Reckonry follows several core security principles:

- Privacy by default
- No hidden network communication
- No telemetry without explicit consent
- Immutable audit trail
- Full source traceability
- No invented financial data
- Secure handling of sensitive files
- Reproducible calculations

---

# Scope

Security reports may include issues related to:

- Data integrity
- Financial calculations
- Ledger corruption
- Import validation
- Report generation
- Sensitive data exposure
- Dependency vulnerabilities
- Supply-chain attacks
- PDF generation
- Plugin isolation
- Cryptographic verification
- Hash generation

---

# Out of Scope

The following are generally considered out of scope:

- Documentation typos
- Feature requests
- UI improvements
- Unsupported operating systems
- Issues caused by modified third-party software

---

# Disclosure Process

When a valid security issue is reported:

1. We will acknowledge the report.
2. We will investigate the issue.
3. A fix will be prepared.
4. A new release will be published.
5. The reporter will be credited unless anonymity is requested.

---

# Responsible Disclosure

Please allow reasonable time for a fix before publicly disclosing vulnerabilities.

Responsible disclosure helps protect all Reckonry users.

---

# Our Commitment

Security is not only about preventing attacks.

For Reckonry, security also means:

- Every financial value must remain explainable.
- Every generated report must remain reproducible.
- Every imported transaction must remain traceable.
- Users must always remain in control of their data.

---

Thank you for helping make Reckonry a trustworthy open-source platform.
