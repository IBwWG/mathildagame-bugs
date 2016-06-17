# mathildagame-bugs
There's no code here, it's just used as a gathering place for reporting issues with #mathildagame.

# Instructions for Players
1. Get a free github account so you can report issues.
2. Learn how to report issues helpfully (read on!)

## Sending helpful data

If the game crashes, or you exit via the title screen, this happens automatically.*  (So don't quit by pressing Alt+F4, nor by clicking the window's X!)

## Non-crashing issues

Please take a screenshot by pressing the F12 key.  They're saved automatically to the `screenshots` subdirectory of the game's data directory, which you can open from the Options menu on the title screen.

## Posting the issue

Go to the Issues tab at the top of the page and search to see if someone else already reported it.  If it appears not, click New Issue at the right.  Then you can drag and drop the screenshot you made above, and describe:

1. Steps to take to demonstrate the issue to someone
2. What you expected to happen
3. What happened instead

For crashing bugs you don't need 2 & 3, because the game just shouldn't crash.  For most other issues these two will help bring clarity to anyone reading the issue.

### Example of a helpful issue

```
Steps:

1. Click "Start Fresh" on the main menu
2. Click Mathilda
3. Choose Tricky
4. Click Skip
5. Click either of the letters neighbouring the current one on the board

Expected: According to the instructions, clicking a neighbouring letter will move to it.
Instead: The game doesn't seem to respond to these clicks.  It's not frozen...clicking the pause button still works.
```

### Example of a less helpful issue

```
The swimming game is broken!  The screen is always stopping and the game never ends.
```

(Which of the two swimming games?  Which difficulty?  Always stopping in what way and under what conditions?  "Always", does that mean it starts again somehow?  If so, how?  Etc...)

### * Optional reading: Wait, what data are you collecting?

Current builds come with a recorder that should help me reproduce any bugs you find (not to worry: it only records what you do *within* the game *while it's running*.)  It also includes:

1. Any missing assets you discovered while playing (a "woosh" sound where there should have been something else) which is helpful for knowing which sounds we're missing (some sounds only play in certain situations, so the more people collecting this information, the easier it is to get all of them)
2. Your computer's specs, which can be helpful sometimes for hardware-specific bugs.
3. A stack trace of a crash (if applicable) which is very helpful for isolating crashing bugs.

Each log is found in its own subfolder under the game's data directory, in the `log\errors` subdirectory.  You can find it easily using the "Open game data folder" button on the Options screen from the main menu.

That's also where you can disable the automatic sending of data, if you would like to.  It's still collected and stored in `log\errors`, in case you want to manually send any information for a particular bug report; you can zip a particular log folder and drag-n-drop the zip file directly into a public Github issue to attach it.
