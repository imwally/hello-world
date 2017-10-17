# How to Contribute

1. [Fork](https://help.github.com/articles/fork-a-repo/) this repo.

2. [Clone](https://help.github.com/articles/cloning-a-repository/)
   your version of this repo to your machine.
   
   `git clone git@github.com:username/hello-world.git`

3. Add a new file in the contributors directory named either with your
   initials.md or firstname_lastname.md. Add a link to your github
   profile inside of this file. 
   
   > `$ cd hello-world/contributors`
   > `$ touch wj.md`
   > `$ vim wj.md`
   
   Add a link to your github profile:
   `https://www.github.com/imwally`
   
   Save the file and quite vim:
   `:wq`
   
4. After you make that change, add the file to your working.

	You can also see the status of your current working tree:
	`git status`
	
	You should see something about untracked files, which is the file
    your just created. 
	
	Add the file.	
	`git add .`
	
	You can run `git status` again to see that the file has been added.
	
5. Commit the change.

	`git commit -m "Add Wally Jones to contributors"`
	
6. Push the change to your fork.

	`git push origin master`
	
7. Create a [pull request](https://help.github.com/articles/creating-a-pull-request/).

8. Wait to be notified about your PR being merged.

9. That's it. You successfully used git to fork, clone, add, commit,
   and push. Oh, and created a pull-request, but that's a GitHub
   thing.
