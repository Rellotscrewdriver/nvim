# Introduction

Hello! This is my personal neovim configuration for Linux with various plugins configured. it evolves as I learn more about neovim and become more proficient in using neovim. <br />
I wouldn't recommend cloning this repo and replace your own config, especially on other platforms since some configs for only for linux! <br />
Good configurations are personal, built over time with a lot of polish.

# Install and setup

Just run install.sh to install it on linux(untested on other platforms)

# Plugins
<details><summary><b>List of plugins</b></summary>

| Plugin            | Usage          |
|-------------------|--------------- |
| [Packer](https://github.com/wbthomason/packer.nvim)      | Plugin Management         |
| [hrsh7th](https://github.com/hrsh7th) + [lspconfig](https://github.com/neovim/nvim-lspconfig)     | AutoCompletion         |
| [lspkind](https://github.com/onsails/lspkind.nvim)     | Icons for autocompletion         |
| [cmp_luasnip](https://github.com/saadparwaiz1/cmp_luasnip)    | Snippet autocompletion         |
| [null-ls](https://github.com/jose-elias-alvarez/null-ls.nvim)     | Spellcheck and Clang_check        |
| [bufferline](https://github.com/akinsho/bufferline.nvim) | buffer management |
| [Telescope](https://github.com/nvim-telescope/telescope.nvim) | for fuzzy finding files and projects|
| [Code Runner](https://github.com/CRAG666/code_runner.nvim)| for running one file code quickly |
| [Alpha](https://github.com/goolord/alpha-nvim)| for dashboard |
| [impatient](https://github.com/lewis6991/impatient.nvim) | for improving starting time |
| [Cmake-tools](https://github.com/Civitasv/cmake-tools.nvim) | for CMake integration |
| [Gitsigns](https://github.com/lewis6991/gitsigns.nvim) | for git integration|
| [nvim-notify](https://github.com/rcarriga/nvim-notify) | GUI notifications |
| [startuptime](https://github.com/dstein64/vim-startuptime) | checking startuptime|
| [symbols-outline](https://github.com/simrat39/symbols-outline.nvim) | symbols-outline |
| [Vimwiki](https://github.com/vimwiki/vimwiki)| vimwiki |
| [Neo-tree](https://github.com/nvim-neo-tree/neo-tree.nvim) | | 
aand many more!(you can just look at init.lua to see all the plugins)
</details>


# UI Demo
<details><summary><b>UI Demos</b></summary>

For more UI demos, check [here](https://github.com/Rellotscrewdriver/nvim/issues/1).

## Start screen with dashboard-nvim

<p align="center">
<img src="" width="800">
</p>

## File fuzzy finding using LeaderF

<p align="center">
<img src="" width="800">
</p>

## Code autocompletion with nvim-cmp

<p align="center">
<img src="" width="800">
</p>

## Git add, commit and push via fugitive.vim

<p align="center">
<img src="" width="800">
</p>

## Command-line autocompletion with wilder.nvim

<p align="center">
<img src="" width="800">
</p>

## Tags

<p align="center">
<img src="" width="800">
</p>

## Cursor jump via hop.nvim

Go to a string starting with `se`

<p align="center">
<img src="" width="800">
</p>

## GUI-style notification with nvim-notify

<p align="center">
<img src="" width="800">
</p>

# Contributing

If you find anything that needs improving, do not hesitate to point it out or create a PR.

If you still have an issue, [open a new issue](https://github.com/jdhao/nvim-config/issues).

# Credits

* [jdhao](https://github.com/jdhao/nvim-config) for inspiration to restart my neovim configuration from scratch



# Further readings
Some of the resources that I find helpful in mastering Nvim is documented [here]().


