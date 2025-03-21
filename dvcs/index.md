# Distributed Version Control with Git

## Installation
Using a Debian-based Linux distribution, type

```
sudo apt install git git-gui git-cola
```

to install git and two different GUI frontends. If you're on Windows,
download `git` from [git-scm.com](https://git-scm.com/download/win) (a
portable edition is available).

## Selected Commands

| Command | Explanation |
| ------- | ---------------------------------|
| `init` | create an empty Git repository or reinitialize an existing one |
| `status` | Show the working tree status |
| `add` | Add file contents to the index |
| `commit` | Record changes to the repository |
| `push` | Update remote refs along with associated objects |
| `diff` | Show changes between commits, commit and working tree, etc |
| `clone` | Clone a repository into a new directory |

## Generate SSH-key
ssh-keygen  
navigate to "/cygdrive/c/Users/[USERNAME]/.ssh"  
less id_rsa.pub  
copy key  
github profil -> settings -> SSH and GPG keys  
click on "New SSH key"  
paste key  
click on "Add SSH key"  

An excellent overview over the available git commands is available as
[git cheatsheet](https://ndpsoftware.com/git-cheatsheet.html).

## Branching Models
Which branching models is to be preferred depends on the needs of an
organization or of a development team. I genereally recommend to keep things
simple. Here are some of the most prevalent models:

* [GitHub flow](https://guides.github.com/introduction/flow/)
* [GitLab flow](https://docs.gitlab.com/ee/topics/gitlab_flow.html)
* [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
