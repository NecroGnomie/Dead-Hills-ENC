|========================================
 Enchanter Dead Hills Routine. 
 
 Version 1.10 (modified)
 
 	Adjusted to end the mission at the end of path 2. 
     	To put macro back to finishing mission edit the Return Path section:
			line 698 "${CampNum}<2" to "${CampNum}<3"
			line 702 "${CampNum}==2" to "${CampNum}==3"
 
 
Credit:

	Blitter - Author
	PussyFoot - Edited for Enchanter use

  Modified for Raid Druid usage on other toons - Necrognomie:
  
	Modified the "get instance" for timing and close quest windows on all toons
 	Removed SpellStun, added 4th manatapping Nuke
 	Re-aligned spacing
	Added support for Large Modulation Shards
	Added support for AA purchase
	Set INI to be character name based
	Added a "group status" check and pause to wait for mana/end as needed.
	Added Robe setting to INI
	Added RankName support

  Needed files:
	wait4res.inc
	AApurchase.inc
	SpellRoutines.inc
	hillsinto.ini - Path File! 
	
  Needed Plugins:
	MQ2MoveUtils
  
 Run the macro once to generate the "CDH_ToonName.ini" file, then edit to fit your group.

 There are a number of places you can edit this macro to better fit your preferences.
 Please look it over before using.
|========================================
