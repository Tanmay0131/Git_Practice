# Git/Github Notes

Note: use ctrl+shift+v to preview md files in VS Code

## Basic Concepts

1. **Repository (repo)**

   A project folder that Git is tracking. Can be **local** (on your computer) or **remote** (Like GitHub)

2. **Version Control**

   A system that tracks changes to code over time, letting you revert to previous versions or collaborate with others.

3. **Commit**

   A snapshot of your changes. Includes a message describing what was changed.

4. **Working Directory**

   The current state of your files on disk.

5. **Staging Area**

   Where you prepare changes before committing. You "stage" files that are ready to be committed.

---

6. `git init`

   Initializes a new Git repository in a folder.

7. `git status`

   Shows the current state of the working directory and staging area

8. `git add <file>`

   Stages changes in a file for the next commit. (note you can `git add *` to stage all files in the working directory, while `git add .` does the whole repository)

9. `git commit -m "message"`

   Saves the stages changes with a commit message.

10. **Add a remote location for a repo**

    `git remote add origin <link to repo>`

11. `git push`

    Sends local commits to the remote repository.

12. `git pull`

    Fetches **and merges** changes from the remote repository to your local one.

13. `git fetch`

    Fetches **but does not merge** automatically.

14. `git merge`

    Merges changes from one branch into another.

    - To merge branches, switch to the branch yhouw want to merge into (using `git checkout`), then use `git merge <branch_you_want_to_merge>`

15. `git branch <branch_name>`

    Create a new branch.

16. `git checkout "branch name"`

    Switch to a different branch (edits/commits will be on this now)
