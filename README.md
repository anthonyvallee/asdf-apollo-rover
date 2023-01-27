<div align="center">

# asdf-apollo-rover [![Build](https://github.com/anthonyvallee/asdf-apollo-rover/actions/workflows/build.yml/badge.svg)](https://github.com/anthonyvallee/asdf-apollo-rover/actions/workflows/build.yml) [![Lint](https://github.com/anthonyvallee/asdf-apollo-rover/actions/workflows/lint.yml/badge.svg)](https://github.com/anthonyvallee/asdf-apollo-rover/actions/workflows/lint.yml)


[Apollo Rover](https://www.apollographql.com/docs/rover/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add apollo-rover
# or
asdf plugin add apollo-rover https://github.com/anthonyvallee/asdf-apollo-rover.git
```

apollo-rover:

```shell
# Show all installable versions
asdf list-all apollo-rover

# Install specific version
asdf install apollo-rover latest

# Set a version globally (on your ~/.tool-versions file)
asdf global apollo-rover latest

# Now apollo-rover commands are available
rover --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/anthonyvallee/asdf-apollo-rover/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Anthony Vallee](https://github.com/anthonyvallee/)
