# dotfiles
Random dotfiles dropped here

To apply the kde dotfiles:
compress the folder and replace the extension with ".knsv"

Then install the following
### Arch
Requires the AUR helper _yay_ to be installed
```bash
# install konsave
yay -S konsave

# applly the theme
cd _dotfilesrepo_

# Import .knsv file
konsave -i kde_acerS3.knsv

# apply theme
konsave -a kde_acerS3
```
