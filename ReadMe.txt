Iitial read me file.

Shows Where from the config is coming.
---------------------------------------
git config --list --show-origin

Set-up GIT identity:
---------------------------------------
git config --global user.name "John Doe" // Global is optional
git config --global user.email johndoe@example.com // global is optional if you do not use global you need to do it again and again. Which I am sure you do not want unless you have multiple persona!!!

Check Settings: 
--------------------------------------
git config --list

--- Getting info from the Web UI -----
echo "# InitialRepo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/GhatakCode/InitialRepo.git
git push -u origin main
                

