# Git Commands

## Guide on git processes:

### What you'll need most: 

1. Start from main : 
````git checkout main````

- pull the latest changes of main if not up-to-date: ````git pull origin````
This will actually do two things: ````git fetch origin```` & ````git merge````
First it will fetch the changes that you'll be able to see in your changes and the latest will merge the changes to your branch. 
git pull will directly merge changes that doesn't have any conflicts, if there is it will show on your editor as conflicts file. 

- create new branch and checkout out the branch (it creates/ branches off a new branch out of main) : ````git checkout -b MOIA-{number}_new_branch_name````

2. Write your code

3. To commit and push:

    - *git add* will stage your changes :  ````git add .````

you can then commit your changes : ````git commit -m "write commit message between the quotation marks"````

then you can push to the remote *(origin)* : ````git push origin````

In between you can check regularly if your branch is up-to-date with main so if there's conflicts with your code it doesn't get to much to resolve: ````git pull origin main````

