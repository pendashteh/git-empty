# git-empty
A git plugin to create an empty git repository

# Usage
```
$ git empty

Initialized empty Git repository in /path/to/here/.git/
[master (root-commit) dd22b2e] Empty.                                                                                                                                                                         
```
Now you have a git repository with a valid branch which contains nothing.

# Why?
## Isn't this what `git init` does?
No, it's not. `git init` doesn't create a branch and you still need to make a commit to have a branch.

## Ok, got it, what is the usecase?
It is a good practice to start a repository with a blank first commit. 

# Install
Add `git-empty` to your `$PATH` and now you can run `git empty` as a git subcommand.

This is how you can write a subcommand of your own. Anything in `$PATH` prefixed with `git-` will become a git subcommand.
