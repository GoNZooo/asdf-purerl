<div align="center">

# asdf-purerl [![Build](https://github.com/GoNZooo/asdf-purerl/actions/workflows/build.yml/badge.svg)](https://github.com/GoNZooo/asdf-purerl/actions/workflows/build.yml) [![Lint](https://github.com/GoNZooo/asdf-purerl/actions/workflows/lint.yml/badge.svg)](https://github.com/GoNZooo/asdf-purerl/actions/workflows/lint.yml)


[purerl](https://github.com/purerl/purerl) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add purerl
# or
asdf plugin add purerl https://github.com/GoNZooo/asdf-purerl.git
```

purerl:

```shell
# Show all installable versions
asdf list-all purerl

# Install specific version
asdf install purerl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global purerl latest

# Now purerl commands are available
purerl --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/GoNZooo/asdf-purerl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Rickard Andersson](https://github.com/GoNZooo/)
