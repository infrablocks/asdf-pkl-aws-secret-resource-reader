# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test pkl-aws-secret-resource-reader https://github.com/infrablocks/asdf-pkl-aws-secret-resource-reader.git "pkl-aws-secret-resource-reader --help"
```

Tests are automatically run in GitHub Actions on push and PR.
