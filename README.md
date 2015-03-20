# git-tools

Copy files to a directory that is inside your path and make sure they are executable. Open new shell and they are available as git commands.

## Show unpushed branches

```
zoidberg@futurama:data (feature-xyz)$ git unpushed
6c3102c (HEAD, feature-packagesbundles) newline removed
```

## Iterate over all .git subdirs and do something

```
git forall log --oneline
6c3102c (HEAD, feature-packagesbundles) newline removed
```
