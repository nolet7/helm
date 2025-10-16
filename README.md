# Linkerd Helm Configuration

This repository holds the Helm chart and environment-specific values for Linkerd.

### Structure
templates/ → base chart templates (namespace, cert secrets)
values/ → environment-specific values files (dev, stage, prod)


Each environment value file defines its own trust anchor and issuer certs.

Helm chart can be referenced by ArgoCD Applications in your linkerd-test GitOps repo.
