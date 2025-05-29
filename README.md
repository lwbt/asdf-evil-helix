<div align="center">

# asdf-evil-helix

[helix](https://helix-editor.com/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Note

I couldn't find a plugin for this version of Helix.
So I made one.
I have no experience with ASDF, but I know shell scripts.
If it works for you, great.
If it doesn't work for you, or it stops working, well I'm sorry.

Intended usage:

```bash
mise plugins add --force https://github.com/lwbt/asdf-evil-helix
mise use -g evil-helix
```

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
asdf plugin add helix
# or
asdf plugin add helix https://github.com/CSergienko/asdf-helix.git
```

helix:

```shell
# Show all installable versions
asdf list-all helix

# Install specific version
asdf install helix latest

# Set a version globally (on your ~/.tool-versions file)
asdf global helix latest

# Now helix commands are available
hx --version
hx --health
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/CSergienko/asdf-helix/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Chris Sergienko](https://github.com/CSergienko/)
