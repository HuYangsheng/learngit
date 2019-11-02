This is a new file, I will put the git commands that I learned new into it.

Now I have learned some skills about git,they are as following:
    git init # this let you to initial a directory which can be managed by git
    git add filename # when you modified a file or create a new file, you can use git
		     # to add this file so that it can be managed by git.
    git commit -m "..." # when you are sure enough work have been done in this file 
			# you can use it to record your modified.
    git status
    git log
    git reflog # find all commit id you commited
    git reset --hard [HEAD^|commit id] # to restore file version
    git rm <file> # delete file from depository, but you can restore it by using
	   	  # git reset --hard <file>
    git checkout -- <file> # can discard the modification in the workplace
    git reset HEAD <file> # when you already add modified file to stage, you can use it
    	  		  # to reset it back to workplace, then you can use git checkout
    			  # to discard modification.
    git remote add origin https://github.com/HuYangsheng/learngit_new.git 
             	  # help you to make connection to your remote github
    git push -u origin master  # push the master on your desktop to remote github and
 			       # merge the master together
    git remote set-url origin git@github.com:HuYangsheng/learngit.git 
		  # update the existiong one if you don't need it 
		  # when you delete the repository in github please use it to update
    git clone git@github.com:HuYangsheng/gitskills.git
	   	  # first the file gitskills.git should be existed in github, then you
		  # can use this commands to clone it from github to your desktop
    git checkout -b dev # create a branch named "dev", it equals to 
			# git branch dev ## create a branch
			# git checkout dev ## switch to dev branch
    git branch # look up current branch
    git checkout master # switch to master branch
    git merge dev # merge dev branch onto current branch, if you want to merge it onto
       	 	  # master branch, you need change to master first.
    git branch -d dev # delete dev branch
    git log --graph # show the branch merge graph
    git merge --no-ff -m "merge with no-ff" dev  # 
    git stash # to stash your current work so that you can do something emergency.
    git stash list # look up the stash work list
    git stash apply # recover the work you stashed but it will still in the stash list
    git stash pop # recover the work you stashed and delete it from stash list, recommend!
    git cherry-pick <commit_id> # copy a special commit into current branch
    git branch -D <branch_name> # delete the unmerged branch, use -D





