# My zsh functions
nothing special.
`proj` makes use of [`xproj`](https://github.com/msp729/xproj) for its listings, because i wanted non-trivial formatting and doing logic in bash is a form of torture.

```zsh
fpath+={path to repo}/zsh
autoload -Uz proj
source {path to repo}/zsh/_proj
```
