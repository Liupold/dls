# dls
dotfiles linker (similar to stow, written in POSIX compatible script and with overwrite options)


``` console
$ ./dls -h

dls (dotfiles linking script) (compatible with GNU stow)
POSIX compatible script. requirement: find, ls, ln

SYNOPSIS:

dls [OPTION ...] [-D|-S|-R] PKG ... [-D|-S|-R] PKG ...

OPTIONS:

    -v      verbose (print what is happening)
    -n      Run in dry mode (do not change anything in file system)
    -f      Overwrite any file (no symbolic link or dir) (be careful)
    -b      Overwrite broken symbolic link
    -l      Overwrite any symbolic link (foreign symbolic link)
    -h      Print this helpful message. (hopefully)
    -t DIR  Change the Target dir.
    -S PKG  link the Package. (stow -S like)
    -D PKG  UN link the Package. (stow -D like)
    -R PKG  Re link the Package. (stow -R like)
```
