# git-rebase-101
---

Try to more understand git rebase and git rewriting history


### git commit --amend

- fix up the most recent commit (combine + edit previous commit).

Before `--amend`

```
96b1f6b just a simple commit
6c7ee98 modify README.md before --amend
ff18554 Initial commit
```

After `--amend`

```
ad55d01 try to add message with --amend
6c7ee98 modify README.md before --amend
ff18554 Initial commit
```

### Merge vs Rebase

- never use `rebase` on public branches.