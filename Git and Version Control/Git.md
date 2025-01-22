# Push Local Repository to GitHub:
`git remote add origin URL` specifies that you are adding a remote repository, with the specified  `URL`, as an `origin` to your local Git repo.

Now we are going to push our master branch to the origin url, and set it as the default remote branch:
`git push --set-upstream origin master`
# Git pull from Github:
* When working as a team on a project, it is important that everyone stays up to date.
* Any time you start working on a project, you should get the most recent changes to your local copy.
* With Git, you can do that with `pull`.

`pull` is a combination of 2 different commands:

`fetch`
`merge`

`pull` is a combination of fetch and merge. It is used to `pull` all changes from a remote repository into the branch you are working on.


