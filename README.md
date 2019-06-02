# M2R: Ramsey Theory

Project folder for the second year group research project on Ramsey Theory.

## Contents

1. [Using Git](#using-git)
1. [Compiling LaTeX](#compiling-latex)


## Using Git

Git is a version control system that allows many people to edit a project
simultaneously.
One advantage of using git is that it is device independent and will run on any 
modern operating system.
Another is that it allows files to be edited offline and saved to a repository
at a later time.
This is a short guide on how to get git set up for this project, as well as how
to save your changes and send them back to the repository.
If you'd rather read through the official documentation, you can find that
[here](https://git-scm.com/doc).

To begin with you'll want to download a GUI git client from
[this](https://git-scm.com/downloads/guis) list.
I'd personally recommend gitkraken, which is free for our use-case.
Once you've got a git client installed, you'll need to create a GitHub account.
This is so I can grant you push access to this repository.
You can do that [here](https://github.com/join?source=header-home).
Again, for our purposes you only need a free account.

If you're using gitkraken, you should be able to log into GitHub/GitLab from the
program and it should display a list of *remote* repositories.
This repository will be among these and you should be able to download(pull) it directly
from the app.

If you're not then, depending on the client, there might be an option to pull a
remote repository.
If there is an option to use HTTPS or SSH, select HTTPS and use
`https://github.com/QuantumAnon/m2r.git` as the repository URL.
It will then ask you to authenticate using your username and password.
Some clients will pull the files from the remote repository automatically, but
others will need you to manually pull them.

## Compiling LaTeX

Each of the projects should contain a `.latexmkrc` file and a GNU makefile.
The makefile specifies what the sources and targets are for compilation and the
latexmkrc contains the compilation command that should be used.
Any special instructions are noted below.

### [Introductions](./intros)

This uses `lualatex` to compile.
