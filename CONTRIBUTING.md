# Steps to create a pull request
Star⭐️ and Fork this repository.

## Fork the repository
Click on the **Fork** button on the top-right handside of your screen. This will create a local "fork" of this repo in your GitHub account.

## Clone the repository
Open command prompt (for windows) or terminal (for macOS) and run the command:
```
git clone https://github.com/ElixirTechCommunity/Blogging.git
```

## Create a branch
Create a branch according to the issue you have been assigned to. This separates the changes in the pull request from your other changes and makes it easy to edit/amend commits in the pull request.You can create a branch using the git command
```
git checkout -b branch_name
```

## Edit and Commit changes
Edit changes and commit them locally. Add the changes you have done locally to that branch using:
```
git add .
```

Then make the changes required and commit them using:
```
git commit -m "your_commit_message"
```
If you are just updating the commit message in the last commit, you can use ```git commit --amend``` to do that.

## Push the changes to GitHub
Push them to your Github fork by ```git push -u origin branch_name```. That creates the "branch_name" branch at your Github fork and sets it as the remote of this branch.
When you now visit Github, you should see a proposal to create a pull request.

## Advice on pull requests
Pull requests are the easiest way to contribute the changes to git repos at GitHub. They are the preferred contribution method, as they offer a nice way for commenting and amending the proposed changes.
* If you later need to add new commits to the pull request, you can simply commit the changes to the local branch and then use ```git push``` to automatically update the pull request.

## Commits in your pull-requests should
* Have a useful description.
* Have some images regarding the changes done by you.

## If you have commit access
* Do NOT use ```git push --force```.
* Use Pull Requests if you are unsure and to suggest changes to other maintainers.
* Do NOT commit to other maintainer's packages without their consent.
