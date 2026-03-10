# Git Assignment - HeroVired

## Project: CalculatorPlus

This repository demonstrates Git workflows including branching, pull requests, Git LFS, Git stash, and version releases.

---

# Q1: Calculator Application

A Python calculator application supporting the following operations:

- Addition
- Subtraction
- Multiplication
- Division
- Square Root

### Square Root Feature
Implemented using Python's `math` library.

### Bug Fix

The divide function was updated to prevent division by zero.

Example:

def divide(self, a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero.")
    return a / b

---

# Git Branch Workflow

Branches used in this project:

- main
- dev
- feature/sqrt
- lfs
- geometry-calculator
- feature/circle-area
- feature/rectangle-area

Development workflow followed:

1. Code added to **dev branch**
2. Feature developed in **feature/sqrt branch**
3. Pull request created
4. Feature merged into **dev**
5. Final code merged into **main**

---

# Release Versions

Version tags created:

- v1.0 – Initial Calculator Release
- v2.0 – Added Square Root Feature and Bug Fix

---

# Q2: Git LFS (Large File Storage)

Git LFS was used to manage large binary files.

Steps followed:

1. Install Git LFS

git lfs install

2. Track ZIP files

git lfs track "*.zip"

3. Add large file (>200MB)

git add largefile.zip

4. Commit and push

git commit -m "Added large file using Git LFS"
git push origin lfs

---

# Q3: Git Stash Workflow

Git stash was used to temporarily save incomplete changes while switching branches.

Example commands used:

git stash
git stash pop

Workflow followed:

1. Started working on **circle area feature**
2. Stashed incomplete work
3. Switched to **rectangle area feature**
4. Retrieved stashed changes
5. Completed features and committed changes

---

# Technologies Used

- Python
- Git
- GitHub
- Git LFS
