# Git Workflow

Now that we have connected our local and remote repositories, let's learn how to move our code between them.

The two main Git commands that you will first use are git add and git commit.

## Working Directory

The working directory is where you have the files and folders on your computer that you're actively working on or changing!

When you make changes to your files, Git will track these changes and allow you to move them to the staging area.

## Staging Area / Index

The staging area is a status of files and folders within your project that tells Git, "Hey, I'm getting ready to go online!" It's a temporary area where you pick and choose what files you want to "commit", or send to the remote repository.

Using the git add command allows us to do so! Here are some variations of the command you may want to consider:

git add example.txt will add the single file to the staging area. If you only want one of your working files to show up on GitHub rather than the rest of your project, consider specifying a specific file.
git add . will add all the changed files to the staging area. This means that any new file added or changed to the working directory will be included.
git add *.html will only stage files with a specified extension. In this example, this command will only add .html files.
## Committed Files

Committing files are about sharing the current code as a "snapshot" that GitHub online has access to. Commits help us separate different actions in our code, and allow us to add helpful messages so we know and keep track of changes. 📸

Here's what some commit messages might look like for a typical project:

initial commit - our first commit.
add fun pics to header - developer added a header to their project
fixed again fr this time!!!!!! - developer fixed a bug... or so they hope.
Note: Commit messages get silly when you're working on your own for a while 😛, but short, clear, and descriptive messages are needed when working on a team! We want messages to explain what we're doing to the code so other devs can know what was worked on at a glance.

Now that we are ready to commit your staged files, use the following command:

git commit -m 'Your commit message here!'

Pretty useful, right? Commit messages are vital to the development of any project! 🚀