# Week-4-Exercise

This week we're building the game **tic tac toe** using the object oriented programming from the lecture.

## Tic Tac Toe

Also known as **Naughts and Crosses** this game involves two players placing a naught or a cross inside a 3x3 grid with the goal being to create a row of 3, vertically, diagonally or horizontally. You can play the game on [this website](https://playtictactoe.org/) or read the [Wikipedia entry](https://en.wikipedia.org/wiki/Tic-tac-toe) about the game.

## Make a GitHub Repository

1. If you haven't already please [make an account with GitHub](https://github.com/join).
2. Then [make a new repository](https://github.com/new) and name it something sensible like `tic-tac-toe`.
3. The other settings aren't important to us at the moment so we can leave them as they are. The key thing is that the Repo be public so you can show it to us if you need a hand with the code or just want some feedback.
4. Clone the repository using the `git clone` command from before.

You can then use this repository to write your code in.

## Committing to The Repository

You should make sure to commit work to your repository fairly frequently and shouldn't leave work uncommitted if you move onto another task.

Here's a quick reminder of how to commit to the repository:
1. `git status` - This will show you all the changes that aren't staged. (This command isn't needed but it gives you an idea of the state of the repo.)
2. `git add [file name]` - Replace `[filename]` with the name of the file that you want to stage. You can use `git add .` which just adds all the files in the folder but it's a good idea to know what the command does.
3. `git status` - Shows that all the files have been staged.
4. `git commit -m [message]` - Replace `[message]` with a short description of all of the changes made. This will create a git commit in your local repo.
5. `git push` - Pushes the commit up to the repository, you should be able to see the work when on the repo page on GitHub.

*Note: Get in contact with us if you're having any issues with this stuff, it can be really hard to use at first and does go wrong.*

## Making the Game

There are a few considerations when making the game:
- Use OOP in your code, a good object to have is the board but you may choose a different structure.
- You can build the game with either 2 players or a bot player, 2 players is probably easiest to start with.