# TaskFlow — Application & CI/CD Pipelines

Application source (backend + frontend) and GitHub Actions CI/CD pipelines for the TaskFlow multi-environment platform.

- **CI:** lint, test, Semgrep (SAST), Trivy (container scan), build & push to ECR
- **CD:** promote dev → staging → prod with manual approval gate, automated rollback, and Slack notifications

📖 **Full project documentation:** [taskflow-gitops](https://github.com/OnyiGlobal2025/taskflow-gitops)