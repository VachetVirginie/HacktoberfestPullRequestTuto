# HacktoberfestPullRequestTuto

Step by step description of creating a pull request for beginners

OS: Linux

Steps:

1. Fork the repository so that you can work on the repo locally.

2. Create upstream (Do it only once) 

		git remote add upstream <clone_link>

you can get clone_link in Clone or Download.

3. Open the terminal (ctrl + alt + t) and run below commands, 

		git status 
		git add . 
		git commit -m "commit_message"

4. Run below steps to sync your branch with the master branch

		git fetch upstream
		git merge upstream/master

5. To final commit

		git push origin master

6. If there is something left on stack and you don't want it

		git stash

Note: Step 4 is not required if you are sure that the last commit is yours.
