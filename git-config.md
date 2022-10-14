
# Git Config - Useful Commands
[![My Skills](https://skillicons.dev/icons?i=git)](https://skillicons.dev)  
Understanding ``git config`` , setting it up names, default editor and some useful commands to use with new machines or when switching accounts.

## Config Scopes

`` system > global > local ``

Global file, will affect all projects using git.
```bash
  git config --global 
```
System file, will prioritize the configs in the initialization.
```bash
  git config --system 
```
Local file, will affect only the repository that you're working with.
```bash
  git config --local
```
## Setting up a default branch

```bash
  git config --global init.defaultBranch <branch>
```

## Name and email of commits
```bash
    git config --global user.name '<name>'
```
```bash
    git config --global user.email '<email>'
```

## Default Editor

```bash
    git config --global core.editor <editor>
```

## See all local configs

```bash
    git config -l

    git config --list
```