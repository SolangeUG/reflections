### LESSON 03 - REFLECTIONS
----

`When would you want to create a remote repository rather than keeping all your
work local?`

> Creating a remote repository is useful when collaborating with others. Plus, with a remote repository, your projects are accessible from anywhere, provided you have access to the internet. And last but not least, a remote repository serves as backup.

----

`Why might you want to always pull changes manually rather than having git
automatically stay up-to-date with your remote repository?`

> When collaborating with others on a project for instance, there could be remote changes that might not work, or that might conflict with your own. Therefore, it's preferable to pull the desired changes manually.

----

`Describe the differences between forks, clones, and branches.  When would you
use one instead of another?`

> Forking is like cloning but it only operates on repositories that are hosted on GitHub. A link to the original repository is created and GitHub keeps count of all the fork repositories.
Cloning creates repositories from a `git` repository, but the latter knows nothing about its clones, until they make commits back to it. Which implies the original repository might never know of its clones. Branches are parts of one single `git` repository.

----

`What is the benefit of having a copy of the last known state of the remote
stored locally?`

> Having a copy of the last known state of the remote stored locally helps track the changes to the remote. Therefore, it's easier to first merge your own changes to that copy, before pushing them to the remote.

----

`How would you collaborate without using git or GitHub?  What would be easier,
and what would be harder?`

> You could collaborate using tools like DropBox or Google Docs. However, it would make it hard to resolve conflicts when making changes to the same lines of code for example.

----

`When would you want to make changes in a separate branch rather than directly
in master?  What benefits does each approach have?`

> You'd prefer making your changes in a branch when working on a new feature, or making experimental changes. That way, your master branch is kept in a working state. So, it's only when you're sure your changes work that you would want to merge them into the master branch.
