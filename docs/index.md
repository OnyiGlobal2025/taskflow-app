# TaskFlow Application

This is the TaskFlow application service — a Node.js/Express app built for observability from the ground up and delivered through a secure, policy-gated pipeline.

## What this is

- **The service** — an Express application that carries the TaskFlow workload.
- **Instrumented** — OpenTelemetry emits traces, metrics, and logs; pino writes structured JSON logs with trace and span IDs injected so logs correlate to traces.
- **Shipped safely** — every image is scanned and policy-checked before it reaches the registry.

## How it fits

`taskflow-app` produces the container image. Infrastructure comes from `taskflow-infra`, and the image is delivered to the cluster by the GitOps config in `taskflow-gitops`. This repo's only output is a trusted image in ECR.

## Where to go next

- [Architecture](architecture.md) — the build, scan, and delivery pipeline.