# Luvbox Theme for Neovim

<!--![screenshot-01](./screenshots/01.png)-->
<!---->
<!--## Float Terminal-->
<!--![screenshot-02](./screenshots/02.png)-->
<!---->
<!--## Telescope Find Files-->
<!--![screenshot-03](./screenshots/03.png)-->
<!---->
<!--## Telescope Live Grep-->
<!--![screenshot-04](./screenshots/04.png)-->
<!---->
<!--## Telescope LSP References-->
<!--![screenshot-05](./screenshots/05.png)-->
<!---->
<!--## Telescope LSP Implementations-->
<!--![screenshot-06](./screenshots/06.png)-->

# Installation

Using [lazy.nvim](https://github.com/folke/lazy.nvim):

```lua
{
    "yakomisar/luvbox.nvim",
    lazy = false,
    priority = 1000,
    config = function()
        require("luvbox").setup({
            cursorline = true,
            transparent_background = false,
            nvim_tree_darker = true,
        })
        vim.cmd.colorscheme("luvbox")
    end,
}
```
