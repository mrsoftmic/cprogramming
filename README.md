# cprogramming
C Programming
1. Create an empty repository
--> git init --bare
2. Get data from Remote Repository to client
--> git clone ssh://<account>@<ip server>/<git project name>
--> git clone ssh://<account>@<ip server>:22/<git project name>
3. Check the status of documents
cd <git project name>
--> cd my_project <enter>
--> git status <enter>
4. Add new documents to the Local Repository
--> git add .  
--> git add <filename>
--> git add *
--> git status
--> git log -p
# Add data into repository local
# Note: . is all file
5. Accept the documents to the Local Repository
--> git commit -a -m "note"
6. Configure account information when working on teamworks
--> git config --global user.name "MrSoft"
--> git config --global user.email "doannv@imic.edu.vn"
--> git config --global user.mobile "0912688283"
--> git config --global user.role "Technical"
--> git config --list
7. Push the data to Remote Repository
--> git push origin <master|...>
--> password:....
8. Updated version on Remote Repository
--> git pull origin <master|...>
--> password:....
--> git log
9. Create branches for the project
--> git checkout -b <branch name> 'Create a new branch
--> git checkout <branch name> 'switch into branch
--> git branch –v
--> git branch
10. How to import branches in git
--> git merge <branch name>
11. Check the branch information on the Remote Repository
--> git ls-remote
