# Security Policy

## Supported Versions

Security updates are strictly applied to active notebooks currently maintained on our primary branch.

| Version | Supported          |
| ------- | ------------------ |
| Main    | 🟢 Supported        |
| < Main  | ❌ Not Supported   |

## Reporting a Vulnerability

### 🚨 Crucial Notice Regarding Jupyter Notebook Cell Outputs
Jupyter Notebooks can accidentally cache and save sensitive data in hidden execution states or print statements. 
* **Do not** open a public issue if you locate an inadvertently exposed Kaggle API Token (`kaggle.json`), a database connection string, or cloud architecture profile keys inside a notebook commit history.
* Opening a public issue risks immediate exploitation of account tokens or computational cloud runtime allocations.

### How to Report Privately
If you identify an exposed credential or data vulnerability within a notebook print block, please report it immediately to the project owner:
* **Email:** janhavir11@gmail.com

You will receive an initial response within 48 hours to coordinate clearing the repository cache, rewriting Git histories, and rolling back active tokens. Thank you for keeping this machine learning workspace safe!
