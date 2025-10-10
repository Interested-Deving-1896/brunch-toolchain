# Building the toolchain

### Requirements

- root access.
- `coreutils` and `curl` packages.

## Getting the source

Clone the main branch and enter the source directory:

```
git clone -b main https://github.com/sebanc/brunch-toolchain.git brunch-toolchain
cd brunch-toolchain
```

## Building the toolchain.

To build the toolchain, you need to have root access and 10 GB of free disk space available.

1. Launch the build (as root):
```
sudo ./build.sh
```
3. Make yourself 100 coffees (the build will take several hours, it mostly depends on your cpu and hdd speed).

4. That's it. You should have a brunch toolchain archive in your current directory.

