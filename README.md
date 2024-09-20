# git-tools
this repository contains some utility scripts to make git life easier!

## Installation
Just clone this somewhere, register this to the `.bashrc` or `.profile` script by using the command:

```bash
source ~/path/to/folder/index.bash
```
That's it, enjoy!

## Usage
These are the commands added by this collection:
* `git publish`:
    This is a shorthand for pushing a new branch on the remote origin without the need of setting up the tracking manually
* `git superprune`:
    This tool removes all local branches and trackings of branches that have been removed from origin.\
    Please, note that this might be distructive, you may lose your progress if you had newer commits on the branch that have been removed on the remote.\
    If you are checked-out on a branch to be deleted, this tool will not be able to delete it.
* `git fix line-endings`
    This tool helps when dealing with hybrid linux/windows dev environments.\
    All files of the repository will be migrated to the `\\n` line endings.
* `git fix email-for-github`
    This script's job is to rebase the commits of a repository by changing a given email with another one.\
    This might be useful when you accidentaly exposed your private email on a public repository.\
    I didn't use this from a long time, i have no idea if this still works.


## License
See the [LICENSE file](./LICENSE)
