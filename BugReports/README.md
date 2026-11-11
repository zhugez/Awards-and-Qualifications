# Bug Reports

Security vulnerability research and responsible disclosure reports.

---

## Findings

### WordPress Ecosystem (Patchstack / Wordfence)
| CVE ID | Vulnerability Type | Target Plugin & Affected Versions | CVSS | Platform | Status |
|---|---|---|---|---|---|
| **CVE-2026-119514** | Privilege Escalation / Broken Access Control | **RepairBuddy – Repair Shop CRM** (<= 4.1234) | 6.3 Medium | Patchstack / Wordfence | Published |
| **CVE-2026-123468** | Broken Access Control (CWE-862) | **Motors – Car Dealership & Classified Listings** (<= 1.4.128, patched in 1.4.129) | 4.3 Medium | Patchstack / Wordfence | Published |
| **CVE-2026-115431** | Broken Access Control (CWE-862) | **Upsell Funnel Builder for WooCommerce** (<= 3.1.6) | 4.3 Medium | Patchstack / Wordfence | Published |

### Telegram for Android
| ID | Vulnerability Type | Severity | Platform | Status |
|---|---|---|---|---|
| TG-01 | Native C++ Integer Truncation — File Descriptor Sandbox Verification | High (7.5) | Telegram Bug Bounty | Pending Resolve |
| TG-02 | Unauthenticated OAuth Token Redirect via Exported Intent | High (7.1) | Telegram Bug Bounty | Pending Resolve |

### IUH
| ID | Vulnerability Type | Severity | Platform | Status |
|---|---|---|---|---|
| IUH-01 | Reflected client-side DOM sink injection | Medium (6.9) | IUH | Validated |
| IUH-02 | Sensitive Credential Leak (Gitleaks) | High (8.7) | IUH | Validated |
| IUH-03 | Sensitive File Exposure | High (8.7) | IUH | Validated |

---

## Directories

| Directory | Description |
|-----------|-------------|
| `Report Bug PatchStack/` | Broken Access Control & Privilege Escalation (CVE-2026-119514, CVE-2026-123468, CVE-2026-115431) |
| `Report Bug Telegram/` | Security research on Telegram for Android |
| `Report Bug IUH/` | Vulnerability report submitted to IUH |

---

> All technical reproduction steps, PoC exploit scripts, and further evidence are withheld pending authorized disclosure.
