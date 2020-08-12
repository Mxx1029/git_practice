## How to push your local code to GitHub 

_exerpt from [here](https://www.youtube.com/watch?v=wrb7Gge9yoE)_

IMPORTANT: to leave directory + go back to home $ **cd**

1. create new repository on GitHub 

2. open command line

3. if you get only **>** at some point press **Crtl + C**

4. $ **pwd**    (shows current repository)

5. $ **cd /path/local/computer/file/directory/end/folder/**    (start and end with / )

6. $ **ls**     (get a list what's in the folder)

7. $ **git init**     (initialize)

8. $ **git add .**    (space before period! adds all files in your local folder in the git repository)

9. $ **git status**   (gives a list of all new files)

10. $ **git commit -m "First commit"**   (make sure you have the closing "! commits all the files to the git repo)

11. $ **git remote add origin https://github.com/Mxx1029/new-repository-name.git**    (copy path from GitHub! links the local git repository to GitHub remotely)

12. $ **git push -u origin master**     (pushes all to GitHub into a master branch)

13. to delete a local GitHub repository, use the $ **rm -rf** on the “. git” file located at the root of your Git repository. By deleting the “. git” file, you will delete the Github repository but you won't delete the files that are located in your project folder.

