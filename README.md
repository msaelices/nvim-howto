# NeoVim how-to help docs and utilities

## Rationale

In order to increase the productivity using Vim, we usually tend to write some cheatsheets or notes and having them stored somewhere.

Why not having all your shorcuts, tips and tricks as help pages? So, in whatever project we are working on, we can type `:help howto-<tab>` and easily access to all our snippets, depending on the topic.

## Installation

You can install nvim-treesitter-textobjects with your favorite package manager, or using the default pack feature of Neovim!

### With Vim-plug

If you are using [vim-plug](https://github.com/junegunn/vim-plug), put this in your init.vim file:

```vim
Plug 'msaelices/nvim-howto'
```

### With Packer

```lua
use({
  "msaelices/nvim-howto"
})
```

### With Lazy.vim

```lua
{ "msaelices/nvim-howto" }
```
