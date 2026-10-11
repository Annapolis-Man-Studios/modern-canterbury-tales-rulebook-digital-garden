---
dg-publish: true
title: Terrains - Encounters
---

Encounters in terrains are in the form of battles. These battles are similar to those found in dungeons and some sidequests. The format of the information of these encounters could look something like this:

	| 2 | Encounter | Ambush: 2x Fog-Stalking Hares. |
	| 5 | Encounter | Combat: 1x Stone-Crag Sentinel. |
	| 7 | Encounter | Ambush: 2x Shadow-Mist Wisps. |
	| 8 | Boss | Summit: The Guardian of the Veil. |

This means there are encounters in areas 2, 5, and 7, and the boss is located in area 8.

The enemy listings will be located in the same generated file like so:

	#### Fog-Stalking Hare
	*Small, twitchy, and prone to sudden strikes.*
	* **Health:** 10
	* **Attack:** 3
	* **Defense:** 1
	* **Speed:** 8
	* **Diplomacy:** 6 (Can be bribed with food)
	* **Drop:** 10 Gold or nothing.
	
	#### Stone-Crag Sentinel
	*A hulking mass of animate rock and moss.*
	* **Health:** 25
	* **Attack:** 5
	* **Defense:** 4
	* **Speed:** 2
	* **Diplomacy:** 2 (Hard to convince, requires high charisma)
	* **Drop:** Raw Gemstone (Value 50 gold).
	
	#### Shadow-Mist Wisp
	*Ethereal entities that drain morale.*
	* **Health:** 15
	* **Attack:** 4
	* **Defense:** 0
	* **Speed:** 6
	* **Diplomacy:** 4 (Can be reasoned with using magic lore)
	* **Drop:** Mist Essence (Consumable item).
	
	---
	
	### Boss: The Guardian of the Veil
	*A towering, armored knight made of living mountain slate. He stands at the end of the path to ensure only the worthy pass.*
	
	* **Health:** 60
	* **Attack:** 7
	* **Defense:** 5
	* **Speed:** 3
	* **Diplomacy:** 1 (Cannot be negotiated with)
	* **Special Attack: "Mountain’s Grasp"** – The Guardian slams his hammer into the earth, causing rocks to erupt under the players' feet. Deals 10 damage to all team members and reduces their Speed by 2 for the next turn.
	* **Drop:** The Cader Key (Required for progression) + 150 Gold.

Next: [[Terrains - Treasure]]
Previous: [[Terrains - Rest areas]]