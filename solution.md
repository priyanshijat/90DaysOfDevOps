git init ----> to initialize folder
touch info.txt ----> create a folder 
git add ----> add the file from working directory to staging area
git commit -m "" -----> add file from staging area to repository
git remote add origin https://<your-username>:<your-PAT>@github.com/<your-username>/90DaysOfDevOps.git ----> to add remote origin
git remote set-url origin https://<your-username>:<your-PAT>@github.com/<your-username>/90DaysOfDevOps.git ----> set-url to push local changes to remote
git push -u origin main 
git pull origin main
git log
git branch feature-update
git checkout feature-update
git add info.txt
git commit -m "Feature update: Enhance info.txt with additional details"
git push origin feature-update

  why branching strategies are important in collaborative development
--- Isolating features and bug fixes
--- Facilitating parallel development
--- Reducing merge conflicts
--- Enabling effective code reviews

