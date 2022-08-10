# ns

## Description
Provision new namespace

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] ns`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree ns`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init ns
kpt live apply ns --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
