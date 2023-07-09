# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test gofumpt https://github.com/looztra/asdf-gofumpt.git "gofumpt --version"
```

Tests are automatically run in GitHub Actions on push and PR.
