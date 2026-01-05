1
git global --config --unset-all user.name
git global --config --unset-all user.email
git global --config  user.name "name"
git global --config  user.email "email"
git init 
git add .
git commit -m "message"
2
git checkout -b branchname
git checkout master
git merge branchname
3
git stash apply
git stash list
git stash pop stashname
4
git clone code
5&6
git fetch origin
git rebase origin/main
git push origin branchname
7
git tag v1.0
git tag v1.0 commit id
8
git cherry-pick startcommitid^..endcommitid
9
git log
git show commit id
10
git author="authorname" --since="00-00-00" --until="00-00-00"
11
git log -n 5
12
git revert commit id
