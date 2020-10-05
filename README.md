# git-games-workshop2
A collection of git based challenges for GrizzlyHacks' second git workshop

## Instructions

1. Fork this repository to your own account.
2. Clone *your personal* fork.
3. Make sure you fetch *all* of the branches using `git fetch --all`
4. As you complete each challenge, submit a pull request.

### Challenge 1
**Merge a branch with master**

Simply merge the branch "mergeme" with master.

### Challenge 2
**Find the commit that broke master**

Inside the master branch, you'll find a java file called *broken.java*. One of the commits broke this file. You'll need to find the commit ID! Add that commit ID to a new file called "broken.txt".

**hint** *broken.sh was fine at commit "c6112f974d4519437f798cc088c07834ef4d1bd4". The change that broke it came sometime after.*

### Challenge 3
**Rebase a branch onto master**

There is a branch called "rebaseme". Add it to master without using `git merge`.
