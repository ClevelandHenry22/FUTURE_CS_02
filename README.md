# FUTURE_CS_02 (Phishing Email Detection & Awareness system)

# 🛡️ PhishGuard-Awareness — Phishing Detection & Awareness Report

> **ShadowFox Cybersecurity Internship | Task 2**
> Prepared by: **Cleveland Henry** | Kenyatta University, Nairobi, Kenya | April 2026

---

##  Overview

This repository contains a professional **Phishing Detection & Awareness Report** produced as part of the Future Interns Cybersecurity Internship Programme (Task 2). Unlike reports using synthetic examples, **this analysis is based on 7 real email screenshots** collected from live inboxes — making the findings directly applicable to real-world threat scenarios.

---

## Key Features
1. Identify phishing indicatiors (spoofed sender, fake domains, malicious links)
2. Classify emails as safe/suspicious/phishing
3. Explain phishing techniques in simple business friendly language
4. Provide clear prevention and awareness guidelines for users

---

##  Sample Classifications

| # | Subject | Sender | Classification | Risk |
|---|---------|--------|----------------|------|
| 1 | FYI (Games Con Discussion) | Adam John (Gmail) |  SAFE | None |
| 2 | OneDrive Action Required | **Venture.ru** | PHISHING | CRITICAL |
| 3 | Is Facebook Working For You? | Vinny (anon) |  PHISHING | CRITICAL |
| 4 | Drop Gaming Headset | Drop (drop.com) |  SAFE | None |
| 5 | You Are Needed | Vincent (anon) |  SCAM | CRITICAL |
| 6 | RE: WFH | Reuben.corrigan@anz.com |  SAFE | None |
| 7 | Geico Insurance Offer | **Val.kill.ma** |  PHISHING | CRITICAL |

**Result: 4 malicious / 3 legitimate**

---

##  Key Phishing Techniques Identified

| Technique | Observed In |
|-----------|-------------|
| Domain spoofing (non-Microsoft sender claiming OneDrive) | Email 2 |
| Lookalike URL (faceBook.com.opt — non-existent TLD) | Email 3 |
| Social engineering narrative (fake FBI agent) | Email 5 |
| Brand impersonation + obfuscated URL (Geico / urlif.y) | Email 7 |

---

##  Tools Used

| Tool | Purpose |
|------|---------|
| Google Admin Toolbox | Email header parsing, SPF/DKIM/DMARC evaluation |
| MXToolbox | Header visualization and authentication |
| VirusTotal | URL and domain reputation analysis |
| WHOIS / DomainTools | Domain registration age lookup |
| IANA TLD Registry | TLD legitimacy verification |
| Phishing.Database | Cross-reference against known phishing domains |

---

## Analysis Methodology

1. Screenshot collection from real inbox samples
2. Visual triage: sender, subject, body inspection
3. Header analysis: SPF, DKIM, DMARC, Return-Path
4. Domain/URL decomposition and TLD validation
5. Threat intelligence cross-referencing
6. Classification against three-tier risk model
7. Full indicator documentation with severity ratings

---

> Malicious URLs are displayed in defanged format (hxxp, [.]) throughout the report.

*Cleveland Henry | GitHub: ClevelandHenry22 | ShadowFox Cybersecurity Internship 2026*
