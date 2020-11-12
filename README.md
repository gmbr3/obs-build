
This repository provides `build` tool to build binary packages in a
a safe and reproducible way. The default is to build in a chroot
sandbox, but it also
supports building in a virtual machine for better security.

The `build` tool can work with multiple package and recipe formats.
The currently supported package formats are `deb`, `rpm`, and `arch`.
The supported recipe formats are `spec`, `dsc`, `kiwi`, and `PKGBUILD`.

See [the man page](https://manpages.debian.org/buster/obs-build/obs-build.1.en.html)
for more information.

