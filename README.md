# CSGO-Server-Setup
This Git provides some configs for an extended [CSGO Egg](https://github.com/Mashlex/Pterodactyl-Eggs/blob/199753a61b2bc9f04b5c4e3f6ecd1fea73615fb2/egg-counter--strike--global-offensive.json), which can be found in another Git. These files are missing from the standard CSGO server and are therefore loaded additionally.

## Included Plugins/Extentions
| Name | Description |
|------------------------------|--------------------------------------------------------------------|
| [Dhooks 2](https://github.com/peace-maker/DHooks2) | A SourceMod extension to hook any game function from within a SourcePawn plugin. This fork adds support to dynamically detour any functions instead of only virtual functions. |
| [SteamWorks](https://github.com/KyleSanderson/SteamWorks) | Exposing SteamWorks functions to SourcePawn. |
| [Plugin Enable/Disable](https://forums.alliedmods.net/showthread.php?p=1682844) | Move plugins to and from the disabled folder by command. |
| [Bypass Password](https://forums.alliedmods.net/showthread.php?p=2738005) | As you know, in CS:GO game, you can not set sv_password on server if there are players in game. Need to be empty server. This plugin block that check, and allow you set sv_password when ever you like. |
| [Random Password Generation](https://forums.alliedmods.net/showthread.php?t=139990) | This is a simple plugin that generates a random password. |
| [Get5](https://github.com/splewis/get5) | Get5 is a standalone SourceMod plugin for CS:GO servers for running matches. |
| [Multi 1v1](https://github.com/splewis/csgo-multi-1v1) | The multi1v1 plugin sets up any number of players in 1v1-situations on specially made maps and they fight in a ladder-type system each round. The winners move up an arena, and the losers go down an arena. Players choose between specific round types (for example: "rifle", "pistol", "awp"), and the plugin automatically spawns and gives players the appropriate weapons each round start. |
| [Practice Mode](https://github.com/splewis/csgo-practice-mode) | Practice Mode is a sourcemod plugin for helping players/teams run practices. Check out the features and command list below for a better understanding of all the tools practicemode provides. |

## Included Modes
| Name | Based On | Description |
|-----------------------|----------|---------------------------|
| Soft Reset | Valve | This is not a real game mod. It is a quick way to reset the server without changing the map. |
| Hard Reset | Valve |  |
| Casual | Valve |  |
| Flying Scoutsman | Valve |  |
| Trigger Discipline | Valve |  |
| Guardian | Valve |  |
| Retake | Valve |  |
| Arms Race | Valve |  |
| Practicemode | [Practice Plugin](https://github.com/splewis/csgo-practice-mode) |  |
| Team Deathmatch | Valve |  |
| Free for All | Valve |  |
| Headshot Mode | Valve |  |
| Arena 1v1 | [Multi 1v1 Plugin](https://github.com/splewis/csgo-multi-1v1) |  |
| 1on1 Match | [Get5 Plugin](https://github.com/splewis/get5) |  |
| 2on2 Match | [Get5 Plugin](https://github.com/splewis/get5) |  |
| 5on5 Match | [Get5 Plugin](https://github.com/splewis/get5) |  |


## Custom Commands
| Command | Description |
|----------------|------------------------------------------------|
| Bot Count | Behind this is the command "bot_quota", which changes the number of possible bots. | 
| Bot Kick | Kick the Bot from the Server. |  
| Bot Add | If the Bots cant join automaticly, then you can add bots. | 
| Generated Password | Generate a random password and write it in the chat. | 

## Configs
### Server Config
The server.cfg is the core of the server configs. It contains all the basic settings that are important.
### Gamemodes Server Config
The gamemode configs are only links to the existing files. This makes it easy if these files are updated by Valve. Some configs have additional commands that may fix some errors. These are not affected by the Valve updates.
