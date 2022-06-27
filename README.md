# Lua NVIM Config
Still a work in progress.   
Working off this playlist: https://youtube.com/playlist?list=PLhoH5vyxr6Qq41NFL4GvhFp-WLd5xzIzZ

# Setup
## Linux Systems
* Get the current version of NeoVim by following the instructions in the `NeoVim Version` section.
* 
# NeoVim Version
Some plugins require neovim ver. 0.7.0 or higher. To get newest version:
* Download the appimage for the newest version [here](https://github.com/neovim/neovim/releases)
* Make it executable with `chmod +x nvim.appimage`
* Add it to your path with `sudo mv neovim.appimage /usr/local/bin/nvim`

# Issues
2/16/21 [RESOLVED]: The autocommand to download packer does not seem to be working  
Use this command to fix it:
```
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
 ```
