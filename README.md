<div align="center">

# asdf-puffin [![Build](https://github.com/saul-salazar-dotcom/asdf-puffin/actions/workflows/build.yml/badge.svg)](https://github.com/saul-salazar-dotcom/asdf-puffin/actions/workflows/build.yml) [![Lint](https://github.com/saul-salazar-dotcom/asdf-puffin/actions/workflows/lint.yml/badge.svg)](https://github.com/saul-salazar-dotcom/asdf-puffin/actions/workflows/lint.yml)

[puffin](https://github.com/siddhantac/puffin) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-puffin](#asdf-puffin--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add puffin
# or
asdf plugin add puffin https://github.com/saul-salazar-dotcom/asdf-puffin.git
```

puffin:

```shell
# Show all installable versions
asdf list-all puffin

# Install specific version
asdf install puffin latest

# Set a version globally (on your ~/.tool-versions file)
asdf global puffin latest

# Now puffin commands are available
puffin
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/saul-salazar-dotcom/asdf-puffin/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Zeno Jiricek](https://github.com/airtonix/)
