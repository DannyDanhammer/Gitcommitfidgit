#!/bin/bash

# Set the repository and file paths
REPO_PATH="C://Users/danny/Gitcommitfidgit"  
FILE_PATH="FreeMoney.py"
GIT_MESSAGE="Daily update: Important Feature added"
BRANCH="main"


cd "$REPO_PATH" || { echo "Repository path not found!"; exit 1; }


echo "    " >> "$FILE_PATH"

# Add, commit, and push changes
git add "$FILE_PATH"
git commit -m "$GIT_MESSAGE"

# Ensure remote URL is correctly set
git remote set-url origin https://github.com/DannyDanhammer/Gitcommitfidgit.git

# Push changes to the specified branch
git push origin "$BRANCH"
