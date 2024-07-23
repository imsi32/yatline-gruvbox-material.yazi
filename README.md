# yatline-gruvbox-material.yazi
Gruvbox Material theme for Yatline plugin. 

## Installation

### General
1) Download the repository.
2) If the directory is downloaded as zip file, extract it.
3) Rename the directory as `yatline-gruvbox-material.yazi`
4) Open the config directory of Yazi.
5) Copy this directory into `plugins` directory.
6) Create `init.lua` file in the main Yazi config directory.
7) Open this file and copy the config to that file.

### Linux
``` bash
git clone https://github.com/imsi32/yatline-gruvbox-material.yazi.git ~/.config/yazi/plugins/yatline-gruvbox-material.yazi
```

## Usage
Copy the following config to the `init.lua` file.
``` lua
local gruvbox_material_theme = require("yatline-gruvbox-material"):setup({ mode = "dark", toughness = "medium" }) -- or "light" -- or "hard" | "soft"
```
Then use the `theme` variable in Yatline config's theme paramater.
``` lua
require("yatline"):setup({
-- ===

	theme = gruvbox_material_theme,

-- ===
})
```

## Credits
- [Gruvbox Material Theme](https://github.com/sainnhe/gruvbox-material)
