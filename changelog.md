#### What's New
On this page you'll find a list of all updates made to Three-D Velocity since it's open-source push on January 21, 2017. The binary distribution as well as the Master branch incorporate all of the changes noted here; therefore, to get the latest version, either pull the latest Master branch or get the binary distribution.

##### Version 2.15, released on mm/dd/yyyy

###### Fixed
- The server now contains a `--log` option. The choices are `info, debug, messages, error, and chat`. You can specify log options by using the `--log level1,level2,...` syntax, like this: `--log error,debug`. The server will tell you what log levels are in use so you can make sure the levels you want are in place ([#32](../../issues/32))
- In a Death Match game online, if you created a bot, the bot would not be counted as a player in the game, so even if it was just you and one or more bots, you would not be permitted to start the game. Now, bots are enrolled as part of the player count in an online Death Match game ([#28](../../issues/28))
- When many weapons were fired, the server would experience a lag. The server now consumes data faster which greatly increases response time. This fixed an issue where sometimes bots would not clear from the server immediately upon destruction ([27](../../issues/27))

##### Version 2.11, released on 04/29/2018

###### Fixed
- When the player selects "Act as spectator," TDV no longer crashes ([#16](../../issues/16))
- TDV would sometimes crash with an invalid status error when checking for playing status of a sound ([#30](../../issues/30))
- The "message of the day," if set on the server, will now show upon connect to the server instead of a little while after connecting ([#22](../../issues/22))

##### Version 2.10, released on 04/30/2017
###### Added
- Admins can now control the server from the console; in-game changes are no longer permitted ([#17](../../issues/17))

###### Fixed
- When loading a game from the main menu, the player no longer hears two engines. Previously, the player would hear an idle engine, and their own engine which was throttling up ([#5](../../issues/5))
- In Multiplayer Mode, when a second player joins a private game, TDV no longer crashes ([#13](../../issues/13))
- In parts of the game involving close-quarters combat, the player's orientation would get stuck according to the last known direction of their aircraft ([#14](../../issues/14))
- TDV would behave unexpectedly if the player provided a blank IP address and/or call sign when connecting to the server. Blank input in these fields is no longer allowed ([#15](../../issues/15))

##### Version 2.0, released on 04/29/2017
###### Added
- The multiplayer mode is available in this version. Instructions for running the server are found elsewhere in this document ([#7](../../issues/7))

##### Version 1.01, released on 01/23/2017
###### Fixed
- Music no longer plays over death scenes in Mission Mode ([#1](../../issues/1))
- In Training Mode, the player is no longer allowed to flip their aircraft unless required or in free-range combat with Fighter 3 ([#2](../../issues/2))

##### Version 1.0, released on 01/21/2017
###### Added
- Initial source code push