# GIT IT

## Contributing upstream to an open source project

1. Make a github account.
2. Navigate to the repository or project you want to contribute to.
3. In the top right corner of the repo/project there are 3 buttons: Watch, Star and Fork. Click on Fork.
4. Fork the repo to your profile. You will now have your own individual copy of the repo that you can play with.
5. Go to your fork (github.com/<YOUR USER NAME>/<REPO NAME> and clone it onto your local system or wherever you do your development.
`git clone https://github.com/<YOUR USER NAME>/<REPO NAME>.git`
6. Commit some fancy changes. Correct some silly mistakes. Fix some bad bugs. Sprinkle on some sweet features! You can do whatever you want with your local copy of a repo/project. The sky's the limit.
7. `git add` your changes
8. `git commit -m "Message about how my changes are important/awesome/an improvement"`
9. `git push origin master` or in place of master you could use a different branch name
10. Back on the copy of your repo in your web browser you should be able to see the changes you just pushed. You will see an option: `New pull request`. Click on it!
11. You can make a pull request on the upstream master branch by confirming your pull request. This will send the moderator a notification and allow them to review your changes before merging them into the upstream project.
12. Moderator reviews your code and may suggest minor changes. Once these changes are made, the Moderator approves your changes.
13. Congratulations! You have just contributed upstream to an open source project!
14. Do a happy dance and start again from number #2

## Configuring your remote projects
[Configuring a remote fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/) allows you to easily keep up with changes that have occurred upstream since you first forked a project. There is more in depth information about managing your remote repos [here](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes)

## Syncing a Fork
[Syncing a fork](https://help.github.com/articles/syncing-a-fork/) is important if you have taken a break from working on a project for a while or if the project you are working on is very volatile. Syncing with upstream ensures that you have minimal merge conflicts and rebases and that you are keeping up with the direction a repo/project is headed


## Rebasing

