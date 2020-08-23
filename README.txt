
Needed Packages:

1. Python		python.org
2. Git			github.com
3. GitHub Desktop	github.com	(the GIT GUI I chose)
4. VSCode		visualstudio.com

From CLI>
pip install flask
pip install flask-wtf
pip install Flask-Bootstrap4


GIT Hub Deskptop doesn't replace knowing the GIT CLI for the test.

git clone [url]

STAGE & SNAPSHOT
Working with snapshots and the Git staging area
git status
show modified files in working directory, staged for your next commit
git add [file]
add a file as it looks now to your next commit (stage)
git reset [file]
unstage a file while retaining the changes in working directory
git diff
diff of what is changed but not staged
git diff --staged
diff of what is staged but not yet commited
git commit -m “[descriptive message]”
commit your staged content as a new commit snapshot
