# git-difftex

## Use this script anywhere

1. Put git-difftex where you keep your globally accessible custom scripts, e.g. on a mac: `/Users/yourName/bin/` or on ubuntu: `~/.local/bin`. Alternatively, you can create a custom bin, e.g. `~/customBin`

2. If placing into a custom bin be sure to add the path to `customBin` to `.bash_profile` (mac) or `.bashrc` (ubuntu):

```
open ~/.bash_profile
export PATH=~/customBin:$PATH
```

or equivalently:

```
export PATH=$PATH:/Users/yourName/bin
```
