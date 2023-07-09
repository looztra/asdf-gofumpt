<div align="center">

# asdf-gofumpt [![Build](https://github.com/looztra/asdf-gofumpt/actions/workflows/build.yml/badge.svg)](https://github.com/looztra/asdf-gofumpt/actions/workflows/build.yml) [![Lint](https://github.com/looztra/asdf-gofumpt/actions/workflows/lint.yml/badge.svg)](https://github.com/looztra/asdf-gofumpt/actions/workflows/lint.yml)

[gofumpt](https://github.com/mvdan/gofumpt) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add gofumpt
# or
asdf plugin add gofumpt https://github.com/looztra/asdf-gofumpt.git
```

gofumpt:

```shell
# Show all installable versions
asdf list-all gofumpt

# Install specific version
asdf install gofumpt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gofumpt latest

# Now gofumpt commands are available
gofumpt --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/looztra/asdf-gofumpt/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Christophe Furmaniak](https://github.com/looztra/)
