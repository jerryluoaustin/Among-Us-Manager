<div align="center">
<h1>Among Us Manager</h1>  

[![Bot Image](https://i.imgur.com/K6V81tr.png)](https://discord.com/api/oauth2/authorize?client_id=756743033181044827&permissions=12787776&scope=bot)

Among Us Manager is a discord bot using reactions to manage muting and deafening in Among Us, allowing you listen to live reactions during the round while you're dead.

[![Invite Link](https://i.imgur.com/zkYVDa9.png)](https://discord.com/api/oauth2/authorize?client_id=756743033181044827&permissions=12787776&scope=bot)
</div>

&nbsp;

## Reactions
Among Us Manager uses discord reactions to smoothly manage muting and deafening. After creating a game, use the reactions under the embed to control the game. Because the bot deafens everyone alive, dead people can hear the thoughts of everyone alive, or the screams of someone dying.

&nbsp;
<div align="center">

<img src="https://i.imgur.com/50kbgh6.png">

</div>

&nbsp;

*Unfortunately due to discord bot limitations, only 10 voice edits are allowed every 5 seconds per server, freezing the bot if multiple games in a single server change stage at once*

## Commands
Start Command | Starting description
--------|---------
`am.start` | Host new game a in current voice channel. Only one game is allowed in each voice channel
`am.join` | Joins existing game in voice channel
`am.joinall` | Force joins everyone in the voice channel into the game
`am.endgame` | Terminates existing game in voice channel. Only players in the game are able to use this command during a 6 hour time period after game is created
**Host Game Commands** | **Host description**
`am.round or 🔇` | Start the round (do tasks). Deafens everyone alive, unmutes everyone dead
`am.meeting or 📢` | Call a meeting. Undeafens everyone alive, mutes everyone dead.
`am.lobby or ⏮` | End of game, back to lobby. Undeafens and unmutes everyone
**Player Commands** | **Round description**
`am.dead or ☠` | Toggle status to dead. Undeafens during rounds to discuss with other dead players and hear other players alive
**Management Commands** | **Management description**
`am.promote <@user>` | Promotes player to host  **Host only**
`am.kick <@user>` | Removes player from game
`am.leave` | Leave game