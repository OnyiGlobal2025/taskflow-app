# TaskFlow — Application & CI/CD Pipelines

Application source (backend + frontend) and GitHub Actions CI/CD pipelines for the TaskFlow multi-environment platform.

- **CI:** lint, test, Semgrep (SAST), Trivy (container scan), build & push to ECR
- **CD:** promote dev → staging → prod with manual approval gate, automated rollback, and Slack notifications

📖 **Full project documentation:** [taskflow-gitops](https://github.com/OnyiGlobal2025/taskflow-gitops)

---

## Internal Developer Portal (Backstage / TechDocs)

Beyond its Project 1 role, this repo is registered in the TaskFlow Backstage portal as the application/build layer. Its documentation is published to TechDocs; source lives in [`docs/`](./docs), with the build and delivery design in [`docs/architecture.md`](./docs/architecture.md).

- AWS account: `713923090919`
- Region: `us-east-1`
- Default branch: `main`