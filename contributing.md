# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test lokalise2 https://github.com/tboogh/asdf-lokalise2.git "lokalise2 --version"
```

Tests are automatically run in GitHub Actions on push and PR.
