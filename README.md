Jellybeans2-nvim: A modified version of jellybeans-nvim
===

**NOTE: This fork has not changed much of jellybeans-nvim**
Please check out the [original colorscheme](github.com/metalelf0/jellybeans-nvim)

Main Differences
===
- Identifiers (i.e. variables) now use the foreground color,
  to avoid over-coloring code.


*NOTE: Colors may differ from screenshot!!!*
![Screenshot](scrot.png)

Instructions
---

**Note**: This colorscheme requires at least Neovim 0.5 (it works fine on current master).

```lua
require('packer').startup(function(use)
  -- ...
  use 'rktjmp/lush.nvim'
  use 'obwan02/jellybeans2-nvim'

end)

cmd('colorscheme jellybeans2-nvim')
```

Notes
---

* this was built with [lush.nvim](http://git.io/lush.nvim); for more
  information on Lush and a helper script to setup your repo clone.
