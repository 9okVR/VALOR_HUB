# VALOR HUB

Multi-game script hub. One loader detects the game and runs the right panel.

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/9okVR/VALOR_HUB/refs/heads/main/ValorHub_Loader"))()
```

A key is required. Get one in the Discord: https://discord.gg/GSAHydBefQ

Supported: Volleyball Legends · Blox Fruits · Fisch · Grow a Garden · Murder Mystery 2 · RIVALS · Bedwars · Keyboard Escape · Steal An Egg · Huss Valley · DOORS · (Universal fallback for anything else)

Usage stats: the loader reports your Roblox username, the game and server you are in, your executor and device (and which executor functions it lacks), which panel switches are on (and the last ones you changed), the panel's errors and which feature they came from, how much time each feature takes, the kick or disconnect message Roblox shows you, your character's movement in the last minute before a kick, disconnect or report (speed, sudden jumps, walk speed), game results the panel counts (e.g. Volleyball touches), and your FPS and ping, so we can see what is used, fix what breaks and catch game updates or kick waves fast. If a run ends without an exit (a crash), the last of these is saved in your executor's VALOR_HUB folder and sent the next time you run VALOR. Problem reports you send from a panel's Report tab go to us with the same details. Nothing else is collected.
