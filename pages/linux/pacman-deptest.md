# pacman --deptest

> Arch Linux package manager utility.
> More information: <https://man.archlinux.org/man/pacman.8>.

- Display help:

`pacman --deptest --help`

- List not installed packages:

`pacman --deptest {{package_name1}} {{package_name2}}`

- Check if the installed package satisfy the minimum version:

`pacman --deptest "{{bash>=5}}"`

- Check if a later version of a package is installed:

`pacman --deptest "{{bash>5}}"`
