[Home](../index.md)/[Github](./index.md)
# Commands

This section describes a list of usefull commands.  
You can get more information at [Book](https://git-scm.com/book/en/v2)

## Configure git

Run the following command to set the username and email address.

```bash
git config --global user.name "your-username"
git config --global user.email "your-email"
```

## Clone a repository

The following command will get the repository form a remote server.  

```bash
git clone https://github.com/Caracal-IT/vault.git
```

## Initialize repository

A git repository must be initialized before you can use it.

```bash
git init
```

## Commit Changes

This is a two step process.  
1. Add the files.  
2. Commit the changes.

```bash
git add myfile.txt myfile2.txt
git add . 
git commit
```

## Status of repository

The following command gill get the status of the repository.

```bash
git status
```

## History of commits

Run the following command to get the history of all the commits.  

```bash
git log
```

## Move to a previous commit

Use the following command to move to a previous commit. 
The code will be disconnected from a branch. 

```bash
git checkout 5092231180ed860ef800ace313ff80de39310c53
```

Type the following command to return to the branch.  

```bash
git checkout main
```
