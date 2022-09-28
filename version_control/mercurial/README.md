# Config

See [hgrc](/version_control/mercurial/hgrc) file.

# Cheatsheet

Interactive staging and commit :
```
hg commit -i
```
## Rewriting history

Amend last commit :
```
hg commit --amend
```

Undo last commit and keep changes :
```
hg strip --keep --rev .
```

Rebase branch :
```
hg rebase --source <REV> --dest <REV>
```
