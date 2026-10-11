PS C:\Users\shyams\Downloads\githubissue> git config --get user.name
shyamsundar009
PS C:\Users\shyams\Downloads\githubissue> git remote -v
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\shyams\Downloads\githubissue> git init
Initialized empty Git repository in C:/Users/shyams/Downloads/githubissue/.git/
PS C:\Users\shyams\Downloads\githubissue> git config
error: no action specified
PS C:\Users\shyams\Downloads\githubissue> git config --get user.name
shyamsundar009
PS C:\Users\shyams\Downloads\githubissue> git config user.name "shyam-sundar-007"
PS C:\Users\shyams\Downloads\githubissue> git config --get user.name         
shyam-sundar-007
PS C:\Users\shyams\Downloads\githubissue> git config user.name "Shyam-Sundar-7"  
PS C:\Users\shyams\Downloads\githubissue> git config user.email "harinikannan2@gmail.com"
PS C:\Users\shyams\Downloads\githubissue> git config --get user.name         
Shyam-Sundar-7
PS C:\Users\shyams\Downloads\githubissue> git config --get user.email
harinikannan2@gmail.com
PS C:\Users\shyams\Downloads\githubissue> git remote -v                      
PS C:\Users\shyams\Downloads\githubissue> git remote -v
PS C:\Users\shyams\Downloads\githubissue> git remote -v
PS C:\Users\shyams\Downloads\githubissue> C:\Users\shyams\.ssh\ -T git@github-personal
C:\Users\shyams\.ssh\ : The term 'C:\Users\shyams\.ssh\' is not recognized 
as the name of a cmdlet, function, script file, or operable program. Check 
the spelling of the name, or if a path was included, verify that the path 
is correct and try again.
At line:1 char:1
+ C:\Users\shyams\.ssh\ -T git@github-personal
+ ~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\shyams\.ssh\:String 
   ) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\shyams\Downloads\githubissue> git remote add origin git@github-personal:YOUR_GITHUB_USERNAME/YOUR_REPO.git
PS C:\Users\shyams\Downloads\githubissue> git remote add origin git@github-personal:Shyam-Sundar-7/dummy.git          
error: remote origin already exists.
PS C:\Users\shyams\Downloads\githubissue> git remote set-url origin git@github-personal:Shyam-Sundar-7/dummy.git
PS C:\Users\shyams\Downloads\githubissue> git remote -v                      
origin  git@github-personal:Shyam-Sundar-7/dummy.git (fetch)
origin  git@github-personal:Shyam-Sundar-7/dummy.git (push)
PS C:\Users\shyams\Downloads\githubissue> git remote -v
origin  git@github-personal:Shyam-Sundar-7/dummy.git (fetch)
origin  git@github-personal:Shyam-Sundar-7/dummy.git (push)
PS C:\Users\shyams\Downloads\githubissue> git branch -M main
PS C:\Users\shyams\Downloads\githubissue> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'github-personal:Shyam-Sundar-7/dummy.git'
PS C:\Users\shyams\Downloads\githubissue> git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add
PS C:\Users\shyams\Downloads\githubissue> git add .
PS C:\Users\shyams\Downloads\githubissue> uv init 
Initialized project `githubissue`
PS C:\Users\shyams\Downloads\githubissue> uv init 
error: Project is already initialized in
       `C:\Users\shyams\Downloads\githubissue` (`pyproject.toml` file exists)
PS C:\Users\shyams\Downloads\githubissue> git add .
warning: in the working copy of '.python-version', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'main.py', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'pyproject.toml', LF will be replaced by CRLF the next time Git touches it
PS C:\Users\shyams\Downloads\githubissue> git commit -m "init" 
[main (root-commit) 342ae85] init
 4 files changed, 14 insertions(+)
 create mode 100644 .python-version
 create mode 100644 README.md
 create mode 100644 main.py
 create mode 100644 pyproject.toml
PS C:\Users\shyams\Downloads\githubissue> git push -u origin main
ERROR: Repository not found.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
PS C:\Users\shyams\Downloads\githubissue> git remote -v                      
origin  git@github-personal:Shyam-Sundar-7/dummy.git (fetch)
origin  git@github-personal:Shyam-Sundar-7/dummy.git (push)
PS C:\Users\shyams\Downloads\githubissue> git remote -v
origin  git@github-personal:Shyam-Sundar-7/dummy.git (fetch)
origin  git@github-personal:Shyam-Sundar-7/dummy.git (push)
PS C:\Users\shyams\Downloads\githubissue> git config user.name "shyamsundar009"
PS C:\Users\shyams\Downloads\githubissue> git config user.email "shyams@useready.com"
PS C:\Users\shyams\Downloads\githubissue> git config --get user.email        
shyams@useready.com                      
PS C:\Users\shyams\Downloads\githubissue> git config --get user.name 
shyamsundar009
PS C:\Users\shyams\Downloads\githubissue> git add .
warning: in the working copy of 'main.py', LF will be replaced by CRLF the next time Git touches it
PS C:\Users\shyams\Downloads\githubissue> git commit -m "by useready"
[main 66e356d] by useready
 1 file changed, 1 insertion(+)
PS C:\Users\shyams\Downloads\githubissue> git remote -v                      
origin  git@github-personal:Shyam-Sundar-7/dummy.git (fetch)
origin  git@github-personal:Shyam-Sundar-7/dummy.git (push)
PS C:\Users\shyams\Downloads\githubissue> git push -u origin main            
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 307 bytes | 307.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github-personal:Shyam-Sundar-7/dummy.git
   342ae85..66e356d  main -> main
branch 'main' set up to track 'origin/main'.

PS C:\Users\shyams\Downloads\githubissue> git config user.name "Shyam-Sundar-7"                                       
PS C:\Users\shyams\Downloads\githubissue> git config user.email "harinikannan2@gmail.com"                             
PS C:\Users\shyams\Downloads\githubissue> git config user.name
Shyam-Sundar-7
PS C:\Users\shyams\Downloads\githubissue> git config user.email
harinikannan2@gmail.com
