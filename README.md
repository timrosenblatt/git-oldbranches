![Dead branches](https://upload.wikimedia.org/wikipedia/commons/b/be/Brennreisig.JPG)

# git-oldbranches
Extra git command for showing information about old branches.
Useful for easy cleanup of old branches.

## Installation
Just put this file in any location referenced in $PATH. Make sure it
has +x permission if you copy-paste the command there.

Fun fact: any executable file in your $PATH named `git-anything` will add
`anything` as a custom command available to git. Way more powerful than
just a git alias.

## Usage
Run `git oldbranches` in any repo and it will print a list of all the
local branches, along with information about the last commit, sorted by
date of last commit.
