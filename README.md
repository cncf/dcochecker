# dcochecker

DCO Checker GitHub Action

## Sample workflow

```yaml
name: DCO
on:
  pull_request:
jobs:
  check:
    uses: cncf/dcochecker/.github/workflows/dco.yml@main
```
