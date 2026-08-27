# GitHub Actions Workflows

Reusable workflows for CI/CD pipelines.

## Usage

```yaml
jobs:
  build:
    uses: magos-cyber/github-actions-workflows/.github/workflows/build.yml@main
```

## Available Workflows

- build.yml - Build and test Go/Python projects
- release.yml - Create GitHub releases
- docker.yml - Build and push Docker images
- lint.yml - Run linters (shellcheck, yamllint, etc.)
