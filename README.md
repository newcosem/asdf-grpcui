<div align="center">

# asdf-grpcui [![Build](https://github.com/newcosem/asdf-grpcui/actions/workflows/build.yml/badge.svg)](https://github.com/newcosem/asdf-grpcui/actions/workflows/build.yml) [![Lint](https://github.com/newcosem/asdf-grpcui/actions/workflows/lint.yml/badge.svg)](https://github.com/newcosem/asdf-grpcui/actions/workflows/lint.yml)

[grpcui](https://github.com/fullstorydev/grpcui) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add grpcui
# or
asdf plugin add grpcui https://github.com/newcosem/asdf-grpcui.git
```

grpcui:

```shell
# Show all installable versions
asdf list-all grpcui

# Install specific version
asdf install grpcui latest

# Set a version globally (on your ~/.tool-versions file)
asdf global grpcui latest

# Now grpcui commands are available
grpcui -help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/newcosem/asdf-grpcui/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Alan Doherty](https://github.com/newcosem/)
