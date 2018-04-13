# Kepler
A sci-fi point-and-click puzzle/text adventure game built in [Twine](https://twinery.org/), an open-source tool for creating web-deployable games built in HTML, CSS, and JavaScript.

## Working with Twine
In order to keep Git happy when working with Twine (since Twine is not the most friendly when working as a team), please follow the below instructions when working on the Twine story.

1. After making changes inside Twine, use Twine's `Publish to File` option so you have the compiled game in the form of the `Kepler.html` file.
2. Before pushing changes to Git, make sure that you have done Step 1 to ensure that the `.html` file being pushed is the compiled game and not an empty/old version of the game.

## Avoiding Git conflicts
Before doing any work, enter the following commands to ensure that you have an up-to-date master branch and there are no issues with your branch and the up-to-date master branch. Feel free to ask any questions in the team Discord server if there are any issues when trying to work with Git since it is very likely that Twine will not cooperate with Git fully.

1. `git checkout master`
2. `git pull origin master`
3. `git checkout <branchname>` [assuming you have already created a branch to work in]
4. `git merge master`
5. `git push`

## Testing the game
The most recent deployed version of the game can be accessed at this [link](http://web.nmsu.edu/~iancj/Kepler.html). If the latest build is not at this link, feel free ask for the most up-to-date version of the game to be deployed.

