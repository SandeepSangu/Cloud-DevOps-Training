# Git Commands

1. **git clone**
   - Clones an existing repository to your local machine.
   - Example: `git clone <https://name-of-the-repository-link>`

2. **git branch**
   - Manages branches (create, list, delete).
   - Examples:
     - Create: `git branch <branch-name>`
     - List: `git branch --list`
     - Delete: `git branch -d <branch-name>`

3. **git checkout**
   - Switches branches or restores working tree files.
   - Examples:
     - Switch: `git checkout <branch-name>`
     - Create and Switch: `git checkout -b <branch-name>`

4. **git status**
   - Displays the state of the working directory and staging area.
   - Example: `git status`

5. **git add**
   - Adds changes to the staging area.
   - Examples:
     - Single File: `git add <file>`
     - All Files in Current Directory: `git add .`

6. **git commit**
   - Records changes to the repository.
   - Example: `git commit -m "commit message"`

7. **git push**
   - Updates remote refs along with associated objects.
   - Examples:
     - Default (for the current branch): `git push`
     - Specific Branch: `git push origin <branch-name>`

8. **git fetch**
   - Fetches changes from a remote repository without merging them.
   - Example: `git fetch origin`

9. **git pull**
   - Fetches and integrates changes from a remote repository to the local repository.
   - Example: `git pull`
   - **Difference between `git fetch` and `git pull`:**
     - `git fetch` retrieves updates from the remote repository but does not merge them into the current branch. It updates the remote tracking branches.
     - `git pull` is a combination of `git fetch` and `git merge`. It fetches the updates from the remote repository and then merges them into the current branch.

10. **git revert**
    - Reverts changes specified by a commit.
    - Example: `git revert <commit-hash>`

11. **git merge**
    - Joins two or more development histories together.
    - Examples:
      - Switch to target branch: `git checkout <branch-name>`
      - Merge: `git merge <branch-to-merge>`

12. **git diff**
    - Shows changes between commits, commit and working tree, etc.
    - Example: `git diff <commit-hash> <commit-hash>`
