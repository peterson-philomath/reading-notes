# Github Connection and Local Repo

How do you connect github to local repos so you can use more tools.

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
