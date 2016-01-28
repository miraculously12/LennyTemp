# All Features Added in this Fork


## Commands
 - Ophelp
   * Shows how to use OP
 - Split [ID] [Count]
   * Splits a player
 - Team [id] [team (r,g,b)]
   * Changes a players Team (you might have to split to see the changes though)
 - Resetvirus
   * Turns special viruses (from OP's) into normal ones
 - Ban [IP]
   * Bans a IP and sends a MSG
 - Banlist
   * Lists banned IPs
 - Clearban
   * Clears ban list
 - Op [ID]
   * Makes player OP
 - Dop [ID]
   * De-OPs a player
 - Rop
   * Resets op
 - Pfmsg [delay] [duration] [x to repeat] [msg1] [msg2] [etc...]
   * Periodically sends a force message (seconds)
 - Spfmsg []
   * stops pfmsg
 - Pmsg [delay] [duration] [x to repeat] [msg1] [msg2] [etc...]
   * Periodically sends a message (seconds)
 - Spmsg []
   * stops pmsg
 - Troll [id]
   * You figure out this one, Its a suprise!
 - Fmsg [message 1] [message 2] [etc...]
   * Forces players to read a message, This is done by changeing leaderboard to msg, freezing players, and change their name temporarily
 - Msg [message1] [message2] [etc...]
   * Changes the leaderboard to a message for a short time
 - kick/killrange [Start] [End]
   * Kicks/kills in a range (eg: killrange 1 10 will kill players whos ids are between them)
 - Nojoin [id]
   * Makes person unable to join
 - Merge [id]
   * forces user to merge
  
## Gamemodes

Id   | Name
-----|--------------
5    | UnlimitPVP - where you split can split indefinitly and rejoin instantly - 1v1 game (created by me)
6    | UnlimitFFA - same as above (unlimited pvp) except in ffa (created by me)
15   | NoCollision teams
16   | NoCollision Zteam
17   | NoCollision Xteam
18   | Leap - Where you leap instead of split, made by Ogarplus
19   | Virus - Where you shoot viruses

## Config

1. showjlinfo: 1 = notifys you if a player joined/left 0 = doesnt notify you (default)
2. showbmessage: 1 = Notifys you about banned people trying to join and autoban msgs 0 = off (default)
3. showopactions: 1 = Notifys you of an OPs Actions, 0 = Off (default)
4. smartbthome: 1 = Automatically sends you back to normal mode after pressing Q proceding an action (default) 2 = off (you need to press Q a lot)
5. maxopvirus: number of special viruses (troll and kill) that is allowed in the game before them all reseting (see the resetvirus command)
6. ejectantispeed: Speed of ejected Anti-Matter
7. serverScrambleCoords: scrambles coordinates 0 is off and 1 is on WARNING, If you turn off, your server could be infested with suicide bots
8. serverMaxConnectionsPerIp: only allows a certain amount of players per ip to prevent suicide bots WARNING, if you set it to bigger than 10, your server may experience many suicide bots
9. auto-ban: Bans an IP after reaching over the amount of clients allowed in serverMaxConnectionsPerIP, 1 = enabled, 2 = disabled (Default)
10. ejectvspeed: Speed of ejected virus
11. SpikedCells: 1 = cells have spikes 0 = they dont have spikes
12. ffaMaxLB: Maximum amount of people to be listed in the leaderboard
13. splitSpeed: Splitting Speed
14. autopause: 1 = on (default) 0 = off

## OP

1. Add 100 mass
2. Rejoin instantly
3. shoot virus
4. shoot Anti-matter
5. shoot troll virus
6. shoot kill virus