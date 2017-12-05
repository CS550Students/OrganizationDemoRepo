# Notes on Github


## What is GitHub?
GitHub is a platform that allows coders to collaborate on and review code together.
It uses version control, so users can work on a snapshot of the code at one time without making any permanent changes to the master.
GitHub Desktop syncs your laptop to the site, allowing you to access code directly from the app.


## Repositories
Repositories are used to organize a single coding project.

__To create a repository, go to file at the top, then New Repository__


## Branches
Branches are the way you can work on multiple versions of a repository at one time.
Changes you make in a branch don't affect the master branch until you make those changes permanent.

__To create a branch, go to branch at the top, then New Branch__
__To delete a branch, go to branch at the top, then Delete__


## Commits
Commits are saved changes that have been made permanent.
Each commit comes with a brief message that describes what changes you have made and why to anyone reviewing your code.

__To commit changes, save the changes you have made in Sublime. Then on GitHub desktop, go to the bottom left and type in a title in the Summary box and a brief description, if needed, of the changes you have made. Then, commit the changes to the branch.__


__To revert, you can not delete a commit, but you can go back to an earlier version of the commits. Instead, you can go to the History tab, right click on the commit and click revert this commit.__
_This doesn't undo the commit. It creates a NEW commit that reverts the repository back to an earlier version._

Zhi's way: checkout to the commit that you want to revert to, copy the contents of the file you want to revert, and replace it on the file after checking back out to the original location.


## Pull Requests
Pull Requests are the center of collaboration on GitHub.
When you open a pull request, you are proposing your changes and asking someone else to review them.
If you make a pull request to a repository that you are not the owner, you are asking the owner to review your changes and merge them into their master branch.



## Merges
Merges bring changes you have made into the master branch.
After merging, you can see the commits from the pull request on the master branch.

__To merge, go to Current Branch and make sure the current branch is the master. Then, go to branch at the very top and click Merge into Current Branch.__



## Markdown
Markdown is a language that allows users to style their form of writing on GitHub

You can use it to:
1._Italicize_
2.__Bold__
3. Create Lists
4. Insert Emojis :computer:
5. ~~Strikethrough~~
6. Link things (http://github.com)
7. Create a Table
8. Insert Images ![Image of GitHub Logo](https://assets-cdn.github.com/images/modules/site/logos/desktop-logo.png)
9. Create Headers

(http://guides.github.com/features/mastering-markdown/)

## Organizations
Organizations allow multiple users to work on a repository at once. Since they are private, only the members of the organization can review each other's work.





