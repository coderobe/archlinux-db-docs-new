
## pitfalls
repository directories cannot be empty when adding the first package
> add an empty .gitignore, see `community/.gitignore` in https://github.com/coderobe/archlinux-packages-x86_64-new

## add a package to the tracking repo
`git remote add -f $pkgname /path/to/$pkgname/.git`

`git subtree add --prefix $repo/$pkgname $pkgname master`
