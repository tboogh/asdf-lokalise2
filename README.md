<div align="center">

# asdf-lokalise2 [![Build](https://github.com/tboogh/asdf-lokalise2/actions/workflows/build.yml/badge.svg)](https://github.com/tboogh/asdf-lokalise2/actions/workflows/build.yml) [![Lint](https://github.com/tboogh/asdf-lokalise2/actions/workflows/lint.yml/badge.svg)](https://github.com/tboogh/asdf-lokalise2/actions/workflows/lint.yml)

[lokalise2](https://github.com/tboogh/lokalise2) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add lokalise2
# or
asdf plugin add lokalise2 https://github.com/tboogh/asdf-lokalise2.git
```

lokalise2:

```shell
# Show all installable versions
asdf list-all lokalise2

# Install specific version
asdf install lokalise2 latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lokalise2 latest

# Now lokalise2 commands are available
lokalise2 --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tboogh/asdf-lokalise2/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tobias Boogh](https://github.com/tboogh/)
