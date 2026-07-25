```
${NVIM_VERSION}
```

## Install

Two builds per architecture:

- `nvim-linux-{x86_64,arm64}.{tar.gz,appimage,deb}` -- bundled with LuaJIT `${LUAJIT_VERSION}`
- `nvim-linux-{x86_64,arm64}-puc.{tar.gz,appimage,deb}` -- bundled with PUC-Rio Lua `${LUA_VERSION}`

### Linux (x86_64)
#### AppImage
1. Download **nvim-linux-x86_64.appimage**
2. Run `chmod u+x nvim-linux-x86_64.appimage && ./nvim-linux-x86_64.appimage`
   - If your system does not have FUSE you can [extract the appimage](https://github.com/AppImage/AppImageKit/wiki/FUSE#type-2-appimage):
     ```
     ./nvim-linux-x86_64.appimage --appimage-extract
     ./squashfs-root/usr/bin/nvim
     ```

#### Tarball

1. Download **nvim-linux-x86_64.tar.gz**
2. Extract: `tar xzvf nvim-linux-x86_64.tar.gz`
3. Run `./nvim-linux-x86_64/bin/nvim`

#### Debian Package

1. Download **nvim-linux-x86_64.deb**
2. Install the package using `sudo apt install ./nvim-linux-x86_64.deb`
3. Run `nvim`

### Linux (arm64)
#### AppImage

1. Download **nvim-linux-arm64.appimage**
2. Run `chmod u+x nvim-linux-arm64.appimage && ./nvim-linux-arm64.appimage`
   - If your system does not have FUSE you can [extract the appimage](https://github.com/AppImage/AppImageKit/wiki/FUSE#type-2-appimage):
     ```
     ./nvim-linux-arm64.appimage --appimage-extract
     ./squashfs-root/usr/bin/nvim
     ```

#### Tarball

1. Download **nvim-linux-arm64.tar.gz**
2. Extract: `tar xzvf nvim-linux-arm64.tar.gz`
3. Run `./nvim-linux-arm64/bin/nvim`

#### Debian Package

1. Download **nvim-linux-arm64.deb**
2. Install the package using `sudo apt install ./nvim-linux-arm64.deb`
3. Run `nvim`
