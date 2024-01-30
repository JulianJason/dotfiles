## Jason's dotfiiles to sync configuration across different machines
---

Currently only tested on debian-flavored distros.


### The gitignore

My setup assumes that I git init and git pull from the user's home directory `~`, the wildcard will prevent accidentally adding personal files to this repo.

To add a file to be tracked by git, use the force flag

`git add -f .bash_aliases`
