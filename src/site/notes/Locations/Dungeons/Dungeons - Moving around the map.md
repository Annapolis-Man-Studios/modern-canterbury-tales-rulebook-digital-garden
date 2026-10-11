---
dg-publish: true
title: Dungeons - Moving around the map
---

Given a dungeon layout of something like this

|           | Col 1             | Col 2               | Col 3                | Col 4             |
| :-------- | :---------------- | :------------------ | :------------------- | :---------------- |
| **Row 1** | [Start]           | [Enemy: Rock Golem] | [Treasure]           | [Event: Slippery] |
| **Row 2** | [Enemy: Cave Bat] | [Trap Door]         | [Enemy: Rock Golem]  | [Empty]           |
| **Row 3** | [Event: Healing]  | [Enemy: Cave Bat]   | [Empty]              | [Treasure]        |
| **Row 4** | [Empty]           | [Treasure]          | [Status: Exhaustion] | [Boss]            |
The party begins the dungeon at `[Start]` and makes their way towards the next floor as a unit. The players have to agree as a team which room to traverse into before moving to a room. Each room can have one of 5 occurrences:
- enemy battles (including boss battles)
- events - occurrences which inflicts a status upon all party members for the rest of the dungeon
- treasure - attachable or n-use items/gold which can be split upon party members or hoarded by one party member
- trap doors - the turn instantly ends and the team starts over from a space adjacent to the trap door space
- empty - nothing occurs, free space
As mentioned before, **the DM should never reveal the contents of each room to the players unless a player uses an item that reveals the map**. 

Next: [[Dungeons - Events]]
Previous: [[Dungeons - Basic Rules]]