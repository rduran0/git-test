# Git Operations Demo

A dummy project will be included here at some point. Meanwhile this is just meant to have this single file to demonstrate the use of git commands.

What you are currently seen is the initial version of this file. Through commits you'll see this file transform.

### Git commands involved

With each update, the text and content of this section will change.

### git commit

The command that actually records a point in the history. This can be used multiple ways

* Simple
```shell
git commit
```

* With a commit message (recommended)
```shell
git commit -m "This is a message to know what happened here"
```

* A commit including all of the unstaged changes
```shell
git commit -a
```

Note: when using argument -a, all new files won't be included unless these are staged with `git add` command.