# CodeCraft_CS_03
A Python-based tool that assesses password strength against security metrics including length, character diversity, and entropy rules.
# Password Complexity Checker

A Python security tool designed to evaluate the strength and resilience of passwords. It analyzes input against critical cybersecurity standards, assessing length, character variability, and predictability to provide real-time feedback and complexity scoring.

---

## 📌 Features

- **Multi-Factor Criteria Evaluation:**
  - Minimum length verification (8+ and 12+ character thresholds)
  - Uppercase and lowercase alphabet presence
  - Numeric character integration
  - Special symbol validation (`!@#$%^&*` etc.)
- **Strength Scoring:** Categorizes passwords dynamically into Weak, Moderate, Strong, or Very Strong.
- **Actionable Remediation:** Pinpoints exactly which criteria are missing to assist users in creating resilient credentials.

---

## 📁 Repository Structure

```text
├── password_checker.py                   # Core Python strength analysis engine
├── Password_Complexity_Checker_Report.pdf# Technical report and compliance documentation
├── .gitignore                            # Environment and artifact exclusions
└── README.md                             # Project documentation
