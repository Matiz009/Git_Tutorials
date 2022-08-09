#Git and GitHub Tutorials

1.	git config –global user.name “[name]” ->sets author name
2.	git config –global user.email “[email address]” ->sets author email id
3.	git init [repository name] ->start new repository
4.	git clone [url] ->obtain a repository from an existing URL.
5.	git add [file] ->adds a file to the staging area.
6.	git commit -m “[ Type in the commit message]” ->records or snapshots the file permanently in the version history.
7.	git commit -a ->commits any files you’ve changed since then & commits any files you’ve added
8.	git diff ->shows the file differences which are not yet staged.
9.	git diff –staged ->differences between the files in the staging area and the latest version present.
10.	git diff [first branch] [second branch] ->differences between the two branches mentioned.
11.	git reset [file] ->unstages the file, but it preserves the file contents.
12.	git reset [commit] ->undoes all the commits after the specified commit and preserves the changes locally.
13.	git reset –hard [commit] ->discards all history and goes back to the specified commit.
14.	git status ->command lists all the files that have to be committed.
15.	git rm [file] ->deletes the file from your working directory and stages the deletion.
16.	git log ->used to list the version history for the current branch.
17.	git log –follow[file] ->lists version history for a file, including the renaming of files also.
18.	git show [commit] ->shows the metadata and content changes of the specified commit.
19.	git tag [commitID] ->used to give tags to the specified commit.
20.	git branch ->lists all the local branches in the current repository.
21.	git branch [branch name] -> creates a new branch.
22.	git branch -d [branch name] -> deletes the feature branch.
23.	git checkout [branch name] -> used to switch from one branch to another
24.	git checkout -b [branch name] ->creates a new branch and also switches to it.
25.	git merge [branch name] ->merges the specified branch’s history into the current branch.
26.	git remote add [variable name] [Remote Server Link] ->used to connect your local repository to the remote server.
27.	git push [variable name] master ->sends the committed changes of the master branch to your remote repository.
28.	git push [variable name] [branch] ->sends the branch commits to your remote repository.
29.	git push –all [variable name] ->pushes all branches to your remote repository.
30.	git push [variable name]: [branch name] ->deletes a branch on your remote repository.
31.	git pull [Repository Link] ->fetches and merges changes on the remote server to your working directory.
32.	git stashes save ->stores all the modified tracked files.
33.	git stash pop ->restores the most recently stashed files.
34.	git stash list ->lists all stashed changesets.
35.	git stash drop ->discards the most recently stashed changeset.
