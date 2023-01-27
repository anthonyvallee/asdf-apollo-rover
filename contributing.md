# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test apollo-rover https://github.com/anthonyvallee/asdf-apollo-rover.git "rover --version"
```

Tests are automatically run in GitHub Actions on push and PR.
