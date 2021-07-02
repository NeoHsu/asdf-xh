<div align="center">

# asdf-xh ![Build](https://github.com/NeoHsu/asdf-xh/workflows/Build/badge.svg) ![Lint](https://github.com/NeoHsu/asdf-xh/workflows/Lint/badge.svg)

[xh](https://github.com/ducaale/xh) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add xh
# or
asdf plugin add xh https://github.com/NeoHsu/asdf-xh.git
```

xh:

```shell
# Show all installable versions
asdf list-all xh

# Install specific version
asdf install xh latest

# Set a version globally (on your ~/.tool-versions file)
asdf global xh latest

# Now xh commands are available
xh --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/NeoHsu/asdf-xh/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Neo Hsu](https://github.com/NeoHsu/)
