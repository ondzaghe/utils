# To delete all branches in your Git repository except master, simply issue the following command
  
  git branch | grep -v "master" | xargs git branch -D
