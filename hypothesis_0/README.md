0. My first hypothesis to test if i can create a file, open it for editing and make it executable for owner
	Did it work: No it did not work, however the file open for editing
	Code: vi file_name;chmod u+x file_name

1. My second hypothesis to check if after setting an upstream for my repo with origin master, then changing branch name to main, will i still be able to push
	Did it work: No, but i got this interesting error message

fatal: The upstream branch of your current branch does not match
the name of your current branch.  To push to the upstream branch
on the remote, use

    git push origin HEAD:master

To push to the branch of the same name on the remote, use

    git push origin HEAD 

So even the branch name doesn't match i can still push to github using 
	git push origin HEAD:master
	this pushes from my branch name main to git with branch name master

2. My third hypothesis if i change branch name back to master, will i be able to push
	Did it work:

3. After changing my branch name from master to main, if i also change my repo name on my remote platform(GitHub) will i be able to push
	Did it work:
