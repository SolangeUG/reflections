### LESSON 02 - REFLECTIONS
----

`What happens when you initialize a repository? Why do you need to do it?`

> When a repository is initialized, a `.git` directory is added to the repository. It is necessary to run `git` init, otherwise it is not possible to track down the changes applied to the directory.

----

`How is the staging area different from the working directory and the repository?
What value do you think it offers?`

> The staging area is an intermediary space between the working directory and the repository, in which you get to determine which changes get committed.

----

`How can you use the staging area to make sure you have one commit per logical
change?`

> When working on a feature or a bug fix, adding the files changed to the staging area helps break local changes to the working directory into small logical changes. Therefore, only the files related to that logical change are loaded onto the staging area and committed as one logical change.

----

`What are some situations when branches would be helpful in keeping your history
organized? How would branches help?`

> Branches would be helpful if you wanted to work on an experimental feature for example, and not sure that it would work. Using a branch for that feature helps you keep your master branch bug free, while trying out some new features for your project.

----

`How do the diagrams help you visualize the branch structure?`

> Diagrams will show all the commits in each branch. Hence, it's easier to spot from which commit id a given branch was created. Which is less straight-forward if done with `git` log alone. Diagrams help spot unreachable commits too.

----

`What is the result of merging two branches together? Why do we represent it in
the diagram the way we do?`

> Merging two branches together results into a new commit that takes into account all the changes made in the two branches. The new commit then points to the two branches as its parent commits.

----

`What are the pros and cons of git’s automatic merging vs. always doing merges
manually?`

> `git`'s automatic merging is time-saving in non-conflicting situations. And when conflicts do occur, `git` actually brings them to your attention, leaving it up to you to fix them. Which in my opinion, is a good thing.
