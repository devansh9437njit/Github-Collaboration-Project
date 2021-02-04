### Git - Define with Examples (Commands & Terminology)
---
**Table Content** 
- [Repoistory](#repo)
- [Clone](#clone)
- [Fork](#fork)
- [Branch](#branch)
- [Merge](#merge)
- [Checkout](#checkout)
- [Push](#push)
- [Pull](#pull)
- [Remote Add / Remove / Show](#remote)
- [Status](#status)
- [Master Branch](#master)

<a name="repo"></a>
## Repository
A Git **Repository** is the <code>\\.git</code> folder inside a project. **Repository** is basically tracks all changes made to files in your project, building a history over time. Meaning, if you delete the <code>\\.git</code> folder, then you delete your project’s history.

<a name="clone"></a>
## Clone
The **Clone** command downloads an existing Git repository to your local computer. You will then have a full-blown, local version of that Git repo and can start working on the project.

<a name="fork"></a>
## Fork
A **Fork** is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.
Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea.

<a name="branch"></a>
## Branch
Branching is a feature available in most modern version control systems. Git branches are effectively a pointer to a snapshot of your changes. When you want to add a new feature or fix a bug—no matter how big or how small—you spawn a new branch to encapsulate your changes. This makes it harder for unstable code to get merged into the main code base, and it gives you the chance to clean up your future's history before merging it into the main branch.

<a name="merge"></a>
## Merge
Git **Merge** will combine multiple sequences of commits into one unified history. In the most frequent use cases, git merge is used to combine two branches.

<a name="checkout"></a>
## Checkout
The git **Checkout** command operates upon three different entities which are files, commits, and branches. Sometimes this command can be dangerous because there is no undo option available on this command.

It checks the branches and updates the files in the working directory to match the version already available in that branch, and it forwards the updates to Git to save all new commit in that branch.

<a name="push"></a>
## Push
The git **Push** is most commonly used to publish an upload local changes to a central repository. After a local repository has been modified a push is executed to share the modifications with remote team members.

<a name="pull"></a>
## Pull
The git **Pull** command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.

<a name="remote"></a>
## Remote
**Remote** repositories are versions of your project that are hosted on the Internet or network somewhere. You can have several of them, each of which generally is either read-only or read/write for you. Collaborating with others involves managing these remote repositories and pushing and pulling data to and from them when you need to share work.

<a name="status"></a>
## Status
The git **Status** command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git. 

<a name="master"></a>
## Master
In Git, **Master** is a naming convention for a branch. After cloning (downloading) a project from a remote server, the resulting local repository has a single local branch: the so-called "master" branch. This means that "master" can be seen as a repository's "default" branch.

___
([ README.md ](../README.md))