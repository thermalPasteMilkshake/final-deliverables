# AI Application Security Assessment — Final Deliverables

Consolidated evidence for a full-stack AI security assessment of a fictional
internal AI assistant (LLM + MCP + CI/CD + web), carried out across nine projects.

**Annotated report:** [`Final-Deliverables-Report.pdf`](Final-Deliverables-Report.pdf)
— every screenshot below with an explanatory note, in project-wise sections.

## Evidence by project

| # | Project | Screenshots | Repository |
|---|---------|-------------|------------|
| 1 | LLM Security Fundamentals | [`1/`](1) | https://github.com/thermalPasteMilkshake/project1-vulnerable-ai-chat |
| 2 | Prompt Injection Defence | [`2/`](2) | https://github.com/thermalPasteMilkshake/project2-defence-layer |
| 3 | AI Red Teaming | [`3/`](3) | https://github.com/thermalPasteMilkshake/project3-redteam |
| 4 | MCP Pentesting | [`4/`](4) | https://github.com/thermalPasteMilkshake/project4-mcp-security |
| 5 | DevSecOps Pipeline | [`5/`](5) | https://github.com/thermalPasteMilkshake/techcorp-devsecops-gates |
| 6 | Full Penetration Test | [`6/`](6) | https://github.com/thermalPasteMilkshake/project6-pentest |
| 7 | Compliance Mapping | [`7/`](7) | https://github.com/thermalPasteMilkshake/project7-compliance |
| 8 | Reporting & Presentation | [`8/`](8) | https://github.com/thermalPasteMilkshake/project8-report |
| 9 | Capstone Secure Application | [`9/`](9) | https://github.com/thermalPasteMilkshake/project-9 |

## Headline results
- **12 findings** — 4 Critical, 6 High, 2 Medium (overall risk: **High**).
- Confirmed live: SQL injection + auth bypass, secrets embedded in the AI prompt,
  MCP remote code execution and path traversal, prompt injection, CI/CD with no
  security gates, and vulnerable dependencies.
- Compliance: OWASP ASVS **56%**, NIST CSF **60%**, EU AI Act **67%**.
- A hardened capstone app (JWT auth, input validation, output scanning, pinned
  dependencies, passing CI/CD gates) demonstrates the fixes.

All testing was performed in an authorised local lab against purpose-built
vulnerable targets.
