# minimal-reproduction-template

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

- Minor and patch updates are grouped together
- Some packages are excluded from the group, to demonstrate behaviour for ungrouped

## Current behavior

- Grouped
  - Have an minimum release age pending version upgrade available (`@sentry/core@10.28.0`) - it is suppressed but missing from Dependency Dashboard
  - Have an minimum release age allowed version upgrade available (`@opentelemetry/semantic-conventions@1.38.0`) - it is proposed in the all-minor-patch branch
- Ungrouped
  - Have an minimum release age pending version upgrade available (`import-in-the-middle@1.14.2`) - it is suppressed and present on Dependency Dashboard

## Expected behavior

- The would-be-grouped minimum release age pending version upgrade should be available in Dependency Dashboard for selection

## Link to the Renovate issue or Discussion

Put your link to the Renovate issue or Discussion here.
