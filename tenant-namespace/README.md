# tenant-namespace

## Description


## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] tenant-namespace`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree tenant-namespace`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init tenant-namespace
kpt live apply tenant-namespace --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
