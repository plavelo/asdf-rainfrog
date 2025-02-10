<div align="center">

# asdf-rainfrog [![Build](https://github.com/plavelo/asdf-rainfrog/actions/workflows/build.yml/badge.svg)](https://github.com/plavelo/asdf-rainfrog/actions/workflows/build.yml) [![Lint](https://github.com/plavelo/asdf-rainfrog/actions/workflows/lint.yml/badge.svg)](https://github.com/plavelo/asdf-rainfrog/actions/workflows/lint.yml)

[rainfrog](https://github.com/plavelo/rainfrog) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add rainfrog
# or
asdf plugin add rainfrog https://github.com/plavelo/asdf-rainfrog.git
```

rainfrog:

```shell
# Show all installable versions
asdf list-all rainfrog

# Install specific version
asdf install rainfrog latest

# Set a version globally (on your ~/.tool-versions file)
asdf global rainfrog latest

# Now rainfrog commands are available
rainfrog --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/plavelo/asdf-rainfrog/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Kengo Tachibana](https://github.com/plavelo/)
