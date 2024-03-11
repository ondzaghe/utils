#### Delete all branches in your Git repository except master
  
  `git branch | grep -v "master" | xargs git branch -D`

#### Fetch Master from another branch

  `git fetch origin master:master`
