sync from your fork repo to the origin repo

for example, the origin repo is named 'origin'


1.pull the latest code via

$git pull origin master

2. Add your fork repo

$ git remote add myrepo $repo.git

3. When the origin repo code was updated. you can by

$ git push myrepo master

4. you can create one new branch when the code is finishing

$ git checkout -b test origin/master

