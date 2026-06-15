# GitHub Actions Lab

## Workflow 1 - Job Dependencies

Purpose:
Demonstrates sequential execution using the needs keyword.

Concepts:
- needs
- runs-on
- steps

Execution:
Build → Test → Deploy

## Workflow 2 - Multi Platform Testing

Purpose:
Demonstrates parallel execution on multiple operating systems.

Platforms:
- Ubuntu
- Windows
- macOS

Concepts:
- runs-on
- pull_request trigger
- actions/checkout@v4

Challenges Faced:
- YAML indentation errors
- Workflow trigger configuration

Resolution:
Validated YAML syntax and checked GitHub Actions logs.
