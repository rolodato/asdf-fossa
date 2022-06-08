<div align="center">

# asdf-fossa [![Build](https://github.com/rolodato/asdf-fossa/actions/workflows/build.yml/badge.svg)](https://github.com/rolodato/asdf-fossa/actions/workflows/build.yml) [![Lint](https://github.com/rolodato/asdf-fossa/actions/workflows/lint.yml/badge.svg)](https://github.com/rolodato/asdf-fossa/actions/workflows/lint.yml)


[fossa](https://github.com/fossas/fossa-cli/blob/master/docs/README.md) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add fossa
# or
asdf plugin add fossa https://github.com/rolodato/asdf-fossa.git
```

fossa:

```shell
# Show all installable versions
asdf list-all fossa

# Install specific version
asdf install fossa latest

# Set a version globally (on your ~/.tool-versions file)
asdf global fossa latest

# Now fossa commands are available
fossa --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rolodato/asdf-fossa/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Rodrigo López Dato](https://github.com/rolodato/)
