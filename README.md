# 37118

## Current behavior

- The `pip-compile` and `pip_requirements` managers show up on the Dependency Dashboard under Detected dependencies.
- MRs are created for "Refresh pip-compile outputs", but also for individual Python packages.

## Expected behavior

- `pip_requirements` manager should not be enabled
- PIP updates are managed by `pip-compile`, the only MR should be "Refresh pip-compile outputs"

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/37118
