# Git lesson

This lesson covers basics of version control

This is part of the first lesson of CHEM 280

To make make commit follow this procedure:

1. Make changes to project you would like to keep
2. When you have your chnages, tell git you are ready to make a checkpoint by using `git add` and the name of the file you wish to track
3. Create the actual checkpoint by using `git commit -m "message about what you did"`

## Adding features
Features should be developed on branches. 

To create and switch to a branch, use the command:

```
git switch -c new_branch_name
```

To switch to an existing branch use,

```
git switch existing_branch_name
```
Use the same procedures to create a commit in order to create a check point for the branches

