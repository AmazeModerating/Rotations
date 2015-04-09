Avicus Rotations
=========

This repository stores configuration files for the servers on The Avicus Network. Each file listed under the "servers" directory corresponds to a server on Avicus and contains the information for that server.

Configuration:
* `min` is the proportion of players required to start a match. For example: a rotation with a `min` value of 0.5 would require teams to be 50% full in order for a match to start.
* `max` determines the maximum number of players that can join. Normal users can join until the team is at full capacity, but when `max` is 1.5, for example, staff and upgraded users can join until the team is 150% full.
* `maps` is the list of maps in the rotation. Once all maps have been played, the server restarts.
* `selection` is used when a game lobby is in use (SG for example). The game lobby will randomly select maps for players to vote on. The highest voted map will be played. It will default to selecting 3 maps, but this can be configured with the `options` variable.
