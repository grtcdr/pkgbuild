# grtcdr/pkgbuild

## Synopsis
This repository contains personal and forked
[PKGBUILD](https://wiki.archlinux.org/title/PKGBUILD) recipes.

Any forked recipes found herein will always be noted as such, and
their maintainer(s)/contributor(s) is/are attributed at the top of the
recipe.

To quickly see the maintainer(s)/contributor(s) of a given
`<PACKAGE>`, clone the repository, navigate inside and run the
following:

```bash
grep -E "^# (Maintainer|Contributor):" <PACKAGE>/PKGBUILD | sed -r "s/# //"
```

## Recipes
- [citron](citron/PKGBUILD)
- [emacs-git](emacs-git/PKGBUILD)

## Usage
> THESE RECIPES ARE PROVIDED WITHOUT WARRANTY OF ANY KIND.

1. Clone the repository.
2. Navigate to the directory which contains the package you'd like to install.
3. Run `makepkg -sci`.
4. Enjoy.
