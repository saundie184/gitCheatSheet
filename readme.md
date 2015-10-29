## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - Show changes between commits, commit and working tree

#### Repo History
`$ git log` - Show commit logs

`$ git log --oneline --decorate --color --graph --all` - Shortcuts for displaying log formats

`$ git log -p [filename]` - Shows git log with file contents visible

#### Stage files to commit
`$ git add <filename>` - Add file contents to the index

`$ git add -A` - Adds all files' contents to the index

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - __Fill Me Out__

#### Branching
`$ git branch <branch name>` - __Fill Me Out__

`$ git branch` - __Fill Me Out__

`$ git checkout <branch name>` - __Switch branches or restore working tree files__

#### Merging

`$ git merge <branch name>` - __Join two or more development histories together__
