# Config

See [hgrc](/version_control/mercurial/hgrc) file.

# Cheatsheet

| Action | Command | Doc |
|-|-|-|
| hg bisect | `hg bisect [-gbsr] [-U] [-c CMD] [REV]` | https://www.selenic.com/mercurial/hg.1.html#bisect |

| Action | Command |
|-|-|
| Bisect - reset | hg bisect --reset |
| Bisect - mark revision as good | hg bisect --good [REV] |
| Bisect - mark revision as bad | hg bisect --bad [REV] |
| Bisect - skip current | hg bisect --reset |


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
