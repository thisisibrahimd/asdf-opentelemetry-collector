<div align="center">

# asdf-opentelemetry-collector [![Build](https://github.com/thisisibrahimd/asdf-opentelemetry-collector/actions/workflows/build.yml/badge.svg)](https://github.com/thisisibrahimd/asdf-opentelemetry-collector/actions/workflows/build.yml) [![Lint](https://github.com/thisisibrahimd/asdf-opentelemetry-collector/actions/workflows/lint.yml/badge.svg)](https://github.com/thisisibrahimd/asdf-opentelemetry-collector/actions/workflows/lint.yml)

[opentelemetry-collector](https://github.com/open-telemetry/opentelemetry-collector) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add opentelemetry-collector
# or
asdf plugin add opentelemetry-collector https://github.com/thisisibrahimd/asdf-opentelemetry-collector.git
```

opentelemetry-collector:

```shell
# Show all installable versions
asdf list-all opentelemetry-collector

# Install specific version
asdf install opentelemetry-collector latest

# Set a version globally (on your ~/.tool-versions file)
asdf global opentelemetry-collector latest

# Now opentelemetry-collector commands are available
otelcol --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/thisisibrahimd/asdf-opentelemetry-collector/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ibrahim Diallo](https://github.com/thisisibrahimd/)
