# Lua NVIM Config
Still a work in progress.   
Working off this playlist: https://youtube.com/playlist?list=PLhoH5vyxr6Qq41NFL4GvhFp-WLd5xzIzZ

# Setup
## Linux Systems
* Get the current version of NeoVim by following the instructions in the `NeoVim Version` section.
* Clone the repository into the `.config` directory
  * If there is already an `nvim` directory in your `.config` directory, you need to rename it or delete it first.
* Open NeoVim with `nvim` and ignore any errors you get about missing packages.
* Packer will start and dowload any missing packages
* Close and reopen NeoVim after installs complete.

# NeoVim Version
Some plugins require neovim ver. 0.7.0 or higher. To get newest version:
* Download the appimage for the newest version [here](https://github.com/neovim/neovim/releases)
* Make it executable with `chmod +x nvim.appimage`
* Add it to your path with `sudo mv nvim.appimage /usr/local/bin/nvim`

# Important Shortcuts (other than regular vim shortcuts)
* gl: get error info (have to be on line with the error)
* <space>e: open file explorer

# Issues
2/16/21 [RESOLVED]: The autocommand to download packer does not seem to be working  
Use this command to fix it:
```
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
 ```
