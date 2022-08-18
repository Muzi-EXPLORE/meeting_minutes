# Contributing
Contributors are urged to use the Clone -> Edit -> Pull Request (PR) workflow when making contributions.

## The Process
### 1 - Getting the Repo
- Clone the repo into your local machine.

### 2 - Making Changes
- On your local repo, `fetch` and/or `pull` to recceive the latest changes made to the remote repo. 
- Create a new branch that you'll use to make changes: Branch from `main`.  Use `git checkout -b new_branch_name`.
- The new branch should be given the same name as the meeting minutes file e.g `meeting_25Dec2022`  
- Make your changes, remember to comment your code.
- Follow the style guide of the project. PEP8 is used for python code.
- If tests exist, run them.
- Add only the file(s) you want to commit e.g `git add file_name.ext`
- Commit the changes with a message e.g `git commit -m "add meeting minutes for 18 Aug 2022 meeting"`
- Commit early; commit often

### 3 - Push up to GitHub
- Push your branch to GitHub whilst setting it as the `upstream`. Run `git push --set-upstream origin new_branch_name`.
- - Note that this will change your local repo so that it tracks `remote/new_branch_name` by defualt. This may affect the results of your `fetch` and `pull` commands
- Open a Pull Request (PR) on the repo. Target the `main` branch for your PR.

### 4 - Update your local repo
- Once your PR has been approved & merged, pull the changes from `origin` to your local repo & delete your extra branches.

## Ideas for making your first contribution
- Add your name to the `CONTRIBUTORS.md` file.
- Adding or modifying docstrings or comments in the code.
- Edit something inside on of the markdown files e.g README, CONTRIBUTING