# Git for DevOps

This file contains essential Git commands and concepts learned during practice.

---

## 🏗️ Create and Initialize Repository

**Commands:**
- mkdir git  
- cd git  
- git init  

**Description:**  
Initializes a new Git repository in the folder.

---

## 📋 Check File Status

**Command:**  
- git status  

**Description:**  
Used to check the current state of files — whether they are untracked, staged, or committed.

---

## 📄 Create and Add Files

**Commands:**
- touch ahmad.txt  
- touch farhan.txt  
- git add ahmad.txt  
- git add farhan.txt  
- git status  

**Description:**  
Creates new files and adds them to the staging area so Git can track them.

---

## ❌ Unstage a File

**Commands:**
- git rm --cached farhan.txt  
- git status  

**Description:**  
Removes `farhan.txt` from the staging area (unstages the file).

---

## 💾 Commit Files

**Commands:**
- git commit -m "add the farhan and ahmad file to track"  
- git status  
- git log  

**Description:**  
Commits the staged files and saves their versions in Git history.

---

## 🔄 Restore Deleted Files

**Commands:**
- rm ahmad.txt  
- git restore ahmad.txt  

**Description:**  
If a file is deleted from the working directory, `git restore` can recover it from the last commit.

---

## 🧮 Add All Files

**Commands:**
- touch shoaib.txt  
- touch sohail.txt  
- git add .  
- git status  

**Description:**  
Adds all new or modified files in the current directory to the staging area.

---

## 🚫 Unstage All Files

**Commands:**
- git rm --cached .  
- git status  

**Description:**  
Unstages all files from the staging area.

---

## 💬 Commit Files Again

**Commands:**
- git commit -m "adding shoaib.txt"  
- git log  
- git status  

**Description:**  
Commits all staged changes with a descriptive message.

---

## 🌿 Branch Management

**Commands:**
- git branch  
- git branch -b dev  
- git checkout -b dev  
- git branch  

**Description:**  
Creates and switches to a new branch named `dev`.

---

## 🧠 View Commit History (Compact)

**Command:**  
- git log --oneline  

**Description:**  
Shows a summarized version of commit history.

---

## 🌐 Remote Repository Setup

**Commands:**
- git remote add origin git@github.com:muhammadshoaib7766/git-for-devops.git  
- git remote set-url origin git@github.com:muhammadshoaib7766/git-for-devops.git  
- git pull origin main  

**Description:**  
Links local repository to GitHub and pulls the latest changes.

---

## 🧩 Work with Branches and Merging

**Commands:**
- git branch  
- git checkout -b staging  
- git merge staging  

**Description:**  
Creates a staging branch and merges it into the main branch.

---

## ✍️ Modify and Recommit Files

**Commands:**
- vim shoaib.txt  
- git add shoaib.txt  
- git commit -m "added modified shoaib file"  
- git status  

**Description:**  
Modify a file, add changes, and commit them.

---

## 🆕 Add and Commit New Files

**Commands:**
- touch suleman.txt  
- git add suleman.txt  
- git commit -m "adding suleman"  

**Description:**  
Adds a new file and commits it.

---

## ♻️ Restore Deleted File Again

**Commands:**
- rm shoaib.txt  
- git restore shoaib.txt  

**Description:**  
Restores deleted file from previous commits.

---

## ⚙️ Configure Git Username and Email

**Commands:**
- git config --global user.name "shoaibi"  
- git config --global user.email "shoaib@gmail.com"  

**Description:**  
Sets the global username and email for commits.

---

✅ **End of Practice Session: Git for DevOps**
