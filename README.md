# Githooks

This repo offers two githooks

- `commit-msg` adds the branch name as a prefix to all commits.
- `pre-commit` runs black and flake8, with settings appropriate for SWAUTO software stack.

# Installation

Installation can be carried out via `core.hooksPath`.

For example, your `.gitconfig` file could look something like

```
[core]
  pager =
  excludesfile = /Users/sfrench/.gitignore_global
  editor = emacs
  hooksPath = ~/githooks
[user]
  email = joe.joe@gmail.com
  name = Joe Joe
[init]
  defaultBranch = main
[push]
  autoSetupRemote = true
```
