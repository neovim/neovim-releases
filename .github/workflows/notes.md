```
${NVIM_VERSION}
```

## Install

### Linux (x64)
#### AppImage
1. Download **nvim.appimage**
2. Run `chmod u+x nvim.appimage && ./nvim.appimage`
   - If your system does not have FUSE you can [extract the appimage](https://github.com/AppImage/AppImageKit/wiki/FUSE#type-2-appimage):
     ```
     ./nvim.appimage --appimage-extract
     ./squashfs-root/usr/bin/nvim
     ```

#### Tarball

1. Download **nvim-linux64.tar.gz**
2. Extract: `tar xzvf nvim-linux64.tar.gz`
3. Run `./nvim-linux64/bin/nvim`

#### Debian Package

1. Download **nvim-linux64.deb**
2. Install the package using `sudo apt install ./nvim-linux64.deb`
3. Run `nvim`
