# Revisions and The Cloud

How do you connect Github to local repos so you can use more tools?

## [Git Intro](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

1. **What is Version Control?**  
    - A system that allows you to revisit previous versions of a file by recording changes. This allows tracking of what the change was and who made it.  These changes are made through Gits which is a snapshot of the file at the time of the change.  

2. **What is cloning in Git?**  
    - Cloning is copying all versions of all the files in the project.

3. **What is the command to track and stage files?**
   - **Tracked** files are any files that were part of the most recent file snapshot
   - **Untracked** files were not part of the last snapshot and do not currently reside in the staging area.
     - **Determine the state of a file**
       - git status  
     - **Staging**
        - Single File
           - git add filename
        - All Files
          - git add *
        - Only changed files
          - git add .

4. **What is the command to take a snapshot of your changed files?**  
     - To commit a file (snapshot) use the command  
        - git commit -m "made change x,y,z"

5. **What is the command to send your changed files to GitHub?**  
   - To push the changes to the remote repo use the command
      - git push origin master

## Git Command lines in Ubuntu

- git clone https:
  - use the https code given in git hub
  - connects the repo on the cloud to the local database
- git remote -v
  - see the url of the GitHub repo
- git status
  - Checks to see the status of the local repo compared to that of the cloud
  - Red shows that there are changes to the local not synced to the cloud
  - Green shows that they are up to date
- git add ...
  - add the changes to commit
  - ... = File Name
  - ... = * (all files in the repo)
  - ... = . (all files that were changed)
- git status
  - shows the difference between cloud and local
- git commit -m
  - takes a snapshot of the changes made
  - -m indicates a message telling why changes were made
- git push origin main
  - pushes changes to the cloud on the main
- git pull
  - pulls repo from the cloud to the local

### Always A-C-P

- Add
- Commit
- Push  
