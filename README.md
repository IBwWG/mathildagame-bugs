# mathildagame-bugs
There's no code here, it's just used as a gathering place for reporting issues with #mathildagame.

# Instructions for Players
1. Get a free github account so you can report issues.
2. Learn how to report issues helpfully:

Beta builds come with a recorder that should help me reproduce any bugs you find (not to worry: it only records what you do *within* the game *while it's running*.)  It also includes your computer's specs, which can also be helpful sometimes.

## Crashing bugs

If you encounter a crashing bug, a screenshot is automatically taken and included in the crash log.

## Any other issue

Please take a screenshot by pressing F12, then exit the game via the main menu (rather than Alt+F4 or any other Windows built-in way of closing a program), upon which it will automatically crash on its way out in order to output the recording and specs.  The screenshot you can find in the game's `screenshots` subdirectory; please move it to the relevant subfolder of the game's `logs` directory, which is where the crash logs go (not `crashdumper`.)

## Either way

Please find the relevant crash log subfolder in the game's `logs` directory (not `crashdumper`), zip it, and post it with the issue.

## Posting the issue

Go to the Issues tab at the top of the page and search to see if someone else already reported it.  If not, click New Issue at the right.  Then you can drag and drop your crash log zip file, and describe:

1. Steps to reproduce
2. What you expected to happen
3. What happened instead

For crashing bugs you don't need 2 & 3, because the game just shouldn't crash.  For most other issues these two will help bring clarity to anyone reading the issue.

### Example of a helpful issue

(attached crashlog zip here...)

Steps:

1. Click "Start Fresh" on the main menu
2. Click Mathilda
3. Choose Tricky
4. Click Skip
5. Click either of the letters neighbouring the current one on the board

Expected: According to the instructions, clicking a neighbouring letter will move to it.
Instead: The game doesn't seem to respond to these clicks.  It's not frozen...clicking the pause button still works.

### Example of a less helpful issue

The swimming game is broken!  The screen is always stopping and the game never ends.

(Which of the two swimming games?  Which difficulty?  Always stopping in what way and under what conditions?  "Always", does that mean it starts again somehow?  If so, how?  Etc...)
