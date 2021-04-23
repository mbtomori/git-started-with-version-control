# Activity 2: So what is `git`? and how does it compare to GitHub?

## Learning Outcomes
- [ ] Describe what git is and how it works at a high level
- [ ] Identify when you are using git and when you are using GitHub
- [ ] Compare git to GitHub (and other version control tools)
- [ ] Use GitHub to fork a repository
- [ ] Use Git to clone a repository to your computer

From the previous lesson on [version control](1-version-control.md), you know that git is a 
***version control software*** that helps individuals and teams build and maintain software by managing
changes to that code base. While `git` is extremely popular software for this, it is not without it's drawbacks. 

According to [Atlassian](https://bitbucket.org/product/version-control-software), the pros and cons of `git` 
are as follows: 
#### Pros of Git Version Control
- Distributed fault tolerant network architecture (people can work on the same codebase without messing each other up).
- Optimized for fast commits and checkouts (You can literally commit every minute if you want to)
- Non-destructive updates through use of an immutable log (You have access to all previous (committed) versions of the code)

#### Cons of Git Version Control
- Weak support for large binary files
- Very large repositories with extensive history can slow down interactions
- Learning curve and un-intuitive commands (if you've already used git, you probably already understand
  the learning curve involved).
  
#### :thinking_face: So if `git` is software, what is GitHub?
GitHub is a code hosting platform (web application) for version control and collaboration that uses git for version 
control. This means that GitHub stores your code, any changes you make, and handles permissions for you, but you 
use git to update your code base. 

Consider this example:
You want to work with a team to build a cool game, but you don't want to have to send your files back and forth to each
other every time you make a change. Not only is it frustrating to always add the new code to your project, but you may
have issues with using the same version of the language (Python 2 vs Python 3, for instance). If you set up your project
as a Repository on GitHub, you can have all of your code in one place, and submit changes to that repository from your
computer. No one has to guess which version of the code is the most recent, or how it all fits together, because all the 
code should be in the `main` branch.

## Key Words
- Repository (often shortened to "repo"): a storage location for software packages or projects. It often resembles 
  a directory of files. ([Wikipedia](https://en.wikipedia.org/wiki/Software_repository))
- Commit: A commit is a snapshot of the project's currently staged changes. Git snapshots record the entire contents
  of each file in every commit. ([Atlassian: git commit](https://www.atlassian.com/git/tutorials/saving-changes/git-commit))
- Branch: A branch represents a line of development. In a repository the `main` branch should be the most current, working
  version of your project. (Note: some repositories may still use the [problematic term `master`](https://www.zdnet.com/article/github-to-replace-master-with-main-starting-next-month/)).
  ([Atlassian: git branch](https://www.atlassian.com/git/tutorials/using-branches))


## Activity:
In this activity, you will create your own copy of this repository in your GitHub account (as a fork) and then clone it
to your computer. 
### 1. Create a fork of this repository
**DID YOU KNOW?** When you contribute to open source software, you will often create a fork of the existing repository, make updates
to your individual copy of the repository, and then try to submit (via pull request) to the original repo. You are less
likely to fork a repository when you work at a company and will clone the repository instead (step 2). 

1. Register for a GitHub account or Login to your existing account at [github.com](https://github.com).
2. Fork the repository to your account by pressing the "Fork" button at the top right. 
![Fork Repository Button](../assets/fork.png)
 *If you have multiple organizations, choose your personal account to fork it into.*  
3. You should now have a copy of your own version of this repository in your account! It should look something like this:
![Forked Repository Image](../assets/forked-repo.png)
   
### 2. Clone your fork to your computer
1. Click on the "Code" button. Click HTTPS and copy the URL in the box (If you have set up SSH with GitHub, 
   you can select SSH). 
   ![Clone Repository](../assets/clone.png)
2. Using your command line, navigate to the location you want to put the repository in.
3. Type `git clone <URL> //ignore the <> symbols`. <br>
   ex. `git clone https://github.com/your-username/git-started-with-version-control.git`
4. Enter your github login credentials (*NOTE: You won't be able to see what you type as you type.*)   
5. You should now have a copy of your forked repository on your computer. 

**Some cool things to note: **
1. You can go through this process for as many computers, machines, virtual machines you use. 
That's one of the great things about git. So, say you originally have this repository in a virtual environment and you
want it on your computer directly as well. Just go through these cloning steps, and you will be able to have it in both places!
2. When you work at a company, you will likely clone the project(s) you're working on without creating
forks.

## Checking your understanding:
Open this file in a Text Editor or IDE of your choice, and add your answers (just type them in where it says <ANSWER HERE>)
1. When you forked this repository, were you using Git or GitHub? Explain your reasoning.
   <ANSWER HERE>
2. When you cloned this repository, were you using Git or GitHub? Explain your reasoning.
   <ANSWER HERE>
3. In your own words, explain the difference between Git and GitHub.
   <ANSWER HERE>

#### Common `Git` commands:
- [`git commit`](https://www.atlassian.com/git/tutorials/saving-changes/git-commit)

#### Additional Resources
Atlassian, the company that owns BitBucket (a GitHub competitor) has great tutorials on git. I highly recommend them.
- [Getting Git Right](https://www.atlassian.com/git)