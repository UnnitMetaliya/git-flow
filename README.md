### Setting Up Git Flow for New Project

#### Steps

[ ] Go to Github.com. Click on "+" icon. Click on "New Repository"  
[ ] Specify github repository name same as local repository name  
[ ] Give nice description to Github repository  
[ ] Click on "Create Repository"  
[ ] Go to command line and check current location. It should be repository you want to push. If it's not, then arrive to that location. For ecample, if my current location is ABC folder in C drive. And, repository I want to push is in XYZ folder in C drive, then I will have to get my location to XYZ folder in C drive. And, then to repository I want to push.

[ ] type "git init" on command line. This is called initializing local repository as GIT repository.  
[ ] Now, go to page being shown right after clicking "Create Repository" button. It has clear instructions.
[ ] First, add remote origin. Copy paste > git remote add origin... line  
[ ] Add all files to staging. Type > git add .  
[ ] Specify commit message. For example, > git commit -m "first commit"  
[ ] Push repository > git push -u origin master  
[ ] Check on Github.com repository if commit got pushed
