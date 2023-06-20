<div align="center">

# asdf-jira-cli [![Build](https://github.com/mrWinston/asdf-jira-cli/actions/workflows/build.yml/badge.svg)](https://github.com/mrWinston/asdf-jira-cli/actions/workflows/build.yml) [![Lint](https://github.com/mrWinston/asdf-jira-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/mrWinston/asdf-jira-cli/actions/workflows/lint.yml)

[jira-cli](https://github.com/ankitpokhrel/jira-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add jira-cli
# or
asdf plugin add jira-cli https://github.com/mrWinston/asdf-jira-cli.git
```

jira-cli:

```shell
# Show all installable versions
asdf list-all jira-cli

# Install specific version
asdf install jira-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global jira-cli latest

# Now jira-cli commands are available
jira version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrWinston/asdf-jira-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Marius Schulz](https://github.com/mrWinston/)
