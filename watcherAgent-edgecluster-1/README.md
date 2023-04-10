# watcherAgent-edgecluster-1

## Description
Created by Nephio for cluster deployment

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] watcherAgent-edgecluster-1`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree watcherAgent-edgecluster-1`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init watcherAgent-edgecluster-1
kpt live apply watcherAgent-edgecluster-1 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
