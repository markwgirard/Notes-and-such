Setting up a new Git Repo
========================

##Create a new repository on the command line

    touch README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin git@github.com:<name>/<reponame>.git
    git push -u origin master
    
where `<name>` is `markwgirard`

Use `git add -A` to add all files in current directory.
    
##Push an existing repository from the command line

    git remote add origin git@github.com:<name>/<reponame>.git
    git push -u origin master
    
In Geotab this is
    `git remote add origin git@git.geotab.com:<groupname>/<reponame>.git`
