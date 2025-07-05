
---

## ⚙️ `action-repo` — GitHub Actions Workflow

```markdown
# ⚙️ Action Repo

This repository demonstrates GitHub Actions workflows for automating tasks like webhook emission and CI/CD triggers.

---

## 🚀 Workflow Overview

Located in `.github/workflows/emit-webhook.yml`, this workflow:

- Runs on push to `main`
- Emits a test webhook payload to your Flask endpoint
- Can be extended for CI/CD or deployment automation

---

## 📂 Files

- `.github/workflows/emit-webhook.yml`: GitHub Actions workflow
- `demo.txt`: Sample file to trigger push events
- `README.md`: Project overview

---

## 🧪 How to Trigger

1. Edit `demo.txt` or any file
2. Commit and push:
   ```bash
   git add .
   git commit -m "Trigger GitHub Action"
   git push origin main

