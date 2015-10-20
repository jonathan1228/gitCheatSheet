## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - View file differences not yet staged

#### Repo History
`$ git log` - Lists version history for current branch

`$ git log --oneline --decorate --color --graph --all` - makes log more easily legible, all parameters customizable and affect different aspects of log  

`$ git log -p [filename]` Shows history of commits associated with file and what was changed/made within them

#### Stage files to commit
`$ git add <filename>` - add file contents to index

`$ git add -A` - adds everything in current path

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - Record changes to the repository along with a message to describe the change.dq
#### Branching
`$ git branch <branch name>` - Creates a copy of the master branch with the given name.

`$ git branch` - List, create, or delete branches

`$ git checkout <branch name>` - Switch branches or restore working tree files.

#### Merging

`$ git merge <branch name>` - Join two or more development histories together.