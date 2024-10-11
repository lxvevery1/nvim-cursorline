# nvim-cursorline

Highlight words and lines on the cursor for Neovim

- Underlines the word under the cursor.

https://user-images.githubusercontent.com/42740055/163586251-15c7c709-86bd-4c17-a298-07681bada220.mp4

- Show / hide cursorline in connection with cursor moving.

https://user-images.githubusercontent.com/42740055/163586272-17560f83-9195-4cb4-8c1c-557cfaf775ea.mp4

## Installation

### Lazy.nvim


```lua
{
    "lxvevery1/nvim-cursorline",
}
```

```

## Configuration options

```lua
{
  cursorline = {
    enable = true,
    timeout = 1000,
    number = false,
  },
  cursorword = {
    enable = true,
    timeout = 1000,         -- <-- this thing is added
    min_length = 3,
    hl = { underline = true },
  }
}
```

## License

This software is released under the MIT License, see LICENSE.
