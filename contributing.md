# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test opentelemetry-collector https://github.com/thisisibrahimd/asdf-opentelemetry-collector.git "otelcol --help"
```

Tests are automatically run in GitHub Actions on push and PR.
