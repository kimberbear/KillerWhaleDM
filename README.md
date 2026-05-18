# Captain Wayne: Deep Sea Deathmatch
> formerly CWVD: Killer Whale Deathmatch

A Zandronum (3.3) compatible .pk3 based upon Captain Wayne: Vacation Desperation by Ciaran Games<br>

## Please note
THIS IS A FAN-MADE PROJECT AND IS NOT AFFILIATED WITH OR ENDORSED BY CIARAN GAMES<br>
If you like this game... Go show your support by buying a pirate ship!<br>
...or well, you can buy the game on Steam too.<br>
captain-wayne.com<br>
<br>
This Zandronum mod is very early in development.<br>
Many things are likely to change, so don't be surprised if old things stop working after new updates!<br>

## Features implemented
* Multiple playable Killer Whales as selectable classes
* Powerups allowing temporary transformation into boss characters
* Fast paced Deathmatch gameplay inspired by Quake III Arena

## Features planned
* More Killer Whales (including original ones not included in the game!)
* A set of unique weapons and a special ability per Killer Whale and Boss
* Deathmatch conversions of CWVD maps (Riptide Rampage or Campaign where possible)
* More gamemodes including Skulltag/Capture The Flag and Last Man Standing

## Installation
Download the latest release build and extract the files. There will be a WAD and PK3. To play, use Doomseeker for easy online gameplay and the latest development build of Zandronum (Zandronum 3.3 works great!) <br>
Make sure that Doomseeker and by extension Zandronum can see the WAD and PK3, that way you can join any servers hosting the game.<br>
You can do that by opening up Doomseeker's settings and adding the file path to the files if there isn't already.<br>
File paths are found by following options -> configure -> file paths<br>
<br>
if you have issues with zandronum recognising the game, just copy the .wad and .pk3 over to C:\users\[your user]\Appdata\Local\doomseeker\plugins\zandronum\3.3-alpha...... basically whereever doomseeker's copy of zandronum is for you. <br>
<br>
As this is project still very early in development you can manually build the game for the latest changes. just note that most servers are gonna host the release builds, so you're better off using them.<br>
See the section Manual Building for how to do that.<br>
## Mapping
Download the Ultimate Doom Builder configs and add them to the Configurations folder at your Ultimate Doom Builder installation.<br>
Make sure to enable CW: Deep Sea Deathmatch as an available game, and add the required pk3 archives including the one for CW-DSD.<br>
The Ultimate Doom Builder configs are far from perfect, so be sure to check back for updates or contribute improvements.<br>
<br>
I really recommend configuring UDB so that you can test with bots. It speeds up map testing significantly. Just add "+addbot" followed by one of the bot's names (e.g. dave) to the command line arguments.<br>
<br>
If you make a custom map, you are welcome to share it with the community and if it is deemed to be of a high enough standard, it may be included with the game and you will be credited appropriately!<br>
<br>
You can add additional files via: command line arguments to the Zandronum executable; dragging the additonal files alongside the game files onto the Zandronum executable; using the launcher to add addtiional command line arguments before starting the game.<br>
The launcher allows you to use custom command line arguments too and they work identically- though the launcher does remember what you entered last and will save it with your server configuration when saved.<br>

## Discord server
We have a Discord server! There, new updates will be announced and you can even find people to play games with. We also have tutorials and if you need help, we're there too. You can also suggest changes and give feedback directly there too.<br>
https://discord.gg/ugCrkT2nxA

## Common issues
"Zandronum is asking me to point to the directory for Doom II!"<br>
Ensure you included kwgame.wad with Zandronum and Doomseeker. kwgame.wad is your substitute for Doom II to keep Zandronum happy.<br>
<br>
"Using the manually built version, the game isn't opening with UDB or Zandronum!"<br>
You've made a mistake somewhere... Make sure that the contents from the CW-DSD folder of the source is in the root of your new archive or it won't work!<br>
<br>
"When starting Zandronum, I got this error: "weapon.swaystyle" is an unknown actor property"<br>
You're probably using the wrong version of Zandronum. We recommend using Zandronum 3.3 or 3.2.1 (at the minimum!)<br>
<br>
## Feel free to contribute or leave feedback!
This is my first Zandronum project (of this scope at least) so if you spot any mistakes or areas of improvement, feel free to contribute or suggest changes!<br>
New features and mapping config improvement are especially welcome at the moment!<br>
## Manual builds
Please take extra care at STEP 3! Ensure that the contents of CW-DSD are in the root of the archive, not in a subfolder of the archive of that name! <br>
This is a super common mistake.<br>
1. Download source
2. Zip the contents of CW-DSD ( the files inside the folder CW-DSD, not the folder itself) and change it's file extension from ".zip" to ".pk3" specifically.
3. Use the WAD and new created PK3 as you would with a normal release, as described above.
<br>
It is especially important to copy "kwgame.wad" into the same directory as "zandronum.exe" as it is your stand in replacement for Doom II..<br>
Zandronum won't be able to start without that WAD file. If Zandronum asks for the directory to Doom II, you haven't placed "kwgame.wad" into the same directory as "zandronum.exe" as Zandronum cannot find it.<br>
<br>
If you have issues, please try opening your .pk3/.zip, and ensure all the game files are not in a single folder inside the zip. This will prevent Zandronum and UDB from opening up CW:DSD.<br>
