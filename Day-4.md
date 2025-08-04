git checkout feature - Switch to the feature branch

git rebase main - Reapply commits of feature branch on top of main

git rebase -i HEAD~3 - Interactive rebase to edit, squash, or reorder last 3 commits

git rebase --continue - Continue rebase after resolving conflicts

git rebase --abort - Abort the rebase operation

git log --oneline - View commit history in one-line format to get commit hashes

git checkout main - Switch to the main branch

git cherry-pick <hash> - Apply a specific commit from another branch onto current branch

nano filename- Open the file to manually resolve conflict (in Kali Linux)

git status - Check which files have conflicts

git diff - View the exact conflicting changes

git add filename - Stage the resolved file

git merge --continue - Continue the merge process after resolving conflict

git merge --abort - Abort the merge if it's too complex or incorrect

mkdir git-advanced-demo - Create a new directory

cd git-advanced-demo  - Move into the project directory

git init  - Initialize a new Git repository

echo "line 1" > file.txt  - Create a new file with initial content

git add . - Stage the new file

git commit -m "Initial commit" - Commit the file to main branch

git checkout -b feature    - Create and switch to a new branch named feature

echo "feature line" >> file.txt - Add a new line in feature branch

git commit -am "Feature commit" - Commit the change

git checkout main   - Switch back to main branch

echo "main line" >> file.txt - Add a conflicting line in main branch

git commit -am "Main commit" - Commit the conflicting change


<img width="1920" height="909" alt="Screenshot_2025-08-04_18_37_58" src="https://github.com/user-attachments/assets/9d37e3e2-cdfa-4c5f-bc71-9aee9c7ecd49" />

<img width="1920" height="909" alt="Screenshot_2025-08-04_18_38_06" src="https://github.com/user-attachments/assets/fc8a262d-7ed4-4196-9488-ce49819a261d" />

<img width="1920" height="909" alt="Screenshot_2025-08-04_18_38_11" src="https://github.com/user-attachments/assets/f3f51368-2d0e-4a63-a4b6-b94f29591eea" />






