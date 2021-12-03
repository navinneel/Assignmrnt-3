# GIt_Assignment_nov2021

## Reference Commands:

#### git clone REPO

Make a copy of a repository. A typical repository address is https://github.com/Grinnell-CSC195/hw1.

#### git add FILE

This can do one of two things. If FILE is not in the repository, it adds it to the repository. If FILE is already in the repository, it marks it as being part of the current set of files to be committed. (Often, you only want to commit only a subset of the files you've modified, so you use git add on each of those.)

#### git status

Get the status of your repository. What files have been modified? Which are staged for commit? Which are just new?

#### git commit

Commits all of the files you're added. Typically, pops up an editor. If vi pops up, use i to switch to insert mode, type the text for the commit, and then type the escape key to get out of insert mode. Then, type :wq to write the file and quit vi.
git commit -m "MESSAGE"
Commits the files you've added, using the given message. (A nice way to avoid the editor.)

#### git log | less

Shows a log of the changes that have been made. (less lets you page through those changes.)

#### git push

Send your commits to the primary repository.

#### git pull

Grab other commits from the primary repository.
Download and Installation:
Download Git from https://git-scm.com/downloads
Follow setup steps from https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup


## Assignment:

1. Clone the repository at ….
2. Create test directory
3. Add an empty file test.txt to the "test" directory 
4. Use get status, you will see the file test/test.txt file in Red color. Please add screenshot
5. Use git to add that file to the repository.
6. Commit your change. Use a meaningful message like "Added test.txt file in the test folder."
7. Push your change to the primary repository. Please add screenshot
8. Look online to see if your change has been pushed.
9. Now edit the test.txt file. Add some random context
10. Add, Commit and Push the text.txt file to the repository
11. Now go to repo online and edit the text.txt file and commit changes.  Please add screenshot
12. Now pull all the changes to the local repository. Please add screenshot
13. Use the git log to see a list of changes to the repository.
14. Take all the screenshots and add them to a folder named “screenshots”
15. Move all the screenshots in that folder
16. Add, Commit and Push all the screenshots to remote repo.


## Branch Creation:

1. Now create a new branch. Make sure you do not add space in the branch name. Use underscores instead of space in the branch name
2. Now run git status and verify if the branch is changed. Output has a line “on branch <branch_name>”
3. Now create a new folder named coding
4. Now create a file code.py and add the below line to the file
       ```print("hello world.")
       ```
5. Now add the file in the “coding” folder, Commit and push the change in new branch
6. Now on Github UI, you will see 2 branches. 
7. Switch to another branch on UI
8. It will either show the option for creating a pull request through the button “compare and pull request” OR you can create PR through a compare URL such as Repourl/compare/main…<branch name> 
9. It will open a Page with the title “Open a Pull request”
10. Click on create a Pull request 
11. Now a Pull request will be created with a URL Repourl/pull/1, Ask TA for the review

