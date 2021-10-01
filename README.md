# vim-config
Base setup for **nvim**, with a bunch of preinstlaled plugins.

# Installation
Clone this repo inside the `~/.config` folder.
```
cd ~/.config
git clone https://github.com/vicmars5/vim-config
mv nvim nvim-bk # We rename the old nvim folder
mv vim-config nvim # and replace it with this repo
cd nvim
git submodule init
git submodule udpate
```

## Add new plugins

``` sh
git submodule add $REPO_URL bundle/$REPO_NAME
```
