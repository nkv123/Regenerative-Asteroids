[center][b][size=24pt][color=red]Regenerative Asteroid Fields[/color][/size][/b][/center]
[center][img]http://imgur.com/MAEqA0zh.png[/img][/center]

[hr]

[center][img]http://imgur.com/72VYU0uh.png[/img][/center]

[hr]

[center][img]http://imgur.com/7dmHxMOh.png[/img][/center]

[center][b]INSTALL[/b][/center]
[hr]

simply copy the data folder inside your steam avorion folder (steam local folder) usually C:\Program Files (x86)\Steam\steamapps\common\Avorion

[center][size=14pt]THIS MOD IS REQUIRED ONLY TO BE INSTALLED ON THE SERVER NO CLIENT INSTALLATION IS REQUIRED[/size][/center]

[center][b]UNINSTALL[/b][/center]
[hr]

[b]STEP 1[/b]: Replace sectorspecifics.lua and neutralzone.lua with orignial.

[b]STEP 2[/b]: Delete all files associated with this mod.
	After which you need to delete every file installed by this mod (except sectorscripts.lua which needs to be modified)

[b]STEP 3[/b]: Add my Uninstall script to data/scripts/sector/
	then add the data folder included in "UninstallRegenerativeAsteroids.rar" to your Avorion directory. this will add script to terminate and remove the script from each sector you visit which contains the RegenerativeAsteroids Script.

[b]Step 4[/b]: Visit every sector which was a Regenerative Asteroid Sector
	The uninstall is safe to leave in place as it does nothing but kill the script.
	Otherwise if your confident every sector that had the Regenerative Asteroids script has been visited, you can remove the uninstall file aswell.

[b]WARNING [/b]- Failure to remove the script before deleteing the mod will CLEAR the entire sector of every entity (including your ship)

[hr]

All messages except for those alerting the player to the sector will be sent to the console. by default you can access the sector with the ' key.

[center][b]Downloads[/b][/center]
[hr]
[b]Downloads[/b]
Version 1.1.0
[url=https://www.dropbox.com/s/pfqbv8ltoyvd47y/Regenerative-Asteroids-V1.1.0.zip?dl=0]Regenerative Asteroids v1.1.0[/url]
[url=https://www.dropbox.com/s/ducto7s4qxr5uvf/Uninstall-Regenerative-Asteroids-V1.1.0.zip?dl=0]Uninstall v1.1.0[/url]

Version 1.0.0
[url=https://www.dropbox.com/s/zqhb99t73arpehi/RegenerativeAsteroids.rar?dl=0]Regenerative Asteroids v1.0.0[/url]
[url=https://www.dropbox.com/s/xs609eqpwyd2vqr/UninstallRegenerativeAsteroids.RAR?dl=0]Uninstall[/url]

[center][b]Changelog[/b][/center]
[hr]
[b]Changelog[/b]
Version 1.1.0
-Moved Config.lua FROM scripts/mods/ TO scripts/mods/Regenerative-Asteroids/
-Fixed Server announcment only sending announcment to player and not server.
-Added Neurtral Zone Regenerative ASteroids Configuration option, default false.
-Added config check to neutralzone.lua for configuration options
-Added SectorGenerator Configuration option, default true.
-Added config check to SectorSpecifics.lua for configuration options
-Updated Uninstall to contain original neutralzone.lua(patch 0.11.0.7844) and sectorspecifics.lua(patch 0.11.0.7844)
-Added readme.txt to Uninstall zip



Let me know what you guys think.