# NeoVim how-to help docs and utilities

## Rationale

In order to increase the productivity using Vim, we usually tend to write some cheatsheets or notes and having them stored somewhere.

Why not having all your shorcuts, tips and tricks as help pages? So, in whatever project we are working on, we can type `:help howto-<tab>` and easily access to all our snippets, depending on the topic.

## Disclaimer

All the documentation in the help pages are referring not only to out-of-the-box Vim features but also to my actual NeoVim configuration you can see here: https://github.com/msaelices/nvim-python

If you are not using my exact configuration, some of the shortcuts mentioned there will not work to you. Please read the [Use it as a template](#use-it-as-a-template) section to adapt it to your needs.

## Installation

You can install `nvim-howto` with your favorite package manager, or using the default pack feature of Neovim!

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

## Use it as a template

To adapt this NeoVim plugin to your needs, you would need to:

1. Clone the Github repo.

2. Change the help documents below the `doc/` directory to fit your NeoVim config and plugins.

3. Recreate all the tags with `:helptags ~/path/to/your/repo/doc/`

4. Commit and push your changes

5. Install it following the above instructions but changing the plugin reference to `yourgithubuser/nvim-howto`

