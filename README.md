# GitHub Actions Needs POC

This repo is home to a small POC of how to manage slightly unusual `needs` conditions between GitHub Action Workflow Jobs.

## Jobs

### `alpha`

Will only run if the current branch name includes the string `alpha`.

### `beta`

Will only run if the current branch name includes the string `beta`.

### `gamma`

Will run only if `alpha` _OR_ `beta` have run successfully.

