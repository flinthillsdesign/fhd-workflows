# fhd-workflows

A shared workflow that is reused on most repos.

```yaml
name: ci

on: push

jobs:
  call-workflow:
    uses: flinthillsdesign/fhd-workflows/.github/workflows/wordpress.yml@master
```
