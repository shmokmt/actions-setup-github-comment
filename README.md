# actions-setup-tfcmt

[![Setup test](https://github.com/shmokmt/actions-setup-github-comment/actions/workflows/test.yml/badge.svg)](https://github.com/shmokmt/actions-setup-github-comment/actions/workflows/test.yml)

The shmokmt/actions-setup-github-comment action installs [suzuki-shunsuke/github-comment](https://github.com/suzuki-shunsuke/github-comment) to the `PATH` in your GitHub Actions.

## `Inputs`

### `version`

Optional. The version of tfcmt. Default is "latest".

## Usage

This action can run be on `ubuntu-latest` and `macos-latest`.

Use latest version

```yaml
steps:
  - uses: shmokmt/actions-setup-github-comment@v1
```

Use specific version

```yaml
steps:
  - uses: shmokmt/actions-setup-github-comment@v1
    with:
      version: v4.0.1
```
