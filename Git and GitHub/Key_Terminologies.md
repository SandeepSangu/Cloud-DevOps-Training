# Key Terminologies

## Git Terminologies

- **Branch:**
  - A version of the codebase that diverges from the main branch to isolate changes for specific features, fixes, or experiments.

  - *Example:* Creating a feature branch to develop a new feature without affecting the main codebase.
  
- **Commit:**
  - A snapshot of your changes, saved to your local repository. Each commit is uniquely identified by a checksum.

  - *Example:* Saving a set of changes with a message describing what was done.

- **Stage (Staging Area/Index):**
  - The area where Git tracks changes that are ready to be included in the next commit.

  - *Example:* Adding modified files to the staging area before committing them.

- **Merge:**
  - The process of integrating changes from one branch into another, typically the main branch.

  - *Example:* Combining changes from a feature branch into the main branch after development is complete.

- **Merge Conflict:**
  - Occurs when changes from different branches conflict and need to be resolved manually.

  - *Example:* Two branches modified the same line of code differently.

- **Clone:**
  - The process of creating a local copy of a repository on your computer.

  - *Example:* Downloading a repository from GitHub to your local machine to work on it.

- **Remote:**
  - A common repository that all team members use to exchange their changes.
  
  - *Example:* GitHub repository that team members push and pull changes from.

- **Origin:**
  - The default name Git gives to the server from which you cloned.

  - *Example:* The URL of the repository you cloned from is referred to as origin.

- **Upstream:**
  - The original repository that was cloned.

  - *Example:* The main repository you forked from on GitHub.

- **Master/Main:**
  - The default branch name given to a repository when it is created. "Main" is the modern default.

  - *Example:* The main branch where the stable code resides.

- **Repository:**
  - A storage location where your project lives, containing all the files and revision history.

  - *Example:* A folder containing all the project files and the `.git` directory.

- **Working Directory:**
  - The directory on your computer where you are making changes to your project.

  - *Example:* The folder you navigate to on your computer to modify project files.

- **HEAD:**
  - A reference to the last commit in the currently checked-out branch.

  - *Example:* The pointer to the latest commit on your current branch.

- **Checkout:**
  - The action of switching from one branch to another or to a specific commit.

  - *Example:* Moving from the main branch to a feature branch.

- **Push:**
  - The action of sending your commits to a remote repository.

  - *Example:* Uploading your changes to GitHub.

- **Pull:**
  - The action of fetching changes from a remote repository and merging them into your current branch.

  - *Example:* Downloading and integrating changes from the remote repository.

- **Fetch:**
  - The action of retrieving updates from a remote repository without merging them into your current branch.

  - *Example:* Getting the latest changes from the remote repository without applying them.

- **Rebase:**
  - The process of moving or combining a sequence of commits to a new base commit.

  - *Example:* Rewriting commit history to make it linear and more understandable.

- **Tagging:**
  - Marking specific points in a repository’s history as important, typically used for releases.

  - *Example:* Tagging a commit with `v1.0` to denote the first release.

- **Alias:**
  - A shorthand for a Git command to simplify repetitive tasks.

  - *Example:* Creating an alias `git co` for `git checkout`.

### GitHub Terminologies

- **Pull Request (PR):**
  - A proposal to merge changes from one branch into another, often used in collaborative environments to review and discuss changes before they are merged.

  - *Example:* Submitting a pull request to merge a feature branch into the main branch on GitHub.

- **Fork:**
  - Creating a personal copy of someone else's repository that lives on your GitHub account.

  - *Example:* Forking an open-source project to make your modifications.

- **Issues:**
  - A feature request, bug report, or task associated with a repository.

  - *Example:* Creating an issue to report a bug or suggest a new feature.
