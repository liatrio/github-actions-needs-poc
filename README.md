# GitHub Actions Needs POC

This repo is home to a small POC of how to manage slightly unusual `needs` conditions between GitHub Action Workflow Jobs.

## Jobs

### `alpha`

Will only run if the current branch name includes the string `alpha`.

### `beta`

Will only run if the current branch name includes the string `beta`.

### `gamma`

Will run only if `alpha` _OR_ `beta` have run successfully.

## Example

To see a working example, you can refer to the following two runs of the workflow:

- [Branch name includes `alpha`][0]
- [Branch name includes `beta`][1]

[0]: https://github.com/liatrio/github-actions-needs-poc/actions/runs/5742562207
[1]: https://github.com/liatrio/github-actions-needs-poc/actions/runs/5742562729
