Here is the `commands.md` 

# Git Commands Cheat Sheet

## 1. Initial Setup

### Configure Git Username
`git config --global user.name "your_username"`

### Configure Git Email
`git config --global user.email "your_email@example.com"`

---

## 2. Creating a New Repository

### Initialize a New Git Repository
`git init`

---

## 3. Basic Git Workflow

### Check the Status of Your Repository
`git status`

### Add Files to the Staging Area
`git add <file_name>`

### Commit Changes to the Repository
`git commit -m "commit message"`

---

## 4. Working with Branches

### Create a New Branch
`git checkout -b <branch_name>`

### Switch to an Existing Branch
`git checkout <branch_name>`

### List All Branches
`git branch`

---

## 5. Working with Remote Repositories

### Add a Remote Repository
`git remote add origin <repository_url>`

### Push Changes to the Remote Repository
`git push origin <branch_name>`

### Pull Changes from the Remote Repository
`git pull origin <branch_name>`

---

## 6. Managing Files

### Move or Rename a File
`mv <old_file_name> <new_file_name>`

### Remove a File
`rm <file_name>`

### Remove a File from Staging but Keep It Locally
`git rm --cached <file_name>`

---

## 7. Viewing Commit History

### View Commit History in Detail
`git log`

### View Commit History as a Summary
`git log --oneline`

---

## 8. Undoing Changes

### Undo Changes to a Specific File
`git restore <file_name>`

### Remove a File from Staging Area
`git reset <file_name>`

---

## 9. Viewing Differences

### Compare Staged Changes with the Last Commit
`git diff --staged`

### Compare Working Directory Changes with the Last Commit
`git diff`

---

## 10. Collaborating with Others

### Clone a Remote Repository
`git clone <repository_url>`

### Merge a Branch into the Current Branch
`git merge <branch_name>`

---

## 11. Deleting Branches and Files

### Delete a Branch Locally
`git branch -d <branch_name>`

### Delete a File
`rm <file_name>`

