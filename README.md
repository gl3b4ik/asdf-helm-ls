<div align="center">

# asdf-helm-ls [![Build](https://github.com/gl3b4ik/asdf-helm-ls/actions/workflows/build.yml/badge.svg)](https://github.com/gl3b4ik/asdf-helm-ls/actions/workflows/build.yml) [![Lint](https://github.com/gl3b4ik/asdf-helm-ls/actions/workflows/lint.yml/badge.svg)](https://github.com/gl3b4ik/asdf-helm-ls/actions/workflows/lint.yml)

[helm-ls](https://github.com/mrjosh/helm-ls) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add helm-ls https://github.com/gl3b4ik/asdf-helm-ls.git
```

helm-ls:

```shell
# Show all installable versions
asdf list-all helm-ls

# Install specific version
asdf install helm-ls latest

# Set a version globally (on your ~/.tool-versions file)
asdf global helm-ls latest

# Now helm-ls commands are available
helm_ls version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.


