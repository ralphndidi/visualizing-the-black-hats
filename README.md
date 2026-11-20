# 🕵️ Visualizing the Black Hats
### Cybersecurity Threat Actor Research & Analysis

![Project](https://img.shields.io/badge/Project-Cybersecurity%20Lab-1f6feb)
![Focus](https://img.shields.io/badge/Focus-Threat%20Analysis%20%7C%20Defensive%20Security-238636)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Scope](https://img.shields.io/badge/Scope-Educational-lightgrey)

> A defensive cybersecurity research activity exploring three hypothetical attackers, their motives, attack methods, target weaknesses, and practical mitigation strategies.

---

## 📌 Project Overview

This project examines three fictional cyberattack scenarios to understand how different threat actors operate and how organisations can reduce cyber risk. Each scenario is analysed using six questions:

- Who is the attacker?
- What organisation or group are they associated with?
- What is their motive?
- What attack method was used?
- What target and vulnerability were involved?
- How could the attack be prevented or mitigated?

The scenarios are hypothetical and are used strictly for education. They do not describe allegations against real people or organisations.

## 🎯 Learning Objectives

By completing this activity, I practised how to:

- Distinguish external cybercriminals, malicious insiders, and hacktivists.
- Identify common attacker motivations.
- Explain ransomware, insider data theft, and website defacement.
- Recognise technical, human, and procedural weaknesses.
- Recommend layered security controls and incident response actions.
- Communicate security findings in a structured report.

## 🧩 Scenarios Analysed

### 1. Ransomware Attacker — DarkMan / Black Box

A fictional attacker compromises a transport company, encrypts business files, and demands payment.

**Key risks:** phishing, outdated software, weak passwords, inadequate network segmentation, and exposed backups.

**Defensive recommendations:** security awareness, MFA, patching, endpoint protection, protected offline backups, least privilege, network segmentation, monitoring, and an incident response plan.

### 2. Data-Stealing Insider — John

A fictional employee misuses legitimate access to copy and disclose customer records.

**Key risks:** excessive permissions, weak activity monitoring, inadequate data-loss controls, and infrequent access reviews.

**Defensive recommendations:** least privilege, periodic access reviews, monitoring unusual downloads, data loss prevention (DLP), encryption, access logging, and timely removal of access.

### 3. Website Defacement Hacktivist — Digital Herd

A fictional hacktivist group compromises a company's public website and replaces its home page with a political message.

**Key risks:** outdated CMS software or plugins, weak administrator passwords, missing MFA, insecure server configuration, and unpatched software.

**Defensive recommendations:** timely updates, strong unique credentials, MFA, restricted administrative access, a web application firewall (WAF), vulnerability scanning, file-integrity monitoring, clean backups, and a recovery plan.

## 🧠 Threat Analysis Summary

| Scenario | Threat actor | Primary motive | Attack method | Main weakness |
|---|---|---|---|---|
| 1 | DarkMan / Black Box | Financial gain | Ransomware, potentially delivered through phishing | Human and technical security gaps |
| 2 | John (insider) | Financial gain | Unauthorised use of legitimate access | Excessive access and weak monitoring |
| 3 | Digital Herd | Ideological / political | Website defacement | Website, CMS, or administrator weaknesses |

## 🛡️ Security Concepts Demonstrated

- **Threat actor:** A person or group capable of carrying out a cyberattack.
- **Ransomware:** Malware that encrypts or locks data and demands payment.
- **Phishing:** Deceptive communication intended to trick a person into taking an unsafe action.
- **Insider threat:** Risk arising from someone inside an organisation misusing, or accidentally exposing, their access.
- **Hacktivist:** An actor who uses cyber activity to promote a political or social cause.
- **Vulnerability:** A weakness in a system, application, process, or human practice.
- **Mitigation:** A measure that reduces the likelihood or impact of a security incident.
- **MFA:** Multi-factor authentication, using two or more different checks to verify identity.

## 📁 Repository Structure

```text
visualizing-the-black-hats/
├── README.md
├── LICENSE
├── .gitignore
├── docs/
│   ├── project-overview.md
│   ├── methodology.md
│   └── findings-and-recommendations.md
├── evidence/
│   ├── scenario-1-ransomware/
│   ├── scenario-2-insider-threat/
│   └── scenario-3-website-defacement/
├── screenshots/
│   └── README.md
├── research/
│   ├── threat-actor-comparison.md
│   └── key-terms.md
├── templates/
│   ├── scenario-analysis-template.md
│   └── evidence-log-template.md
└── references/
    └── references.md
```

## 🔬 Methodology

1. Read the supplied lab activity and identify the facts in each hypothetical scenario.
2. Classify the threat actor and stated motivation.
3. Identify the attack method and affected business asset.
4. Separate scenario facts from possible vulnerabilities or assumptions.
5. Map each weakness to appropriate preventive, detective, and recovery controls.
6. Record findings and recommendations in the evidence folders.
7. Review the final report for clarity and consistency.

**Important:** Where the scenario describes a possible entry route or weakness rather than a confirmed fact, it is labelled as a possibility. No live systems were scanned, accessed, or tested as part of this research activity.

## 📊 Key Findings

The scenarios demonstrate that cyber risk can originate from external criminals, employees with legitimate access, and ideologically motivated groups. Different motives and techniques can still exploit familiar weaknesses: poor access control, weak authentication, unpatched software, inadequate monitoring, and insufficient recovery planning.

A layered security approach is therefore essential. No single control can prevent every incident.

## 🖼️ Screenshots & Evidence

Use `screenshots/` for genuine screenshots of your completed work, such as:

- Your final report open on your computer.
- Your repository after creation on GitHub.
- Your completed evidence or analysis documents.
- Relevant course or lab completion evidence, where permitted.

Use the scenario-specific folders under `evidence/` for notes and supporting documents. Do not add fabricated screenshots or claim that a tool was used when it was not.

## 🚀 How to Upload This Project to GitHub

1. Extract the downloaded ZIP file.
2. Open the extracted `visualizing-the-black-hats` folder.
3. Create a new **public** GitHub repository named `visualizing-the-black-hats` (or choose private if preferred).
4. Do not initialise the GitHub repository with a README, licence, or `.gitignore` because these are already included.
5. Open Git Bash inside the extracted project folder.
6. Run:

```bash
git init
git add .
git commit -m "Add Visualizing the Black Hats cybersecurity lab"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/visualizing-the-black-hats.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username. If Git reports that `origin` already exists, check it with `git remote -v` before changing it.

## 🧰 Suggested Repository Details

**Repository name:** `visualizing-the-black-hats`

**Description:** `Defensive cybersecurity research analysing three hypothetical threat actors: ransomware, insider data theft, and hacktivist website defacement. Includes threat analysis, vulnerabilities, evidence templates, and mitigation strategies.`

**Suggested topics:** `cybersecurity`, `threat-analysis`, `ransomware`, `insider-threat`, `hacktivism`, `security-awareness`, `risk-management`, `cybersecurity-lab`

## 👨‍💻 Author

**Raphael Ndidi-Uboma**  
Cybersecurity Learner | Ethical Hacking | GRC | Security Analysis

This repository documents an educational lab activity and demonstrates foundational threat analysis and defensive security reasoning.

## 📚 Reference

Cisco Networking Academy. (2018–2020). *Lab – Visualizing the Black Hats*. Cisco Public.  
Assignment instructions supplied for this activity.

---

⭐ If you find this project useful, feel free to explore the documentation and use the templates for your own authorised learning activities.
