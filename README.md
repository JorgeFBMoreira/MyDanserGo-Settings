# MyDanserGo-Settings
Repository for my own Danser-Go Settings.

## What is Danser-go?
danser-go is a CLI visualisation tool for osu!standard maps, made by Wieku.
If you want to use Danser-go, please go to danser-go repository and follow all the instructions.

Danser-go: https://github.com/Wieku/danser-go

## What is this repository for?
I made this repository to have a "online backup" of my danser settings. I'll leave a little list here of what you may need to change if you want to use my settings.

# Settings
### General
```json
"General": {
	"OsuSongsDir": "C:\\Users\\Leonardo\\AppData\\Local\\osu!\\Songs",
	"OsuSkinsDir": "C:\\Users\\Leonardo\\AppData\\Local\\osu!\\Skins",
	"DiscordPresenceOn": true,
	"UnpackOszFiles": true
},
```
"OsuSongsDir" | "OsuSkinsDir": Change "\\Username\\" to your account name. For example, if you use Windows 10 and your account name is "Leonardo", change "Username" to "Leonardo".<br>
"DiscordPresenceOn": is a option to link to your discord as a "discord rich". In summary, if you use danser, it'll be displayed in your Discord Account.<br>
"UnpackOszFiles": I suggest to leave this option on.
<br>
### Graphics
```json
"Graphics": {
	"Width": 1366,
	"Height": 768,
	"WindowWidth": 1280,
	"WindowHeight": 720,
	"Fullscreen": true,
	"VSync": false,
	"FPSCap": 0,
	"MSAA": 0,
	"ShowFPS": false,
	"Experimental": {
		"UsePersistentBuffers": false
	}
},
```

"Width" | "Height": Use your own screen resolution. If you run a play (knockout/danse/play), this is the applied resolution.
"WindowWidth" | "WindowHeight": If you don't use fullscreen, change this settings to the screen resolution you want.
"Fullscreen": true if you want fullscreen, false if you don't
