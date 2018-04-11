Device Tree Blob Overlay Configuration File System Control 
====================================================================================

Overview
------------------------------------------------------------------------------------

### Introduction

This is a repository for making dtbocfg control debian package.

dtbocfg is Device Tree Blob Overlay ConFiGuration file system.

For details of dtbocfg, please refer to following URL.

  * https://github.com/ikwzm/dtbocfg

Build Debian Package
------------------------------------------------------------------------------------

### Download repository

```console
shell$ git clone --recursive --depth=1 -b v0.0.5 git://github.com/ikwzm/dtbocfg-ctrl-dpkg
shell$ cd dtbocfg-ctrl-dpkg
```

### Build

```console
shell$ sudo debian/rules binary
    :
    :
    :
shell$ file ../dtbocfg-ctrl_0.0.5-1_all.deb 
../dtbocfg-ctrl_0.0.5-1_all.deb: Debian binary package (format 2.0)
```

