mkdir hm_2
cd hm_2
git init my

cd my
git add README.md
git commit -m "repo: add first files"

git branch first_branch
git checkout first_branch
git commit -a -m "repo: 1st_subtask"

git checkout master
git commit -a -m "repo: 2nd_subtask"
git log --all
