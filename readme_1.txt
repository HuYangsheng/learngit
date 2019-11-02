This is a new file, I will put the git commands that I learned new into it.

Now I have learned some skills about git,they are as following:
    git add filename # when you modified a file or create a new file, you can use git
		     # to add this file so that it can be managed by git.
    git commit -m "..." # when you are sure enough work have been done in this file 
			# you can use it to record your modified.
    git init # this let you to initial a directory which can be managed by git
    git status
    git log
    git reflog # find all commit id you commited

    git reset --hard [HEAD^|commit id] # to restore file version
    git rm <file> # delete file from depository, but you can restore it by using git 
		  # reset --hard <file>
    git remote add origin https://github.com/HuYangsheng/learngit_new.git 
             	  # help you to make connection to your remote github
    git push -u origin master  # push the master on your desktop to remote github and
 			       # merge the master together
   
