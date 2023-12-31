# asdf-gofumpt

[![Build](https://github.com/looztra/asdf-gofumpt/actions/workflows/build.yml/badge.svg)](https://github.com/looztra/asdf-gofumpt/actions/workflows/build.yml)
[![Lint](https://github.com/looztra/asdf-gofumpt/actions/workflows/lint.yml/badge.svg)](https://github.com/looztra/asdf-gofumpt/actions/workflows/lint.yml)

[gofumpt](https://github.com/mvdan/gofumpt) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

## Contents

- [asdf-gofumpt](#asdf-gofumpt)
  - [Contents](#contents)
  - [Dependencies](#dependencies)
  - [Install](#install)
  - [Contributing](#contributing)
  - [License](#license)

## Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `GITUB_TOKEN` set this environment variable (must be a valid [Personal Access Token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens)) in your shell config to load the correct version of tool x.

## Install

Plugin:

```shell
asdf plugin add gofumpt
# or
asdf plugin add gofumpt https://github.com/looztra/asdf-gofumpt.git
```

gofumpt:

```shell
# Show all installable versions
asdf list all gofumpt

# Install specific version
asdf install gofumpt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gofumpt latest

# Now gofumpt commands are available
gofumpt --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

## Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/looztra/asdf-gofumpt/graphs/contributors)!

## License

See [LICENSE](LICENSE) © [Christophe Furmaniak](https://github.com/looztra/)
