<div align="center">

# asdf-cli [![Build](https://github.com/selleo/asdf-cli/actions/workflows/build.yml/badge.svg)](https://github.com/selleo/asdf-cli/actions/workflows/build.yml) [![Lint](https://github.com/selleo/asdf-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/selleo/asdf-cli/actions/workflows/lint.yml)

[cli](https://github.com/selleo/cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add cli
# or
asdf plugin add cli https://github.com/selleo/asdf-cli.git
```

cli:

```shell
# Show all installable versions
asdf list-all cli

# Install specific version
asdf install cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cli latest

# Now cli commands are available
selleo version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/selleo/asdf-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [selleo](https://github.com/selleo/)
