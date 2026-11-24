# Module 02: Linux, Security Tools & Reconnaissance

**Duration:** 28 November 2026 – 02 December 2026 | **Level:** Beginner

## Learning objectives
1. Linux fundamentals: files, directories, permissions, users, groups, processes and security basics.
2. Passive and active reconnaissance, DNS/domain information gathering and network enumeration.
3. Introductory use of Nmap, Wireshark, Burp Suite and OWASP ZAP.
4. A controlled reconnaissance lab with documented observations.

## Repository structure
- `docs/` — topic notes and tool guides
- `practicals/` — step-by-step beginner exercises
- `templates/` — lab record and findings report templates
- `scripts/` — read-only local system inventory helper

## Suggested order
1. Read the Linux fundamentals notes.
2. Complete Linux command practice.
3. Study reconnaissance and DNS concepts.
4. Review the four security tools.
5. Perform the practicals only in an authorized lab.
6. Fill report templates with your actual observations.

## Safety
Perform active scanning and web testing only on systems you own or have explicit written permission to assess. Use localhost, an isolated lab VM, or an intentionally vulnerable training application. Do not scan public, college, company, or third-party networks without authorization. Never publish credentials, tokens, personal data, or sensitive packet captures.

## Quick start
```bash
pwd
ls -la
whoami
ip addr
ps aux
```
Run the included read-only helper:
```bash
chmod +x scripts/system_inventory.sh
./scripts/system_inventory.sh
```

## Submission checklist
- [ ] Add your name and internship details if required.
- [ ] Complete practical exercises in an authorized lab.
- [ ] Replace `[ADD YOUR OBSERVATION]` placeholders with actual results.
- [ ] Add only sanitized screenshots, if permitted.
- [ ] Check that no secrets or personal information are included.
- [ ] Push the repository to GitHub and submit its link.

This is a learning starter repository. Do not claim an activity was completed unless you performed it.
