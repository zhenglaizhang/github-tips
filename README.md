#Github Tips

## Issue Tracker for each repository
 
* where the discussions take place, 
* bugs are tracked and reported, 
* features are requested
* labels and milestones that provide the ability for better visualization and categorization of all the issues.


## Generate SSH Keys
https://help.github. com/articles/generating-ssh-keys/
https://help.github.com/articles/ setting-your-username-in-git/
https://help. github.com/articles/setting-your-email-in-git/.


Project and repository, although not the same thing

    https://github.com/<username>/<repository_name>

    git init
    hub create 
    echo "# header" >> README.md
    git commit -m 'init new repo'
    # use the Git protocol (git@github.com) that uses SSH underneath
    git remote -add origin git@github.com:zhenglaizhang/<repository_name>.git
    git push origin master
    # or below
    hub push origin master


.gitignore teampltes
    https://github.com/github/gitignore
