# CSGO-Server-Setup
This Git provides some configs for an extended [CSGO Egg](https://github.com/Mashlex/Pterodactyl-Eggs/blob/199753a61b2bc9f04b5c4e3f6ecd1fea73615fb2/egg-counter--strike--global-offensive.json), which can be found in another Git. These files are missing from the standard CSGO server and are therefore loaded additionally.

The heart of this git is the Admin Menu Custom Config, in addition to the gamemode_server.cfg files. Thanks to Sourcemod, complete configurations and customisable parameters can be loaded into this menu. Which makes it easy in the end for every player with rights to start the mode with his wishes without having any idea of the syntax of the CSGO server.

In addition, the package contains some useful plugins and configurations that can be copied directly to a server. Provided [Metamod](https://www.sourcemm.net/) and [Sourcemod](https://www.sourcemod.net/) are installed.

## Included Plugins/Extentions
| Name | Description | Version |
|----------|----------|----------|
| [Dhooks 2](https://github.com/peace-maker/DHooks2) | A SourceMod extension to hook any game function from within a SourcePawn plugin. This fork adds support to dynamically detour any functions instead of only virtual functions. | 2.2.0 |
| [SteamWorks](https://github.com/KyleSanderson/SteamWorks) | Exposing SteamWorks functions to SourcePawn. | 1.2.3c |
| [Plugin Enable/Disable](https://forums.alliedmods.net/showthread.php?p=1682844) | Move plugins to and from the disabled folder by command. | 1.0.1 |
| [Time Traveler](https://forums.alliedmods.net/showthread.php?t=134288&page=3) | Ever wanted to run a command in the future? In 10 minutes? In a hour? Now you can! Just enter the timer and the command using sm_futex and this plugin will tunnel into the future and execute your command! | 07-28-2016 YoNer |
| [Bypass Password](https://forums.alliedmods.net/showthread.php?p=2738005) | As you know, in CS:GO game, you can not set sv_password on server if there are players in game. Need to be empty server. This plugin block that check, and allow you set sv_password when ever you like. | 02-23-2021 |
| [Random Password Generation](https://forums.alliedmods.net/showthread.php?t=139990) | This is a simple plugin that generates a random password. | 06-15-2015 |
| [Get5](https://github.com/splewis/get5) | Get5 is a standalone SourceMod plugin for CS:GO servers for running matches. | 0.12.0 |
| [Multi 1v1](https://github.com/splewis/csgo-multi-1v1) | The multi1v1 plugin sets up any number of players in 1v1-situations on specially made maps and they fight in a ladder-type system each round. The winners move up an arena, and the losers go down an arena. Players choose between specific round types (for example: "rifle", "pistol", "awp"), and the plugin automatically spawns and gives players the appropriate weapons each round start. | 1.1.10 |
| [Practice Mode](https://github.com/splewis/csgo-practice-mode) | Practice Mode is a sourcemod plugin for helping players/teams run practices. Check out the features and command list below for a better understanding of all the tools practicemode provides. | 1.3.4 |

These plugins improve or enable the game modes. 

## Included Modes
| Name | Based On | Description |
|----------|----------|----------|
| Soft Reset | Server Setup | This is not a real game mod. It is a quick way to reset the serverconfigs without changing the map. |
| Hard Reset | Server Setup | This is not a real game mod. It reload a map and reset the serverconfigs. |
| Full Reset | Server Setup | This is not a real game mod. It restarts the entire server. |
| Casual | [Valve](https://developer.valvesoftware.com/wiki/Creating_a_Classic_Counter-Strike_Map) | Used as [Normal](https://developer.valvesoftware.com/wiki/Creating_a_Classic_Counter-Strike_Map) mode: Like Competitive but with fewer rounds, shorter freezetime per round, no friendly fire, no team collision, free armor and free defuse kit/cutters. Used as [Trigger Discipline](https://developer.valvesoftware.com/wiki/CS:GO_Game_Modes#trigger_Discipline) mode: Gunshots that a player does not hit an enemy with damage himself down to a minimum of 1 HP. |
| Arms Race | [Valve](https://developer.valvesoftware.com/wiki/CS:GO_Game_Modes/Arms_Race) | The game is one perpetual round where killed players respawn at the default spawns. A weapon progression (a number of guns and their order) is defined where players win by making a specified number of kills with each of these weapons. |
| Flying Scoutsman | [Valve](https://developer.valvesoftware.com/wiki/CS:GO_Game_Modes#Flying_Scoutsman) | Only scouts and knives, low gravity, high precision. |
| Danger Zone | [Valve](https://developer.valvesoftware.com/wiki/CS:GO_Game_Modes/Danger_Zone) | *soon* |
| Guardian | [Valve](https://developer.valvesoftware.com/wiki/CS:GO_Game_Modes/Guardian) | Two human players must defend a bombsite as CT or hostages as T against rushing bots. Maps must support this mode to work as intended. |
| Retake | [Valve](https://developer.valvesoftware.com/wiki/CS:GO_Game_Modes#Retakes) | Each round, 3 Terrorists spawn on a bomb site with a bomb being planted and 4 CTs spawn at fixed locations around it or on the other bomb spot. Each player can choose a loadout card at round start. |
| Practicemode | [Practice Plugin](https://github.com/splewis/csgo-practice-mode) | Practice Mode is a sourcemod plugin for helping players/teams run practices. Check out the features and Practicemode | [command](https://github.com/splewis/csgo-practice-mode) list for a better understanding of all the tools practicemode provides. |
| Team Deathmatch | [Valve](https://developer.valvesoftware.com/wiki/CS:GO_Game_Modes/Deathmatch) | Like Armsrace but with free weapon choice and respawns across the map. Kills grant points, depending on the weapon type and if it is currently the bonus weapon. A player wins by scoring the highest after the round's time limit. Only opponents of the other team can be killed. In addition, this mode is also available as a headshot only mode. |
| Free for All | [Valve](https://developer.valvesoftware.com/wiki/CS:GO_Game_Modes/Deathmatch) | This mode is like the Team Deathmatch mode except that everyone, the opponents as well as your own team, are cleared for shooting. And of course this is also available as a headshot only mode. |
| Arena 1v1 | [Multi 1v1 Plugin](https://github.com/splewis/csgo-multi-1v1) | *soon* |
| 1on1 Match | [Get5 Plugin](https://github.com/splewis/get5) | *soon* |
| 2on2 Match | [Get5 Plugin](https://github.com/splewis/get5) | *soon* |
| 5on5 Match | [Get5 Plugin](https://github.com/splewis/get5) | *soon* | 

Some plug-ins have been omitted, such as Deathmatch or Arms Race, which only ask for a little added value. This means that you are not dependent on other plug-ins.

## Custom Commands - *soon* -
| Command | Description |
|----------|----------|
| Bot Count | Behind this is the command "bot_quota", which changes the number of possible bots. | 
| Bot Kick | Kick the Bot from the Server. |  
| Bot Add | If the Bots cant join automaticly, then you can add bots. | 
| Generated Password | Generate a random server password and write it in the chat. | 
| Remove Password | This remove the password, to change the server to a public server again. | 

## Configs
### Adminmenu Custom
This file contains the extra gamesetting configurations with the queries for some individual commands. The game mode can be started via the admin menu and adjusted again and again without having to know anything about the source syntax. 
### Server Config
The server.cfg is the core of the server configs. It contains all the basic settings that are important.
### Gamemodes Configs
The gamemode configs are only links to the existing files. This makes it easy if these files are updated by Valve. Some configs have additional commands that may fix some errors. These are not affected by the Valve updates.
### Gamesettings Configs
These are the config files which can be loaded via the admin menu and which merge the functions of the plugins with the gamemodes. They are also reset again and again through this.
### Mappool INC
These are mappools, very close to the default pools. But they can be easily adapted as desired.
