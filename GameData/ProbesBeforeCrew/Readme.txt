Probes Before Crew Readme v2.9.3
by _Zee


=================================  (1) Income Sliders  =================================

The very nature of this mod significantly reduces both Science income and Funding income.
You may need to use settings that are different from what you are used to.
Seriously, don't just press the default "Hard" button and call it a day. I call that "Impossible Mode".
There are users that challenged themselves to see if this is even possible and I never heard from any of them getting past the Moons of Kerbin.

Recommended minimum for the Science slider is 70%.
	- Planet packs are one of the few circumstance I can imagine that could justify a lower
	  setting, but none are officially supported yet.
	  
Recommended minimum for the Funding slider is 80%.
	- If you use MANY part-adding mods, you may need to set it HIGHER.
	  Remember, more part-mods means you'll be spending more on unlocking and using parts.


=================================  (2) CommNet Settings  =================================

PBC has a planned design for antenna availability and synchronizes antenna ranges and unlock timing with the 
rest of the parts on the techtree and the SOI's they collectively grant you access to.

When it's time to start sending missions to Duna and Eve, you'll be able to get by with just a T2 R&D facility and a T2 Tracking Center. 
However, there will definitely be gaps in coverage at certain points in the year and without T3 R&D you'll have no mid-range(20G) relays yet. 
The player generally has enough funds to consider purchasing the T3 Tracking Center at this point though, so its 
an interesting choice during your career when to invest in the T3 Tracking Center (and the T3 R&D for access to the mid-range relay).

In order to scale the effectiveness of low-end antenna and high-end antenna together correctly, 
	= = =   THE SUGGESTED DSN MODIFIER TO USE IS (0.35)   = = =  
Antenna ranges are set with this value in mind. It will make talking directly to the KSC back home easier in the early-game and harder in the end-game.

Your personal preference for using multiple groundstations will dramatically change the game as well. Choosing not to use them will make things more challenging.
Early-game relay-antennas get an advantage when talking directly to Kerbin, but not to other relays. 
This is important because without groundstations, you'll need to utilize relay-to-relay comms MUCH more frequently.

Finally worth noting, is the Probe Control Loss setting. It is possible to play with Full Control Loss enabled, 
but it will make getting your first probe into orbit at new celestials a bit more tricky.

	- Remember, if you play with RemoteTech then the Antenna range changes made by PBC automatically do NOT apply 
		and RemoteTech takes precendence on everything "Comms" related. 
	  
================================= (3) Science Definitions =================================

This is just a quick note for users who wish to alter the Science Definitions made by this mod.
If you prefer to see the science reward values of vanilla or a different mod,

First find the
	= = Zs_Science.cfg
file contained within 
	= = GameData/ProbesBeforeCrew/_Core
and delete/remove the file.
You could also rename the EXTENSION to disable the file, for example
	= = Zs_Science.txt

The |ScienceParamModifier| mod by DMagic packaged with this mod also overhauls Celestial Body Science Multipliers.
If you deleted/removed/renamed the Zs_Science.cfg file above, then you will probably also want to delete this entire folder
	= = GameData/ScienceParamModifier
	
Everything else will remain as PBC defines, including where the experiment parts are supposed to be on the tech tree.


================================= (4) Kerbalism Users =================================

Starting with Kerbalism version 3.0.0, PBC's science reward tweaks will defer to Kerbalism's science reward tweaks when you 
have enabled Kerbalism's Science Module. If you prefer PBC's system of collecting and turning in science (much more
like vanilla) then follow Kerbalism's instructions for turning off it's Science Module. No editting of PBC's files is necessary,
PBC will automatically enable/disable its Science Defs depending on the Kerbalism setting you've selected.


================================= (5) END =================================


