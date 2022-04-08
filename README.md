# dotfiles
Random dotfiles dropped here

To apply the kde dotfiles:
compress the folder and replace the extension with ".knsv"

## Acer S3: (Arch + KDE) setup
![Screenshot_20220408_181949](https://user-images.githubusercontent.com/49370656/162483328-4bdd4204-dd3a-4f52-9eb0-7358618fc63d.png)

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
