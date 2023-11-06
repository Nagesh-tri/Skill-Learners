Git Steps:

-[] Installing Git
-[] Add git-bin folder into path variable

-[] Open your project folder In vs code and done your prior work
-[] open a new terminal -->(<CTRL+SHIFT+`>)
-[] SetUp your username and email using these commands in terminal:
        git config --user.name "<Your Name>"
        git config --user.email "<Your Email>"
Initialize a git repo:
-[] Initialize a git-repositry (your folder will be a repo now) --->git init 
-[] Stage your files(add them to git version control)   -->git add .
-[] commit in first time with your msg   --> git commit -m "<your msg>"
    <!-- from now this is first snap of your project has been stored now 
    Its a good habit to commit regulary specially when you have done today's work and goin to rest must commit before go ,, who know blunders happen overnight -->

GitHub steps
-[] moving from local to online: publish your repo simply with vs code git source control 
    <!-- left hand side 3rd icon (just after search ) you will find it jsut click on "publish to github"  and rename your repo if you want and click on 2nd option that is shown 
    "public repo"-->
        <!-- If you are publishing it first time  -->
        -[] First Time Work Only:
            -[] you will require to autherise vs code to work with github using brower it will ask for github password do that first then do above step again



copying (Clone) repo from github to your local machine

-[] goto github repo you want offline: 
        -[] click on <Code> button (green colored in center of page)
        -[] copy HTTPS link under clone section
-[] open terminal on your local machine from where your want to copy repo  
    -->(🪟<WindowKey+R>)  -->enter "cmd" in it 
    -->or simply open it by searching
-[] type this command along with your repo link that copied earlier 
    -->>  git clone <Your_repo_link>
-[] you are all done new folder has beed ceated 
    <!-- you can diectly open it in vs code by this command :  -->  code RepoName/. 



Pushing changes to github : push 
-[] git push REMOTE-NAME BRANCH-NAME   -->git push origin master


Branching:
-[] git branch <branch-name>    creating new branch
-[] git branch                  see all branches availble to our project
    <!-- it will also tell in which branch we are at very moment -->
-[] git checkout <branch-name>      to change branch

