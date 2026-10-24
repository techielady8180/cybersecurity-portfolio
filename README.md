# Cybersecurity Portfolio

Hands-on security work covering **incident response, digital forensics, scripting and risk management**, built while studying cybersecurity at City Colleges of Chicago.

**Focus areas:** security operations · log analysis · incident handling · IT risk · cloud security
**Training:** CompTIA Network+ CompTIA Security Plus · ISACA IT Risk Fundamentals · ISACA AI training · CAPM Certification

---

## Projects

### Scripts (`/scripts`)
| Script | What it does | Skills shown |
| --- | --- | --- |
| [`failed_login_detector.py`](scripts/failed_login_detector.py) | Parses an auth log, counts failed SSH logins per IP, flags brute-force attempts, and raises severity when a success follows the failures. Optional CSV report. | Python, regex, log analysis, detection logic |
| [`file_integrity_checker.py`](scripts/file_integrity_checker.py) | Builds a SHA-256 baseline of a folder and reports added, removed or modified files. | Hashing, integrity monitoring, forensics fundamentals |
| [`log_triage.sh`](scripts/log_triage.sh) | First-look triage of an auth log with `grep`, `awk`, `sort` and `uniq`. | Bash, Linux command line |

**Try it:**
```bash
cd scripts
python3 failed_login_detector.py sample_data/auth.log
./log_triage.sh sample_data/auth.log
```

### Incident response (`/incident-response`)
- [**Phishing playbook**](incident-response/phishing-playbook.md): a step-by-step response plan following the six-phase IR lifecycle.
- [**Brute-force case study**](incident-response/brute-force-case-study.md): analysis of a simulated SSH attack using my scripts, with containment steps and MITRE ATT&CK mapping.

### Digital forensics (`/forensics`)
- [**Forensic lab report**](forensics/forensic-lab-report-template.md): chain of custody, hash verification, findings and timeline from a hands-on Autopsy lab. *(In progress: completing Cybrary's Digital Forensics Basics lab.)*

### Risk management (`/risk-management`)
- [**IT risk register**](risk-management/sample-risk-register.md): likelihood × impact scoring and treatment plans for a small healthcare technology company.

---

## Tools and skills
`Python` · `Bash` · `Linux` · `Git` · `Autopsy` · `Wireshark` · `SIEM concepts` · `MITRE ATT&CK` · `NIST incident response` · `Risk assessment`

## Ethics
All data in this repository is simulated. IP addresses come from ranges reserved for documentation (RFC 5737). These tools are for defensive learning and authorized use only.

## Contact
[LinkedIn](https://www.linkedin.com/in/tr2026) · [chicitytechie2026@outlook.com]
