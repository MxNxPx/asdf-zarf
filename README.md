<div align="center">

# asdf-zarf [![Build](https://github.com/MxNxPx/asdf-zarf/actions/workflows/build.yml/badge.svg)](https://github.com/MxNxPx/asdf-zarf/actions/workflows/build.yml) [![Lint](https://github.com/MxNxPx/asdf-zarf/actions/workflows/lint.yml/badge.svg)](https://github.com/MxNxPx/asdf-zarf/actions/workflows/lint.yml)


[zarf](https://github.com/defenseunicorns/zarf) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add zarf
# or
asdf plugin add zarf https://github.com/MxNxPx/asdf-zarf.git
```

zarf:

```shell
# Show all installable versions
asdf list-all zarf

# Install specific version
asdf install zarf latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zarf latest

# Now zarf commands are available
zarf --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MxNxPx/asdf-zarf/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Palassis](https://github.com/MxNxPx/)
