*************************************************
READ ME file for rtsmod
by Michael Chervenak
Created: 2/4/20
latest edit: 2/21/20
*************************************************


*************************************************
Description
*************************************************
Brings RTS like systems to Quake 4, like Unit production buildings. Build a Command Center
to gain access to a barracks and vehicle depot. Send harvesters to collect the resource that
is spawned on the map to purchase the barracks and vehicle depot. purchase marine units from
the barracks and vehicles from the depot with resources.

Control your units around the map and lead them to the enemy base to destroy it.
If you die you lose.

*************************************************

changelog:
2/4/20

blaster.cpp
	- num_attack from 1 to 11
machinegun.def
	- spread from 2 to 5
Machinegun.cpp
	- altfirerate to firerate

2/8/20
SysCVar.cpp
	rm_thirdperson = 0 changed to 1
	rm_thirdpersonrange = 80 changed to 200
	rm_thirdpersonheight = 0 changed to 50

2/10/20
PlayerView.cpp
	-commented thirdPerson bool line 518
		-Allows HUD in Third person camera

2/13/20
	-tried to sync aim and bullet travel

2/15/20
	-edited ui in game and main menu
2/21/20
	adjusted third person camera 
	enabled buymenu (doesnt showup)
