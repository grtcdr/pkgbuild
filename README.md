# grtcdr/pkgbuild

## Synopsis
This repository contains personal and forked [PKGBUILD](https://wiki.archlinux.org/title/PKGBUILD) recipes.

Any forked PKGBUILD recipes found herein will always be noted as such,
and their maintainer(s)/contributor(s) is/are attributed at the top of the PKGBUILD.

To quickly see the maintainer(s)/contributor(s) of a given `<PACKAGE>`'s PKGBUILD, run the following:
```bash
grep -E "^# (Maintainer|Contributor):" <PACKAGE>/PKGBUILD | sed -r "s/# //"
```

## Recipes
- [citron](citron/PKGBUILD)
- [emacs-git](emacs-git/PKGBUILD)

## Usage
> THESE RECIPES ARE PROVIDED WITHOUT WARRANTY OF ANY KIND.

1. Navigate to the directory which contains the package you'd like to install.
2. Run `makepkg -sci`.
3. Enjoy.
