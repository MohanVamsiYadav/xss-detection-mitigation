# XSS // SECURITY OPERATIONS
![Security](https://img.shields.io/badge/SECURITY-XSS-00ff41?style=for-the-badge) ![OWASP](https://img.shields.io/badge/OWASP-ZAP-black?style=for-the-badge)

```text
root@cyberlab:~$ assessment --status
[OK] Local Juice Shop assessment
[OK] ZAP report: 11 alert categories
[--] XSS execution unconfirmed
[--] Original remediation retests pending
```

Educational web security assessment by Bombothula Mohan Vamsi Yadav.

## Scan intelligence
| High | Medium | Low | Informational |
|---|---|---|---|
| 1 | 4 | 3 | 3 |

These are scanner alert categories, not confirmed XSS exploits. High refers to an off-site redirect.

[Original PDF report](reports/XSS_Final_Report.pdf) · [Deployment instructions](DEPLOY.md) · [Evidence](screenshots/)

## Run locally
`python3 -m http.server 8000 --directory docs` then open http://localhost:8000.

Backend: `cd backend && npm install && npm start`. The standalone examples do not patch Juice Shop. Only test authorized systems. The website is a static portfolio and safe-rendering demo, not a scanner.
