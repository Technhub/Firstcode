As for the additional task, assuming the project is on a Git repository with a branch called develop, the following commands can be used to clone the branch and develop on a local PC:

$ git clone

$ git checkout develop


To add a new function to the project and introduce it to the team's develop branch, the following commands can be used:

$ git checkout -b new-feature


Make changes to the code*/


$ git add .

$ git commit -m "Added new feature"

$ git checkout develop

$ git merge new-feature

$ git push
