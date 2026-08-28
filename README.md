# GitHub Actions Workflows

Reusable GitHub Actions workflows for CI/CD pipelines.

## Workflows

| Workflow | Purpose |
|----------|---------|
| `build.yml` | Build and test projects |
| `release.yml` | Create GitHub releases |
| `docker.yml` | Build and push Docker images |
| `lint.yml` | Run linters (shellcheck, yamllint, golangci) |
| `test.yml` | Run Python/Go tests |
| `security-scan.yml` | Trivy + Gitleaks scanning |
| `ansible-lint.yml` | Validate Ansible roles |

## Usage

```yaml
jobs:
  build:
    uses: magos-cyber/github-actions-workflows/.github/workflows/build.yml@main
```

## License

MIT
