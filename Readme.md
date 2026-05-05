<!-- for local pc file u want to save in github do this followings. -->
1. first make new repo in github  , make new folder in local then (git init) which creat gitrepo in you file then  

2. copy link from github  and paste  code in v.s code 

3. paste it in v.s terminal use this code (git remot add origin link )

4. for check origin use (git remote -v ) which show u link 

5. you can also check which branch u are using main or master. use(git branch ) if branch is master for change its name use (git branch -M main ) which switch u to main branch .

6. for push your file into github use (get push origin main ) but if u dont want to use again again use this code for main directory (git push -u origin main ) this code set your code as permenet branch which u want to use

7. only u have to use is (git push ) insted of git push origin main 

#                                       Git Branches 

1. Branches mean tree branch eg main , master etc .

2. branche use for lot of devleoper working on a project some are working on add new features and some are working on ui and etc so they cannot use main branch (orignal code) they use copy code and add new feature in it and ui then they merge the code to main after finalise .

# Make new branch 

3. for make branch use code (git checkout -b branch name (featurel)).

# For check wich branch we are using 
4. for check which branch we are on  use code(git checkout) and how many braches  are ther use code  (git branch).

# Branch  switch 
5. for switch the branches use code (git checkout main ) its switch to featurel one branch or others .

# Delete Branch  

6. first switch to Another branch for delete which u want to delete  using (git checkout branchname (eg: main) ). 

7. for delete Branch  use(git branch -d branchname ) .