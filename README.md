# 39778

## Current behavior

- Open updates
  - Update dependency `@opentelemetry/semantic-conventions` to v1.38.0
- Pending Status Checks
  - Update dependency `import-in-the-middle` to v1.15.0
  - Update dependency `import-in-the-middle` to v2

## Expected behavior

- Open updates
  - Update dependency `@opentelemetry/semantic-conventions` to v1.38.0
- Pending Status Checks
  - Update dependency `import-in-the-middle` to v1.15.0
  - Update dependency `import-in-the-middle` to v2
  - **Update dependency `@sentry/core` to v10.28.0**

Observation: `@sentry/core` is on v10.27.0, it has a newer release v10.28.0 that does not meet the 7 days `minimumReleaseAge`, but does not appear on the Dependency Dashboard because it's in a group.
For `import-in-the-middle` there is a newer release v1.15.0 (and v2) that does not meet the 3 months `minimumReleaseAge`, but appears on the Dependency Dashboard as it's not in a group.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/39778
