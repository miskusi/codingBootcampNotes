# Commands

## pwd
lists present working directory

## cd <directoryName>
Change present working directory to PWD/directoryName

## mkdir <directoryName>
Makes new directory called directoryName in the PWD

## touch <fileName >
Makes a new file called fileName in PWD

## ls <directoryName?>
Lists all files in PWD or directory

## clear
Clears text off the terminal

# GIT commands

When pushing to github, follow these steps:

1. `git add < fileName >`
    - This adds Filename to the changelist
    - Use `git add` . OR `git add -A` to add everything to the changelist

2. `git commit -m "Some commit message"`
    - if you forget -m you will be in vi (a command line text editor). type `i` then Type your message, then pres `esc`, then `:wq` and finally enter. (this is how you get out of it if you forget to add)

3. [Optional] `git pull`
    - Use this only if ther are other changes not already in your local copy

4. `git push < server > < branch >`
 - you can usually just do `git push`