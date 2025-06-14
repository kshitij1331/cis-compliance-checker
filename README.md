# CIS Compliance Checker

A Python and Ansible-based automation tool to audit and remediate Linux systems based on the Center for Internet Security (CIS) Benchmarks.

## 📌 Features

- Audits RHEL/Ubuntu systems against CIS Benchmark v2.x guidelines
- Generates human-readable compliance reports
- Automatically remediates non-compliant configurations via Ansible playbooks
- Modular and customizable YAML tasks
- Supports dry-run and rollback modes
- Designed for secure enterprise automation

## 🛠️ Technologies Used

- Python 3
- Ansible
- Shell scripting
- YAML
- SSH/Paramiko
- Linux (RHEL, Ubuntu)

## 📁 Structure

cis-compliance-checker/
├── ansible/
│ ├── playbooks/
│ └── inventory/
├── scripts/
│ ├── audit_runner.py
│ └── utils.py
├── reports/
├── README.md
└── requirements.txt
