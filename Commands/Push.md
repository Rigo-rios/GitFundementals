# git push 

when you have a [remote](./remote.md) set up you'll need to begin to move [commits](./commit.md) to the remote. This can be done with the command `git push`.

You can attach a name and branch name to your command to specify where you're pushing to.

```
git push origin main
```

This command will push the **main** branch to the remote called **origin**. This means any commits that are in your local will be **pushed**  to the remote.

### Upstream Tracking

instead of including the name of the remote and the branch you're on every time, you can set local branches to track an upstream branch. This means you can tell the branch to push to its assigned upstreams remote branch by ysing the command `git push`.

before doing so, you'll need to use the `-u` or `--set-upstream` flag. This can be done on any `git push`.

```
git push -u origin main
```

after this command is used, you csn just use the `git push` and it will funciton the same way.

## Resources

-[Git Push Documentation](htpps://git-scm.com/docs/git-push)

---

[Back to home](../Readme.md)