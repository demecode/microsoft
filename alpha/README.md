# Alpha Repositories

This directory is the workspace for independent repositories that live under the
`microsoft` head repo.

Each child directory, such as `coffee_agent`, should be initialized and managed
as its own Git repository. The head repo ignores child repo directories so their
source files, dependencies, branches, and commits stay separate.

Suggested layout:

```text
alpha/
  coffee_agent/
    .git/
    README.md
    src/
    tests/
```

Use the head repo for shared coordination files and keep product code inside the
child repos.
