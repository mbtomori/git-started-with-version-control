# Activity 7: Best practices for collaboration

## Learning Outcomes
- [ ] Describe common `git` and GitHub best practices with regard to naming and collaboration.

## `Git` Best Practices
Like all other aspects of software development, there are best practices for using Git and GitHub that you should be 
aware of. 

#### Writing Good Commit Messages
As mentioned in a previous section, there are fairly strong opinions about what makes a good commit message. [Chris Beams'](https://chris.beams.io/posts/git-commit/)
article on what makes a good commit message is easy to read
and provides a fairly straightforward. Teams may decide to use a different standard, which is totally fine as 
well. If you are working in a new team, it makes sense to decide what format your team will use so that you can all more
effectively review and provide feedback on one another's code. 

In summary, these are some good guidelines for writing good commit messages:
1. Limit the subject line to 50 characters
2. Capitalize the subject line
3. Do not end the subject line with a period
4. Use the imperative mood in the subject line ("Fix" not "Fixed")

If you need to use the extended body of a commit message, use the body to explain what and why vs. how.

In summary, these are some good guidelines for writing good commit messages:

Limit the subject line to 50 characters
Capitalize the subject line
Do not end the subject line with a period
Use the imperative mood in the subject line ("Fix" not "Fixed")
If you need to use the extended body of a commit message, use the body to explain what and why vs. how.

#### Branch Naming Conventions and Cleanup
Teams may also decide how branches should be named. This will likely be described in a style guide given to you at
a company or you may have to work with your team to determine what a branch should be named. Generally, branch names
should be consistent as to whether to use hyphens or underscores, and whether they should include identifying information
as to the owner of the branch. 

Here are some resources that discuss branch naming:
- [Deepsource.io's Git Branch Naming Conventions](https://deepsource.io/blog/git-branch-naming-conventions/)
- [Git Branch Naming Conventions](https://allenan.com/git-branch-naming-conventions/)

It is also important to remove dead branches from the remote so that the number of branches do not get unweildy. Clean
up after yourself by deleting any merged branches. 

## GitHub best practices
Any team you join will have a process for reviewing and merging pull requests. Some things to consider are:
1. Where/How should you give feedback? On a particular line or as a comment in your review? (Note: if you are a reviewer
   you can press: start review, and then add comments to a line by hovering over that line and pressing the + button
   or you can add your comments in your overall thoughts.)
   
2. How soon should teammembers expect to receive feedback or acknowledgement of a pull request being submitted?
3. What is the process for merging pull requests? Should the reviewer do it? Or the original author of the pull request?
   (Most companies I've heard of leave it to the author after all approvals have been given).

## Activity
If you are working on a team, consider what collaboration best practices and working agreements you want to set 
to avoid confusion -- especially around merging!


## Next Step:
Go to [8-merge-conflicts](8-merge-conflicts.md) to go to the next activity.