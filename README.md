<div align="center">

# asdf-pkl-aws-secret-resource-reader [![Build](https://github.com/infrablocks/asdf-pkl-aws-secret-resource-reader/actions/workflows/build.yml/badge.svg)](https://github.com/infrablocks/asdf-pkl-aws-secret-resource-reader/actions/workflows/build.yml) [![Lint](https://github.com/infrablocks/asdf-pkl-aws-secret-resource-reader/actions/workflows/lint.yml/badge.svg)](https://github.com/infrablocks/asdf-pkl-aws-secret-resource-reader/actions/workflows/lint.yml)

[pkl-aws-secret-resource-reader](https://github.com/infrablocks/pkl-aws-secret-resource-reader) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add pkl-aws-secret-resource-reader
# or
asdf plugin add pkl-aws-secret-resource-reader https://github.com/infrablocks/asdf-pkl-aws-secret-resource-reader.git
```

pkl-aws-secret-resource-reader:

```shell
# Show all installable versions
asdf list-all pkl-aws-secret-resource-reader

# Install specific version
asdf install pkl-aws-secret-resource-reader latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pkl-aws-secret-resource-reader latest

# Now pkl-aws-secret-resource-reader commands are available
pkl-aws-secret-resource-reader --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/infrablocks/asdf-pkl-aws-secret-resource-reader/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tom Duckering](https://github.com/infrablocks/)
