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

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add flyway
# or
asdf plugin add flyway https://github.com/lakshanwd/asdf-flyway.git
```

flyway:

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
