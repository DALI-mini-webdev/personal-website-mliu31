personal website for dali's mini webdev course x wisp

to pull github files on terminal (unix)/powershell (windows) ---> sets up communication channel b/t github & ur local computer (so u don't have to drag and drop each time, just edit through powershell)
~~~
1) copy the link in 'get code' in your github repo 
2) paste it into powershell with 'git clone [paste it]' (pulls repo from remote repo to your local machine)
3) navigate into the directory that youw ant inside ur github 'cd personal-website-mliu31' 
4) 'ls' for unix; 'dir' for windows (lists all the files present in that directory)


to push github files from terminal/powershell (on local machine) to github (remote repo)
~~~
1) 'ls' for unix; 'dir' for windows (lists all the files present in that directory)--confirms where you are & see new files that you've added on your local machine 
2) 'git status' (see all the files that you've added)
3) 'git add .' preps those new file for commit (file names turn green -> ready for commit!)
4) 'git commit -m "commit message//make it descriptive e.g. created new files"' (prepped to get pushed to remote repo) 
5) 'git push' pushes the code you've prepped to the remote repo online