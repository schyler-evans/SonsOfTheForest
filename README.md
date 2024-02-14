# SonsOfTheForestServerSave

## Notes on Multiplayer Saving

The host saves the status of the world and their own inventory to a given slot, like Singleplayer. This means that anything you built in that game, together or alone, host or guest, will be saved on the Host's account, and will be inaccessible to anyone else. You cannot save the world yourself, or change hosts. In order to keep playing the same person must host the game. Guests do not see slots and instead have their screens go black for a moment before the game resumes.

Guests save the contents of their inventory and own player status to their own account. This means that if the host saves the game, but the guest does not, if the server is reloaded the guest will lose every item they had since they last saved on that server. A player's location is also one of the things that is saved, so a player will always appear where they last saved, no matter where they were when they quit the game. In order to protect your progress, save before quitting the game or closing the server. However, if you had a bunch of items, died, and lost them, as long as you saved recently enough to have all or most of those items, if the host saves and you both reload, you'll get all of your item that you had when you last saved back, so you won't lose anything except for what you obtained after you saved. This also means that if you saved, built a log cabin, died, and the host saved and reloaded the server, you'd get all your items back and still have the log cabin built.

Whenever the server is reloaded, all items reappear. This includes story items, and items that you can only have 1 of, like the Modern Axe. You can use this to remedy glitches, such as one player not being able to obtain an important item (like the Modern Axe). This also respawns resources like computers lying on the ground, and also makes cloth respawn in open suitcases. This can be abused, but I don't recommend it because it doesn't make the game much better.

The normal rules of saving the game in Singleplayer may not apply. This could mean that enemies in caves might respawn, which they're not supposed to; however this is not guaranteed. There's other discrepancies (such as shark corpses on beaches disappearing), so be aware that when you load the game again things may not reload the way you expect them to.

## Directory Location: Muliplayer Save File
C:\Users\[User]\AppData\LocalLow\Endnight\SonsOfTheForest\Saves\[some-sort-of-guid]\Multiplayer

## Directions: Hosting a multiplayer save from elsewhere (e.g. from this project.)
- Take the entire save directory (e.g. the directory(s) at the root of this project) and plop them down in the Muliplayer Save File Location listed above on your machine.
- Relaunch the client.
- You _should_ be able to host the save file.

## Directions: Sharing a multiplayer save for use by others.
- Take the entire target save directory and give it to someone else.

## Directions for setting up easy server file syncing with this group
- Navigate to the Muliplayer Save File Location listed above in terminal.
- Delete the existing 'Multiplayer' directory (if you want to retain any existing multiplayer saves, place them aside to re-add later.)
- Get git sorted out on your machine.
- Run 'git clone git@github.com:schyler-evans/SonsOfTheForestServerSave.git Muliplayer'
- Let Schyler know that you've ran into auth issues and we'll get you sorted out.
- Profit.
