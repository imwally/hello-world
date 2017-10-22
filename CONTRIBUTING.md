# How to Contribute

1. [Fork](https://help.github.com/articles/fork-a-repo/) this repo.

2. [Clone](https://help.github.com/articles/cloning-a-repository/)
   your version of this repo to your machine.
   
   `git clone git@github.com:username/hello-world.git`

3. Add a new file in the contributors directory with your initals or name as the file name. Then use your editor of choice to add a link to your github profile inside of the file.
    * `cd hello-world/contributors`
    * `echo "https://github.com/imwally" >> WJ.md`
   
4. Add the file to your local repository using the following commands.
    * `git status`
	    * See the status of your current working repository.
	* `git add .`
        * Adds the file to the repo.
	
	You can run `git status` again to see that the file has been added.
	
5. Commit the change with a meaningful description.

	* `git commit -m "Add Wally Jones to contributors"`
        * the `-m` flag let's you set the message
	
6. Push the change to your fork.
    * `git push origin master`
	
	
7. Create a [pull request](https://help.github.com/articles/creating-a-pull-request/).

8. Wait to be notified about your PR being merged.

9. That's it. You successfully used git to fork, clone, add, commit,
   and push. Oh, and created a pull-request, but that's a GitHub
   thing.
