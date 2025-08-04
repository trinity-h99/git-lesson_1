## Git Lesson

The lesson covers the basics of the version control

This is part of the first lesson for Chem 280

To make a commit (or "version" or "checkpoint") of your project, folow this procedure

1. make changes to your project that you would like to keep
2. When you have your changes, tell git you are ready to create a checkpoint of the files using the `git add` command and list the files
3. Creat a checkpoint using `git commit -m "message about what you did"`

## Adding Features
Features should be developed on branches. To create and switch to a branch, use the command:

```
git switch -c new_branch_name
```

to switch to an existing branch, use

```
git switch existing_branch_name
```