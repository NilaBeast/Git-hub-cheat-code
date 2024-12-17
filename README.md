 SETUP
 Configuring user information used across all local repositories -->
 1. git config --global user.name “[firstname lastname]”
 * set a name that is identifiable for credit when review version history
 2. git config --global user.email “[valid-email]”
 * set an email address that will be associated with each history marker
 3. git config --global color.ui auto
 * set automatic command line coloring for Git for easy reviewing

 4. CLONE & STATUS
 Clone - Cloning the repository on our local machine.
           git clone <-some link->

 Status - Displays the state of the code.
           git status

5. CD - Change directory - This is used to change folder from another folder.
           cd folder name 

6. ls - List files - this showing list of files in the selected folder.
   ls -a - This shows the list of files including hidden files.

7. Untracked - New files that git doesn't yet track.
8. Modified - files changed.
9. Staged - Files ready to be commit.
10. Unmodified - Files unchanged.

11. ADD & COMMIT
    Add - Adds new or changed files in your working directory to the git staging area.
         git add<-file name->

    Commit - It is the record of change.
         git commit -m "some massege"

12. Push command - Upload local repo(pc or laptop) content to remote repo(git repository).
         git push -u origin main

13. Init command 
    init - used to create a new git repo
    git init
    git remote add origin <-link->
    git remote -v  (to verify remote)
    git branch      (to check branch)
    git branch -M main (to rename branch)
    git push origin main

14. Branch commands
     git branch  (To check branch)
     git branch -M main (To rename branch)
     git checkout <-branch name->  (To navigate and to enter another branch)
     git checkout -b <-new branch name->  (To create new branch and navigate)
     git branch -d <-branch name-> (To delete branch)

15.  Merging code
       Way 1:-
            git diff<-branch name->  (To compare commits, branches, files and more)
            git merge <-branch name->  (To merge 2 branches)
       Way 2:-
            Create a PR(Pull Request)

16. Pull command 
     git pull origin main
    used to fetch and download content from a remote repo and immediately update the local repo to match that content .

17. Resolving merge conflicts
    An event that takes place when git is unable to automatically resolve differences in code between two commits.  

                             