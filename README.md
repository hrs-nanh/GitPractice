#GitPractice
1: clone to copy remote repository
2: pull will download lastest version from remote repository to local repository
3: how to push to remote?
	3.1: git remote add <name> <url>
	ex: git remote add origin xxx.git
	3.2: git push <repository> <refspec> ...
	repository: name
	refspec: branch name
	ex: git push -u origin master
	-u means next time use it, you can skip branch name
4: how to clone?
	4.1: git clone <repo> <directory>
	4.2: check file
	4.3: git add <file name>
	4.4: git commit -m "add description"
	4.5: git push
5: how to pull?
	5.1: git pull <repo> <refspec>
	5.2: git log (check log git)
6: solve conflict
	6.1: open file, edit and add -> commit
	check: git log --graph --oneline
