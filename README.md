# talosctl-zsh-plugin

`talosctl-zsh-plugin` is plugin for [Talos Linux](https://www.talos.dev/v1.6/introduction/what-is-talos/).

## Installation

1. Clone the repository into a new directory called `talosctl`:

    ```shell
    git clone https://github.com/rusmephist/talosctl-zsh-plugin.git $ZSH_CUSTOM/plugins/talosctl
    ```

2. Add `talosctl` to your .zshrc file along with other plugins:

    ```zsh
    ...
    plugins=(git dnf terraform talosctl)
    ...
    ```

3. Reload shell

    ```shell
    exec $SHELL -l
    ```
