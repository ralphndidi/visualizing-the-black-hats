# Findings and Recommendations

## Scenario 1 — Ransomware
**Finding:** Business files and systems are unavailable after encryption and a ransom demand.

**Potential weaknesses:** Phishing susceptibility, outdated software, weak passwords, insufficient segmentation, and backups connected to the production network.

**Recommendations:** Staff awareness, MFA, patch management, endpoint protection, least privilege, segmentation, monitoring, tested offline or protected backups, and incident response procedures.

## Scenario 2 — Insider data theft
**Finding:** An employee with legitimate access copies customer records for an unauthorised purpose.

**Potential weaknesses:** Excessive permissions, weak monitoring, insufficient data-loss controls, and infrequent access reviews.

**Recommendations:** Least privilege, regular access reviews, alerting for unusual downloads, DLP, encryption, audit logs, staff policies, and prompt access revocation.

## Scenario 3 — Website defacement
**Finding:** A public website is altered to display an ideological message and becomes temporarily unavailable.

**Potential weaknesses:** Outdated CMS or plugins, weak administrator credentials, missing MFA, insecure server configuration, and unpatched software.

**Recommendations:** Patch CMS and plugins, use unique passwords and MFA, restrict admin access, remove unused accounts/plugins, deploy a WAF where appropriate, scan for vulnerabilities, monitor file integrity, and maintain clean backups and recovery procedures.

## Cross-scenario conclusion
Use layered controls: identity and access management, secure configuration, patching, monitoring, user awareness, backups, and tested incident response.
