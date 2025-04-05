# CS347-Lab01-Git-Experiments
This is a GitHub repo for experimental learning. 

## Part I
1. Go to git hub and create a new repository and give it the name
2. Choose to keep the readme and choose a licence
3. Go to settings and then add collaborators
4. Save the changes
5. Click on code to get the link to clone the repo 
6. Go to terminal and cd to the directory where you want to have the new repo cloned 
7. Execute the command <git clone the link to clone the repo>
8. Create the new file (no special commands if you are on vs code) or touch <filename> and  then vim <filename> to edit the file and then finally <:wq> to save the changes
9. Do git add <filename> to add the file, then do git commit -m "commit message" to commit changes and then git push to show the changes
10. Finally, go to git to view that the changes were posted.

## Part II
1. Executed `git log`
2. Created a branch named "still_experimental"
3. Created a file named "dog.txt" using `touch`
4. Added the file to the staging area using `git add`
5. Committed the change using `git commit`
6. Pulled any new changes using `git pull`
7. Pushed latest changes to github using `git push origin main`
8. Paul created a pull request via github where a description and comment was included.
9. Mauricio reviewed and accepted (merged) the pull request
10. Pulled the latest changes using `git pull` and performed a `git log` noticing that the merge from the checked out branch was performed successfully and logged in the git log.

## Part III

1. Edited the same file 
2. one person add, committed and pushed changes 
3. The second person did the same right after 
4. A merge conflict occured
5. The second person prompted in the terminal git merge
6. Resolved the issue but accepting both changes in the editor, then added, committed and pushed
