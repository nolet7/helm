# Helm Values Repository

This repository contains environment-specific Helm values used by ArgoCD to deploy Linkerd.

## Structure
values/
├── values-dev.yaml
├── values-stage.yaml
└── values-prod.yaml


Vault paths used for mTLS:
- `linkerd/dev`
- `linkerd/stage`
- `linkerd/prod`

Each contains `ca_crt`, `issuer_crt`, and `issuer_key`.
