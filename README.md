# ClusterSage GitOps

This folder is the desired-state repository for ArgoCD. Terraform bootstraps ArgoCD into each AKS cluster; ArgoCD deploys application workloads from this layout.

## Layout

- `environments/dev/applications`: ArgoCD Applications for dev.
- `environments/dev/values`: dev Helm values.
- `environments/staging/applications`: ArgoCD Applications for staging.
- `environments/staging/values`: staging Helm values.
- `environments/prod/applications`: ArgoCD Applications for prod.
- `environments/prod/values`: prod Helm values.

Replace placeholder GitHub organization and image tags before enabling sync.
