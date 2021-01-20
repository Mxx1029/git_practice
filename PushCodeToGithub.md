## How to push your local code to GitHub 

_exerpt from [here](https://www.youtube.com/watch?v=wrb7Gge9yoE)_

### Standard commands: ###
- $ **cd** (leave directory + go back to home)
- $ **echo "Hello! This text is going into my newly created md.-File" >> newtext-file.md** (create a text file + fill some text in)
- $ **cat newtext-file.md** (print the file's content to console)
- $ **mkdir test** (make folder named "test")
- $ **rm newtext-file.md** (remove file)
- $ **rmdir test** (remove folder "test")

### push to GitHub ###

1. create new repository on GitHub 

2. open command line

3. if you get only **>** at some point press **Crtl + C**

4. $ **pwd**    (shows current repository)

5. $ **cd /path/local/computer/file/directory/end/folder/**    (start and end with / )

6. $ **ls**     (get a list what's in the folder)

7. $ **git init**     (initialize)

8. $ **git add .**    (space before period! adds all files in your local folder in the git repository)

9. $ **git status**   (gives a list of all new files)

10. $ **git commit -m "Initial import"**   (make sure you have the closing "! commits all the files to the git repo)

11. $ **git remote add origin https://github.com/Mxx1029/new-repository-name.git**    (copy path from GitHub! links the local git repository to GitHub remotely)

12. $ **git branch -M main**   (rename the main branch to main in GitHub and local repository (Terminal))

13. $ **git push -u origin main**     (pushes all to GitHub into the main branch)

14. to delete a local GitHub repository, use the $ **rm -rf** on the __“.git”__ file located at the root of your Git repository. By deleting the __“.git”__ file, you will delete the Github repository but you won't delete the files that are located in your project folder.

