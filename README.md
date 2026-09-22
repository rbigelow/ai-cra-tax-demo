# ai-cra-tax-demo
An agent-based demo for CRA.

## Secure CRA audit interface prototype

This repository contains a static Bootstrap 5 prototype for a secure CRA auditor workflow, including:
- `index.html` – assigned audit dashboard
- `audit-file.html` – audit file detail workspace
- `tax-return.html` – tax return detail and drill-down view
- `notes-evidence.html` – audit notes and evidence viewer
- `audit-report.html` – printable/exportable audit report

To preview locally, run:

```bash
cd /home/runner/work/ai-cra-tax-demo/ai-cra-tax-demo
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000/index.html`.
