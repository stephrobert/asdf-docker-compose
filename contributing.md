# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test docker-compose https://github.com/stephrobert/asdf-docker-compose.git "docker-compose --help"
```

Tests are automatically run in GitHub Actions on push and PR.
