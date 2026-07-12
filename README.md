# KLAForge GitOps

KLAForge is a personal platform engineering project built to learn and
operate Kubernetes, GitOps, automation and cloud-native technologies.

## Platform

- Debian 13
- k3s
- Traefik
- Argo CD
- cert-manager
- GitHub Actions
- GitHub Container Registry

## Repository structure

```text
bootstrap/        Initial Argo CD bootstrap
clusters/         Cluster-specific configuration
infrastructure/   Shared platform components
applications/     Applications deployed on KLAForge
docs/             Architecture and operational documentation