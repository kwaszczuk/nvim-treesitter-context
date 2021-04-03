# nvim-treesitter-context

Lightweight alternative to [context.vim](https://github.com/wellle/context.vim)
implemented with [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter).

## Install

```vim
Plug 'nvim-treesitter/nvim-treesitter'
Plug 'romgrk/nvim-treesitter-context'
```

## Screenshot

![theme](./static/demo.gif)

### Notes

This plugins uses the new neovim `WinScrolled` event when available to update its
context window. Make sure to have a recent neovim build to get this behavior. The fallback
behavior is to update its content on `CursorMoved`.

## Commands

`TSContextEnable` and `TSContextDisable`.

## Appearance

Use the highlight group `TreesitterContext` to change the colors of the
context. Per default it links to `NormalFloat`.
