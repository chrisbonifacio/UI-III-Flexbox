# User Interface Project II: Great Idea Web Page With Flexbox

Now that you have experienced building a layout using `inline-block`. Lets revisit the same HTML structure and refactor our first page with flex box module. If you didn't finish yesterday's assignment, just start from scratch or use the solution code provided to you.

Once you have finished the home page using flex box module, go build the services page based on the [design file](design-files/services-desktop-design.png) provided to you. This time you will need to structure your own HTML in addition to using flex box module. You have been provided all the necessary images in the `img` folder.

**Useful Resource: [CSS Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)**

## To Get Started

- Fork the project to your GitHub account
- Clone this project into a directory on your machine.
- Open the code with your preferred integrated development environment (IDE).
- Start on the objectives

[Click this link to learn how to use git on this project](https://youtu.be/8UQYTQzzNYM)

## Objectives

- [ ] Home Page Refactor:

  - Note that the provided HTML is blank. This is because I want you to use your code from yesterday if possible. If you didn't finish, that's fine, just use the solution from yesterday
  - Refactor the home page layout with flexbox where `inline-block` was used before.
  - In your navigation elements, point the services `<a href=""></a>` to `services.html`

- [ ] Services Page Build:

  - Update the title in your newly copied services page to say `Great Idea! - Services`
  - Using the provided [design file](design-files/services-desktop-design.png), create the services page layout using flexbox and box model.
  - Wrap the great idea logo in an anchor tag and point the `href` to `index.html`

  **Remember, you should continue using box model properties this whole time. Flexbox is only used for bigger layout pieces. You will still need content width, padding, border, and margins to succeed.**

## Stretch Goals

- [ ] Create another page based on one of the navigation items in addition to services. Try to create a layout that follows the patterns of the first two designs but with your own creative twist. Use lorem ipsum text for all your content.
- [ ] Introduce media queries into your services page to create a mobile view that stacks all the boxes on top of each other on phone but looks like the layout file on desktop.

* Chris Bonifacio

- [] Merge Conflicts in Git:

  - A merge conflict happens when changes are made to the same line of a file and/or if one person edits a file and another deletes it.
  - In order to resolve a merge conflict caused by competing line changes, you have to make a new commit in which you decide whether you want to keep only your branch's changes, the other conflicting branch's, or make a brand new change that combines changes from both branches.
  - Now you can merge the branches on the command line or push changes to your remote repository on Github and merge changes in a pull request.

- [] Git Commands:

  - git pull: The "pull" command is used to download and integrate remote changes. The target is always the currently checked out HEAD branch. By default, pull uses a merge operation but can be configured to use rebase instead.

  - git rebase: Rebase is one of two Git utilities that specializes in integrating changes from one branch onto another. It's different from Merge as it is always a forward moving change record, while Rebase has powerful history rewriting features.

  - git merge: The "merge" command is used to integrate changes from another branch. The target of this integration is always the currently checked out HEAD branch.

  - git reset: Resets current HEAD(points to the current branch or last commit made on branch) to a specified state. Can be a dangerous command if not used carefully as it is much more complicated than other git commands.

  - git revert: Revert some existing commits. It is used to record some new commits to reverse the effect of earlier ones, usually only a faulty one. If you want to throw away all uncommited changes in working directory, there is the --hard option.

  - git clean: Remove untracked files from the working tree. Cleans the working tree by recursively removing files that are not under version control, starting from the current directory. Usually, only files unknown to Git are removed, but the -x option can be used to remove ignored files as well. This is useful for removing all build products.
