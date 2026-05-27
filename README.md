Number Guessing Game

Branches

main:
Initial Number guessing game

dev:
Add encouraging message for players

feature1:
Add ability to quit game with negative number input
Add play-again loop functionality
Improve user feedback messages for guesses
Add version comment documenting quit feature

feature2:
Add maxAttempts constant and game over state
Implement max attempts logic and game over condition

feature3:
started hint
got it done
had to fix
done

hotfix:
Fix randomInt to properly include max value in range


Differences between merge, rebase, squash, and cherry-pick:
merge combines 2 branches while keeping the history of the 2.
rebase moves commits to appear more linear
squash combines multiple commits into 1

What you observed in the git history for feature1 vs feature2 vs feature3:
feature 1 kept merge history
feature 2 became a cleaner linear sequence
feature 3 was reduced from many small commits to a large clean one

When you would use each strategy in real projects:
I would use merge when I want my hisory, rebase when I want clear linear history,
and squash to get rid of messy repeated commits.

