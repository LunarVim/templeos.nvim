![templeos](https://user-images.githubusercontent.com/29136904/192857917-b9782639-15a5-4f2d-afe1-35319602d198.png)

## Showcase

![1](https://raw.githubusercontent.com/ysfgrgO7/lvim-templeos_scorts/main/scrot1.png) 
![2](https://raw.githubusercontent.com/ysfgrgO7/lvim-templeos_scorts/main/scrot2.png) 
![3](https://raw.githubusercontent.com/ysfgrgO7/lvim-templeos_scorts/main/scrot3.png) 
![4](https://raw.githubusercontent.com/ysfgrgO7/lvim-templeos_scorts/main/scrot4.png) 
![5](https://raw.githubusercontent.com/ysfgrgO7/lvim-templeos_scorts/main/scrot5.png)

## Installation

> Using [Packer](https://github.com/wbthomason/packer.nvim)

```lua
use "lunarvim/templeos.nvim"
```

> Using [LunarVim](https://github.com/LunarVim/LunarVim) `config.lua`

```lua
lvim.plugins = {
  "lunarvim/templeos.nvim"
}
```

## Activate

> Using your `init.lua`

```lua
vim.cmd("colorscheme templeos")
```

> Using [LunarVim](https://github.com/LunarVim/LunarVim) `config.lua`

```lua
lvim.colorscheme = "templeos"
```

## Font installation

> **Note**
> To make this colorscheme fully immersive you must use the recommended font!

- [Download](https://github.com/LunarVim/templeos.nvim/raw/master/templeos_font.ttf) the font or get it from the [root](./templeos_font.ttf) of this repository

> on Linux

- Move or copy the file to your fonts directory

  ```bash
  mv templeos_font.ttf ~/.local/share/fonts
  ```

- Run this to rebuild your font cache. [Learn more](https://www.geeksforgeeks.org/fc-cache-command-in-linux-with-examples/)

  ```bash
  fc-cache -f -v
  ```

- Set your terminal font to `TempleOS`

> on Windows

- Double click on the `templeos_font.tff` file

- Click Install

- Set your terminal font to `TempleOS`