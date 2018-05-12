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

## Easier testing
When making changes to the Twine story and testing it in the web browser, rather than clicking the .html file in your file browser every time you use Twine's `Publish to File` option, you can simply refresh your browser and the changes should be reloaded and you will stay at the same passage you were working in. This removes a few mouse clicks from the overall steps needed to view new changes.

## Remote access to the game
The most recent deployed version of the game can be accessed at this [link](http://web.nmsu.edu/~iancj/Kepler.html). If the latest build is not at this link, feel free ask for the most up-to-date version of the game to be deployed.

## Playing the game locally
While the game can be played remotely using the above link, the size of the game and the image assets can cause some loading issues depending on connection speed and how well the NMSU webhosting service is working. For the best experience, it is best to clone the repo and play the game locally in your browser. The steps to download and play the game are as follows:
1. Clone or download the repo to your machine and place it in the directory of your choice.
2. Do not move any of the files out of the directory or some parts of the game may no longer function.
3. Open the Kepler.html file in the browser of your choice.
4. The game should start at the first passage ready to play!
5. You can save your progress using the save function on the sidebar. It can be saved locally in a .save file or you can save it within your browser. We recommend saving it locally since clearing your browser cache will result in the save file being deleted.
6. Enjoy the game!
