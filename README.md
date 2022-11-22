# pull_request
pull request 

1. git checkout parent_branch_name

2. git pull origin child_branch_name

3. then solve merge conflicts

4. then commit and push

5. and take pull

#upload repo on bitbucket

In the Android studio, go to VCS-> 'Enable version control'.
From dropdown menu select Git, then click OK.

Right click on your Project view in the Android Studio:
go to Git -> Add.

(All the files in the project should change the color, turned green probably)

Open Terminal in the Android studio.
From your empty repo in the Bitbucket page, copy from the paragraph "Step 2: Connect your existing repository to Bitbucket" the line :

git remote add origin https://<user>@bitbucket.org/<path>.git, then Enter.

Now type:

git commit -m "initial commit" (to commit all the files from the Project), then Enter.

Now type:

git push -u origin master (to push all the commited files to the master- or the other branch, just change "master" to other branch).

That's it. Your project is versioned and placed in your Bitbucket repo.
