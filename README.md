# WARFRONT

Build a nation on a strategy map, then fight its battles yourself, as a soldier on the ground.

WARFRONT is a real-time strategy game in the spirit of *Age of Empires* and *Rise of Nations*. When two armies meet, you can let the computer settle it, or drop into the battle as a classic-Battlefront-style third-person shooter: capture command posts, drive tanks, fly fighters, or command the whole army as its General. Every soldier your nation trained is one life in that battle.

Play alone against the computer, or with a friend on a second laptop.

![Storming an enemy capital](images/battle-city.png)
![The strategy map](images/strategy-map.png)

## Download

**[⬇ Download WARFRONT for Windows (zip, about 140 MB)](https://github.com/cbeaver728/warfront-download/releases/latest/download/WARFRONT-win64.zip)**

Older versions and what changed in each: [all releases](https://github.com/cbeaver728/warfront-download/releases).

**You need:** Windows 10 or 11 (64-bit) and about 300 MB of space. It runs on laptops with built-in graphics. Nothing else to install.

## Install

1. Download the zip, right-click it and choose **Extract All**.
2. Open the extracted folder and double-click **WARFRONT.exe**. Keep the folder together: the game needs the files beside it.
3. If Windows says **"Windows protected your PC"**, click **More info**, then **Run anyway**. (The game isn't signed by a publisher, so Windows doesn't recognize it yet.)
4. If Windows Firewall asks about WARFRONT, allow it on **Private networks**. You only need that to play with a friend.

To update, download the new zip and replace the old folder. Your saved games are kept elsewhere, so they stay.

## How to play

- **The strategy map:** pick a faction and a difficulty on the start screen. Train workers, build farms, lumber camps and mines, grow your cities, research new ages, and raise armies. **Win by taking the enemy's capital.**
- **Battles:** when armies meet, choose **Simulate** (the computer settles it) or **Fight it yourself**. In a battle: WASD moves, the mouse aims, left click fires, **E** gets in and out of vehicles, **F1** shows all the controls and **Esc** opens the menu.
- **Save your game:** on the strategy map, **Esc → Save game**. On the start screen, pick it under **Saved games** to carry on.

## Play with a friend

Both of you need **the same version** of the game: download the same release.

1. **On the same Wi-Fi:** one player clicks **Host a game** on the start screen and reads out the address it shows. The other types it in and clicks **Join**.
2. **From different houses:** both install [Tailscale](https://tailscale.com/download) (free) and sign in to the same Tailscale account. Then host and join as above, using the host's **Tailscale address** (it starts with `100.`).

You each play your own nation on the same map. When your armies meet, the defender chooses first whether to fight, and then you can **fight the battle together**, on opposite sides.

A two-player game can be saved by the host (**Esc → Save game**) and picked up later: the host chooses it under **Saved games** and clicks **Host this game**, and the friend joins as usual.

## If something goes wrong

- **The game won't start, or looks wrong:** update your graphics driver (Windows Update → Advanced options → Optional updates, or your graphics maker's website).
- **Your friend can't connect:** check the address, that you're both on the same Wi-Fi (not a guest network) or both on Tailscale, and that the host's Windows Firewall allows WARFRONT.
- **To report a problem:** press **Esc → Open log folder** and send the file `godot.log`, with what you were doing.

---

*WARFRONT is a free, unofficial fan project made for fun. It isn't affiliated with, endorsed by or connected to Lucasfilm, Disney, EA or the makers of Battlefront, Age of Empires or Rise of Nations. Music and some animations are free (CC0) works; see [CREDITS](CREDITS.md).*
