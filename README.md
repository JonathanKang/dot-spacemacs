# This is mainly used for manage my personal .spacemacs file using version control.

## How to Use This

- `git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d` and switch to `develop` branch
- `git clone git@github.com:JonathanKang/dot-spacemacs.git`
- At your home directory, run `ln -s /path/to/dot-spacemacs/dot-spacemacs .spacemacs`
- Setup other needed components by spacemacs

### Custom keybings

- `M-h/j/k/l` Select the window to the left/down/up/right of the current one.
- `M-b` Open shell in emacs.
- `Space b l` Open useful buffer list(basically only show opened files).
- `Space b L` Comparing with the above one, this also shows magit buffers.

### Setup other tools
#### markdown layer
- install vmd using npm `npm install vmd -g`
> To use vmd to preview markdown, use `, c P`
- `dnf install discount`
> so that we can preview it in the browser using `, c p`

#### ccls as lsp server
- [Install ccls](https://github.com/MaskRay/ccls/wiki/Getting-started)
