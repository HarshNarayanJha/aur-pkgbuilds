# aur-pkgbuilds

Contains all the [AUR](https://aur.archlinux.org/) pkgbuilds that I maintain.

## Maintainance

I use `aurpublish` to make changes to the aur packages while keeping all of them under a single repo on GitHub.

To pull a new package that I maintain
```
aurpublish -p new_pkgbase
```

To push to aur after changes
```
aurpublish new_pkgbase
```

git hooks takes care of formatting errors, .SRCINFO and commit messages
