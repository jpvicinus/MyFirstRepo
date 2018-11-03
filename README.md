# MyFirstRepo


## Git

#### Making a git repository

- Create a folder that will house all of your projects work

-- e.g. if your working on a calculator project, you might make a folder called calculator (no spaces is best practice)

- Add all of your meaningful code to this folder

- Using the terminal, `cd` into the folder that is holding all of your code. 

-- e.g. if your code is in `Documents/code/python/calculator` you would type `cd ~/Documents/code/python/calculator` 

- Run `git init` to create an empty git repository locally

- Run `git status` to see all the files that are in your new git repository (the files should be red at this point)

- Run `git add .` to add all the files to your git repository.

` Run `git status` again to see all the files that were added. (the files should be green now)

- Your not done yet. You still need to package these added files together in a commit. Run `git commit -m 'enter your git commit message here' 

-- the `-m` stands for `message`

- Run a `git status` again. You should see no pending changes ready to be commit and also should say you have 1 commit ready to be pushed. 

- You need to create a repository from your github account now. 

- In github, login, click repositories, click new, enter a meaningful name and click create.

- Read the instructions on the screen. 

- Run the following command to link your local empty git repository with your newly created github repository 

- `git remote add origin https://github.com/jpvicinus/test1.git`

- You are now ready to push

- Run the following to push your first commit `git push -u origin master`

-- `-u` stands for upstream. `master` is the branch name you are creating. 

- Now refresh your github repository page. you should now see your code! 
