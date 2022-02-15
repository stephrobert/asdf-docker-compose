<div align="center">

# asdf-docker-compose [![Build](https://github.com/stephrobert/asdf-docker-compose/actions/workflows/build.yml/badge.svg)](https://github.com/stephrobert/asdf-docker-compose/actions/workflows/build.yml) [![Lint](https://github.com/stephrobert/asdf-docker-compose/actions/workflows/lint.yml/badge.svg)](https://github.com/stephrobert/asdf-docker-compose/actions/workflows/lint.yml)


[docker-compose](https://docs.docker.com/compose/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add docker-compose
# or
asdf plugin add docker-compose https://github.com/stephrobert/asdf-docker-compose.git
```

docker-compose:

```shell
# Show all installable versions
asdf list-all docker-compose

# Install specific version
asdf install docker-compose latest

# Set a version globally (on your ~/.tool-versions file)
asdf global docker-compose latest

# Now docker-compose commands are available
docker-compose --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/stephrobert/asdf-docker-compose/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Stephane ROBERT](https://github.com/stephrobert/)
