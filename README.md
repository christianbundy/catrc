# Concatenated Run Commands

A command-line interface for managing loosely coupled dotfiles.

## Installation

Download to your project directory, add `README.md`, and commit:

```sh
brew tap christianbundy/tap
brew install catrc
```

## Usage

1. Move your dotfiles to a directory in `~/.catrc` (we'll call this directory `dotfiles`).

    ``` shell
    mv ~/.vimrc ~/.catrc/dotfiles/
    ```
2. Run `catrc` to concatenate and symlink these to your home directory.

    ``` shell
    catrc
    ```

## Support

Please [open an issue](https://github.com/christianbundy/catrc/issues/new) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/christianbundy/catrc/compare/).
