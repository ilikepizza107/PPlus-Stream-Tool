![preview](https://media.discordapp.net/attachments/913208498676973619/1019213690689568798/Untitled.png)

# Project+ Stream Tool
*Also available for [Melee](https://github.com/Readek/Melee-Stream-Tool), [Ultimate](https://github.com/pokeroby_beto/Ultimate-Stream-Tool), [Rivals of Aether](https://github.com/Readek/RoA-Stream-Tool) and [Rushdown Revolt](https://github.com/Readek/Rushdown-Revolt-Stream-Tool)!*

So you're interested in doing Project+ streams, huh? Luckily for you, with this tool you'll be able to update all the variables you need for the provided overlays with the provided GUI, and easily customize the overlays to make them your own! 

---

## Features
- [Handy interface](https://media.discordapp.net/attachments/913208498676973619/1018910167817007136/Untitled.png) to quickly change everything you need, like player names, characters, scores, round, casters...
- Easy and fast setup using a browser source. Drag and drop!
- A game overlay for both [16:9](https://media.discordapp.net/attachments/913208498676973619/1018920716609007656/Screenshot_2022-09-12_11-26-45.png?width=1202&height=676) and [4:3](https://media.discordapp.net/attachments/913208498676973619/1018911365076897894/Screenshot_2022-09-12_10-49-02.png?width=1202&height=676) is included, with renders and stock icons for all characters and skins!
- A [VS Screen](https://media.discordapp.net/attachments/913208498676973619/1018915195709554748/Screenshot_2022-09-12_11-04-57.png?width=1202&height=676) is also included, to be used in pauses between games.
- Easy to customize! Made in html/javascript, every file can be edited at will!
- This is **not** a Stream Control clone. It doesn't have anything to do with it, everything is custom made.

---

## Setup Guide
You can watch [this video](https://www.youtube.com/watch?v=417QjymeOMk) beto made or follow the steps below. (It is for Smash Ultimate but it's the same thing).

These are instructions for regular OBS Studio, but I imagine you can do the same with other streaming software:
- Dowmload the ZIP file.
- Extract somewhere.
- Drag and drop `Game Scoreboard 16.9/4.3.html` into OBS, or add a new browser source in OBS pointing at the local file.
- If the source looks weird, manually set the source's propierties to 1920 width and 1080 height, or set your OBS canvas resolution to 1080p, or make the source fit the screen.
- In the source's propierties, change *Use custom frame rate* -> `60` (if streaming at 60fps of course).
- **Also tick** `Refresh browser when scene becomes active`.
- Manage it all with the `Project+ Stream Tool` executable.

Repeat from the 3rd step to add the `VS Screen.html`, though I recommend you to do so on another scene.

### Interface shortcuts!
- Press `Enter` to update.
- Press either `F1` or `F2` to increase P1's or P2's score.
- Press `ESC` to clear player info.

2 basic transitions are included in the `Resources/OBS Transitions` folder, if you don't have a transition yourself of course. To use them on OBS:
- Add a new stinger transition.
- Set the video file to `Game In.webm` or `Swoosh.webm`.
- Transition point -> `350 ms`.
- I recommend you to set the Audio Fade Style to crossfade, just in case.
- On the scene's right click menu, set it to Transition Override to the transition you just created.

The interface will also update basic text files with the match info at `Resources/Texts/Simple Texts/` so you can add them to OBS with ease.


---

## Customizing stuff

You can still customize how your Scoreboard and VS screen look by replacing the files in the overlay folder.

While to change the position of the icons and writings you should modify parts of the code contained in the `html` and `js` files.

---

## Credits

The "Project+ Stream Tool" was made by [beto](https://twitter.com/pokeroby_beto), with edits by ilikepizza107.

This is an upgraded version of the [Melee Stream Tool](https://github.com/Readek/Melee-Stream-Tool) made by [Readek](https://twitter.com/Readeku).

The scoreboard was made by [beto](https://twitter.com/pokeroby_beto), with edits by ilikepizza107

All the renders were taken from the Project+ Dolphin HD Textures

For any feedback contact [ilikepizza107](675031793686282276) on Discord.
