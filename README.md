<div align="center">

# asdf-flyway [![Build](https://github.com/lakshanwd/asdf-flyway/actions/workflows/build.yml/badge.svg)](https://github.com/lakshanwd/asdf-flyway/actions/workflows/build.yml) [![Lint](https://github.com/lakshanwd/asdf-flyway/actions/workflows/lint.yml/badge.svg)](https://github.com/lakshanwd/asdf-flyway/actions/workflows/lint.yml)

[flyway](https://flywaydb.org/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add flyway https://github.com/lakshanwd/asdf-flyway.git
```

For pre-0.16.0 asdf versions:

```shell
asdf plugin-add flyway https://github.com/lakshanwd/asdf-flyway.git
```

flyway:

```shell
# Show all installable versions
asdf list all flyway

# Install specific version
asdf install flyway latest

# Set a version globally (on your ~/.tool-versions file)
asdf set -u flyway latest

# Now flyway commands are available
flyway --version
```

For pre-0.16.0 asdf versions:

```shell
# Show all installable versions
asdf list-all flyway

# Install specific version
asdf install flyway latest

# Set a version globally (on your ~/.tool-versions file)
asdf global flyway latest

# Now flyway commands are available
flyway --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/lakshanwd/asdf-flyway/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Lakshan Dissanayake](https://github.com/lakshanwd/)
