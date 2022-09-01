Status:
Shows status of the local repository. This status includes: number of local commits that have not been synced with remote (GitHub), list of files in local folder that are NOT being tracked by git, list of files in local folder that have changes that need to be committed.
example: git status

Clone:
Will make a copy of an already made repo in a new location.
example: git clone "url"

Add:
Will add changes to files to be included into the next commit.
example: git add "file name"

Rm:
Can remove tracked files (Git has to know about said files), (Also does not remove branches)
example: git rm "file name"

Commit:
Pretty much a save changes made (To tracked files) command. Think of it ike saving in a video game accept you can choose with other commands what will be saved.
example: git commit

Push:
Will push the commits made on the branch to the remote repository.
example: git push "repository" "branch name"

Fetch:
Pretty much the opposite of pull. This will get commits from the remote repository to go to your repository.
example: git fetch "repository" (for a specific branch use >>>) "branch name"

Merge:
Used to merge branches. Will merge the branch with the branch you are on.
example: (You're on main branch) git merge "branch name"

Pull:
Like fetch where it gets commits from the remote repository to go to your repository but, it also immediately updates your repository to what the remote repository has.
example: git pull "repository"

Branch:
This can create, remove, rename, and list any of the braches. (Have to switch branches with a different command though)
example: git branch "branch name" (this one creates the branch with whatever name you put)

Checkout:
This command lets you switch between available branches. You will go to whateve branch name that you enter in the command.
example: git checkout "branch name" (Will switch to the branch name you enter)

.git folder:
This is a hidden folder that keeps every change made even without commits. It is hidden to prevent deleting it on accident. This folder can help you to undo changes because it shows what you did.
example: "information" .git (The information is just the stuff before the .git on the same line when you view it)

.gitignore file:
Pretty much tells GitHub what files it can ignore when you commit things. Will ignore files ending with a /.
example: "information" .gitignore (The information is just the stuff before the .gitignore on the same line when you view it)

Pull requests:
Tells other people you are working for or with that you've pushed to a repository. Can choose between them to merge to the main branch.
example: Click the branch you want in the drop menu, enter the name and description, then send the pull request.

SSH authentication to repositories:
Used for GitHub to have your repository. You have to make sure to not give GitHub your private key though, only the public one. Now you can commit to that repository and GitHub will have it.
