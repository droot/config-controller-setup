# setup

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] setup`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree setup`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init setup
kpt live apply setup --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
