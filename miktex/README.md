# Reasoning

Arch removed the `libjpeg` alias of the dependency `libjpeg-turbo` in [#a0e534d2](https://gitlab.archlinux.org/archlinux/packaging/packages/libjpeg-turbo/-/commit/a0e534d2803d7561c791ab5cd7f1a6f496d0cfaa).  
The name of the dependency is updated in the `PKGBUILD`.

# Using

`repo.patch` contains the alterations to the AUR-repo required to use this patch.  
`PKGBUILD` already has the patch applied.
