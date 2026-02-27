# setup-vind-test

Integration tests for [`loft-sh/setup-vind`](https://github.com/loft-sh/setup-vind).

## Test matrix

| Workflow | What it tests |
|----------|---------------|
| `test-basic` | Default cluster creation, workload deployment |
| `test-custom-name` | Custom cluster name via `name` input |
| `test-multi-cluster` | Two clusters in one job (platform + agent) |
| `test-k8s-version` | Pinned Kubernetes version via `kubernetes-version` input |
| `test-config-file` | Custom vcluster.yaml via `config` input |
