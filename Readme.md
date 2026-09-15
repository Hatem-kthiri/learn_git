# Git Workflow Checkpoint

## 📌 About This Checkpoint

This checkpoint is designed to practice the **basic Git workflow** by creating a repository, adding and removing files, making commits, and checking the commit history.

It also introduces basic **global Git configuration** commands.

## 🎯 Objectives

By completing this checkpoint, I practiced how to:

* Create a project folder
* Initialize a Git repository
* Create files
* Add files to the staging area
* Commit changes
* Check the commit history
* Remove files and commit the changes
* Configure Git globally
* Display global Git configurations
* Push project screenshots to GitHub

## 🛠️ Steps Completed

### 1. Create the project folder

```bash
mkdir learn_git
```

### 2. Enter the folder

```bash
cd learn_git
```

### 3. Create `third.txt`

```bash
touch third.txt
```

### 4. Initialize the Git repository

```bash
git init
```

### 5. Add `third.txt` to the staging area

```bash
git add third.txt
```

### 6. Commit the file

```bash
git commit -m "adding third.txt"
```

### 7. Check the commit history

```bash
git log
```

### 8. Create `fourth.txt`

```bash
touch fourth.txt
```

### 9. Add `fourth.txt` to the staging area

```bash
git add fourth.txt
```

### 10. Commit the new file

```bash
git commit -m "adding fourth.txt"
```

### 11. Remove `third.txt`

```bash
rm third.txt
```

### 12. Add the change to the staging area

```bash
git add .
```

### 13. Commit the removal

```bash
git commit -m "removing third.txt"
```

### 14. Check the commit history

```bash
git log
```

### 15. Change the global Git pager

```bash
git config --global core.pager cat
```

### 16. List all global Git configurations

```bash
git config --global --list
```

### 17. Check Git global configuration options

```bash
git config --global
```

## 📸 Screenshots

Screenshots were taken during the different steps of the Git workflow and added to this repository as required by the checkpoint.

The screenshots demonstrate:

* Git repository initialization
* Adding files to the staging area
* Creating commits
* Viewing commit history
* Removing a file
* Git global configuration

## 📚 What I Learned

Through this checkpoint, I practiced the main Git workflow:

```text
Create / Modify Files
        ↓
   git add
        ↓
   Staging Area
        ↓
  git commit
        ↓
  Git History
        ↓
    git log
```

I also learned how to configure Git globally and check the configuration settings on my machine.

## ✅ Conclusion

This checkpoint helped me become more comfortable with the basic Git commands and understand how changes move from the working directory to the staging area and finally into the Git repository.
