<p align="center"><img src="https://voyager.postman.com/logo/postman-logo-icon-orange.svg" alt="Postman" width=128 height=128></p>
<h2 align="center">Postman AppImage</h2>
<p align="center">Unofficial / Community provided Postman AppImage - stable release</p>

[![Postman AppImage release](https://github.com/valicm/Postman-AppImage/actions/workflows/release.yml/badge.svg?branch=main)](https://github.com/valicm/Postman-AppImage/actions/workflows/release.yml)

## Get Started

#### [Download the latest release](https://github.com/valicm/Postman-AppImage/releases/latest)
- stable release only
- supports update of the AppImage

### Executing
#### File Manager
Double-click the `*.AppImage` file and you are done!

> In normal cases, the above method should work, but in some cases you 
> need mark file as executable. You can do this using File manager -> right click > Properties > Allow Execution,
> or by terminal issuing command `chmod +x Postman-*.AppImage`

#### AppImageLauncher
Use AppImageLauncher for better desktop integration ==> [download AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher)

#### Terminal
```bash
chmod +x Postman-*.AppImage
./Postman-*.AppImage
```

#### Build
The AppImage is built from .tar.gz Postman package by GitHub Continuous Integration using this
bash script https://github.com/valicm/appimage-bash.
