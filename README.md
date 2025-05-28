# tmux-minimal

Minimal, productive `tmux` config for terminal-focused workflows.

## Features

- `M-x` as prefix
- Reload config: `Prefix + r`
- Vim-style nav/resizing
- Mouse + clipboard support (`xclip`)
- Clean status bar
- Truecolor
- TPM plugins:
  - `tpm`
  - `tmux-yank`
  - `vim-tmux-navigator`

## Install

```sh
git clone https://github.com/felixoakz/tmux-configs ~/.config/tmux
ln -s ~/.config/tmux/.tmux.conf ~/.tmux.conf

## Inside tmux, install plugins with:
$ <M-x> + I
