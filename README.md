# ds4a-team-101-project

# Follow this exercise to familiarize with git

I created a `scratch/` folder in the parent directory of this repository. I thought it would be a good idea as a way to practice Github. Basically use this folder to dump anything you want just to learn Git workflow.

**IMPORTANT** This is a disposable folder so do not keep anything important here. It may get deleted.
## Exercise:

1. After you have joined the repository from the email invitation, it's time to download a local copy of the web server repository into your local computer. There is two ways: via SSH and HTTPS. I'll suggest HTTPS so it uses your username and password to authenticate. Code >  HTTPS and grab the link

![image](https://user-images.githubusercontent.com/83491621/117556867-4b155d00-b022-11eb-98da-a9906f3e04f1.png)

2. In your terminal, go to a folder where you want to store your local repository. We are going to clone here. After you authenticate, it should look like this:

![image](https://user-images.githubusercontent.com/83491621/117556885-81eb7300-b022-11eb-9aaa-acb945a9d3f1.png)

3. You are in the main branch, but as it is called "main", you never want to make changes here as this should be the latest and greatest and clean branch from the remote origin repository.

Use `git status` to know what git action you are on

Use `git branch` to find out what branch you are on

4. Create a dummy branch for this exercise:

`git branch scratch-bruno`

5. Change to that branch 

` git checkout scratch-bruno`

6. So now, this is where you want to do your actual work, such as adding files, working your notebook, etc. I created `bruno-scratch.txt` file which I want to upload to the remote repsitory.

- Just move any dummy file in the `scratch` folder.

7. After adding the file, do `git status` it will look like this:

![image](https://user-images.githubusercontent.com/83491621/117557077-3f2a9a80-b024-11eb-96db-929aaf59e471.png)

8. Follow the instructions to add what's unstaged to the staging area. In my case it was `git add scratch/`, then do `git status` to see where you are:

![image](https://user-images.githubusercontent.com/83491621/117557096-71d49300-b024-11eb-942d-143de676f0f6.png)

9. Ready to commit with `git commit -m "my commit here"`. It should look like this.

![image](https://user-images.githubusercontent.com/83491621/117557120-a6e0e580-b024-11eb-86ab-f0998df646cb.png)

10. Now we are ready to push to the remote main branch. We use `git push origin scratch-branch`. Notice you add the name of your branch you are pushing, not `main`.

![image](https://user-images.githubusercontent.com/83491621/117557147-e6a7cd00-b024-11eb-9064-af92312c148a.png)

11. We are more than half way here, now go on to your github account and just by magic! (jk, you did all the work here), you will see a notification that something was pushed. However, it is not in `main` yet. We want to create a pull request for this. 
![image](https://user-images.githubusercontent.com/83491621/117557179-2969a500-b025-11eb-8318-653f87f80544.png)

![image](https://user-images.githubusercontent.com/83491621/117557209-751c4e80-b025-11eb-88e0-3ff81e002255.png)

