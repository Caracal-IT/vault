[Home](../index.md)/[Github](./index.md)
# Commands

This section describes a list of usefull commands.  

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



