<!-- for local pc file u want to save in github do this followings. -->
1. first make new repo in github  , make new folder in local pc then (git init) which creat gitrepo in you file then  
for check gitrepo use (ls -a)
3. copy link from github  and paste  code in v.s code 
4. paste it in v.s terminal use this code (git remote add origin  Link )
5. for check origin use (git remote -v ) which show u link  its confirm that your linked.
6. you can also check which branch u are using main or master. use(git branch ) if branch is master for change its name use (git branch -M main ) which switch u to main branch .
then first add you file in stage use (git add filename)
7. for push your file into github use (get push origin main ) but if u dont want to use again again use this code for main directory (git push -u origin main ) this code set your code as permenet branch which u want to use
8. only u have to use is (git push ) insted of git push origin main 

#   Git Branches 

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

# for add 2nd branch in github 

8. Agr branches alg alg hai jis branch pe jo kro ge vo usi branch pe dikhe ga  

9.  (git push origin file name ) eg. git push origin featurel

# For merge both file in whatever u make changes in both file  
10. For comapre both branch use (git diff main or featurel  )

# There are 2 ways for merge branches  

11. fist way using teminal in vs (git merge branch main) if code on both branch are same on same line so its  give option to change or overwrite and other option then we have to use (git merge file name ) for change in other branch by merging both  .

12. 2nd way using github . We create pr (pull request in github which let other know what changes u do and want to merge .When head of the project or manager review the code then he let the code merge. ) 

# Steps
  1. click on compare and pull request which come when we use this code in terminal (git push origin file name)
  2. go to github click on compare & pull request

  3.  Wite message in input 
  4.  click on creat pull request button & let the github check everthing is ok . 

  5.  after green click on (merge pull request) then confirm merge  clik on it 

# Pull command for merge file in localReop (in pc )

13. use  (git pull origin main) 


# Undoing changes how to undo line or file changes 

Chase 1: these are for stage changes  jha add krliya pr commit nhi kiya 

14.  Use (git reset filename)

15.  For all file (use git reset)

# after commit undo only for one  and use of log 

16. after commit we dont want to use it so we can use (git reset Head~1) git cannot commit it and use previous one commit  and head me latest commit ye by defalut head name hota hai  

17. use (git log )is for check we can see are commits

# Want to do undo multipale commits 

18.  Hash mean a perticular code with commit .
 
 19. copy commit hash(code) using (git log) code then coppy it use this code for undo comit use code  (git reset hashcode). 

 20. using  (git reset --hard hashcode ) isse hmare vs code me jo jo changes hai vo ht jaengei  

 # Fork

 21. Fork  is for copy code in github and its create in your repository. 
