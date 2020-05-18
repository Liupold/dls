# dls
dotfiles linker (similar to stow, written in POSIX compatible script and with overwrite options)


``` console
dls (dotfiles linking script) (compatible with GNU stow)
POSIX compatible script. requirement: find, ls, ln

SYNOPSIS:

dls [OPTION ...] [-D|-S|-R] PKG ... [-D|-S|-R] PKG ...

OPTIONS:

    -v  --verbose             verbose (print what is happening)
    -n  --simulate            Run in dry mode (do not change anything in file system)
    -f  --overwrite--files    Overwrite any file (no symbolic link or dir) (be careful)
    -b  --overwrite--broken   Overwrite broken symbolic link
    -l  --overwrite-link      Overwrite any symbolic link (foreign symbolic link)
    -h  --help                Print this helpful message. (hopefully)
    -t DIR --target DIR       Change the Target dir.
    -S PKG --link PKG         link the Package. (stow -S like)
    -D PKG --delete PKG       UN link the Package. (stow -D like)
    -R PKG --re-link PKG      Re link the Package. (stow -R like)

author: liupold <rohn.ch@gmail.com>
```
