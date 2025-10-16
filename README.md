# Linkerd Helm Environment Overrides

This repository provides environment-specific customization values for Linkerd Helm installation.

It is referenced by the Argo CD applications defined in the `linkerd-test` GitOps repo.

## Structure
values/
├── values-dev.yaml
├── values-stage.yaml
└── values-prod.yaml


Each environment YAML file overrides parameters like resource limits, identity configuration, and HA settings.
