# Activity 2: So what is `git`? and how does it compare to GitHub?

## Learning Outcomes
- [ ] Describe what git is and how it works at a high level
- [ ] Compare git to GitHub (and other version control tools)

From the previous lesson on [version control](1-version-control.md), you know that git is a 
***version control software*** that helps individuals and teams build and maintain software by managing
changes to that code base. While `git` is extremely popular software for this, it is not without its drawbacks. 

According to [Atlassian](https://bitbucket.org/product/version-control-software), the pros and cons of `git` 
are as follows: 
#### Pros of Git Version Control
- Distributed fault tolerant network architecture - In other words, people can work on the same codebase without 
  messing each other up).
- Optimized for fast commits and checkouts - You can literally commit every minute if you want to).
- Non-destructive updates through use of an immutable log - You have access to all previous (committed) versions of the code).

#### Cons of Git Version Control
- Weak support for large binary files. 
- Very large repositories with extensive history can slow down interactions. 
- Learning curve and un-intuitive commands (if you've already used git, you probably already understand
  the learning curve involved).
  
#### :thinking_face: So if `git` is software, what is GitHub?
GitHub is a code hosting platform (web application) for version control and collaboration that uses git for version 
control. This means that GitHub stores your code, any changes you make, and handles permissions for you, but you 
use Git to update your code base. 

Consider this example:
You want to work with a team to build a cool game, but you don't want to have to send your files back and forth to each
other every time you make a change. Not only is it frustrating to always add the new code to your project, but you may
have issues with using the same version of the language (Python 2 vs Python 3, for instance). If you set up your project
as a Repository on GitHub, you can have all of your code in one place, and submit changes to that repository from your
computer. No one has to guess which version of the code is the most recent, or how it all fits together, because all the 
code should be in the `main` branch.

Your team uses git commands to make changes to that codebase, and when you're ready to have your code added to the
main code base, you create a pull request on GitHub. Your teammates can give you feedback, comment on, approve, or deny
your changes in that pull request before they are merged using the GitHub web application. 

GitHub is not the only platform for hosting software. Other popular platforms include Atlassian's 
[BitBucket](https://bitbucket.org) and [GitLab](https://about.gitlab.com) which also offer free trials. 

## Key Words
- Repository (often shortened to "repo"): a storage location for software packages or projects. It often resembles 
  a directory of files. ([Wikipedia](https://en.wikipedia.org/wiki/Software_repository))
- Commit: A commit is a snapshot of the project's currently staged changes. Git snapshots record the entire contents
  of each file in every commit. ([Atlassian: git commit](https://www.atlassian.com/git/tutorials/saving-changes/git-commit))
- Branch: A branch represents a line of development. In a repository the `main` branch should be the most current, working
  version of your project. (Note: some repositories may still use the [problematic term `master`](https://www.zdnet.com/article/github-to-replace-master-with-main-starting-next-month/)).
  ([Atlassian: git branch](https://www.atlassian.com/git/tutorials/using-branches))
  
## Next Step:
Go to [3-gitting-started](./3-gitting-started.md) to go to the next activity.

#### Additional Resources
Atlassian, the company that owns BitBucket (a GitHub competitor) has great tutorials on git. I highly recommend them.
- [Getting Git Right](https://www.atlassian.com/git)