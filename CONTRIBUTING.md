# Contributing

## Reporting issues

Open an issue with the expected behavior, the actual behavior, and steps to reproduce. Include the output of `kubectl describe` or `kubectl logs` when relevant.

## Pull requests

1. Fork the repository and create a branch from `main`.
2. Keep commits small, with descriptive messages.
3. Test changes on a local Minikube cluster before opening the PR.
4. Describe what changes and why.

## Conventions

- YAML: 2-space indentation, no tabs.
- Kubernetes manifests go in `k8s/`; Helm values go in `monitoring/`.
- Never commit tokens, passwords or other credentials.
