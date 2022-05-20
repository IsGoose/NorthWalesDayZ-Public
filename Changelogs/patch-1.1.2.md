# Patch 1.1.2
Date of Release: TBA [IN ACTIVE DEVELOPMENT]  
__This Page will be Updated Continuously Throughout Development of this Patch__

## Current Development Subject
* Damage System Overhaul (See Notes)
* New Unconscious Animations & Implementation

## Additions
* Antihack Bans now Routed Via Ban API to make Antihack Bans Easier to Check, and Easier to Remove False-Positives

## Small Changes & Fixes
* Long Antihack Logs will now be Logged Properly and not cut off due to Character Limit

## Notes
The Default Epoch Damage System is slightly scuffed in the sense that it is entirely based on the "HandleDamage" Event Handler.
This Event Handler will actually fire up to 5 Times Every time the player is Hit, and will apply Blood Damage Every Time.
The New Implementation will only apply Damage Once, and will properly differentiate which Body Part was Hit (Head, Body, Legs, Arms)
Now Damage is scaled better, and Weapons that Previously Did quite low Damage (Pistols, 5.56mm Weapons, etc), are now actually effective.
The Aim of this is to Hopefully shift the Meta, and make previously "shit" weapons more Viable for Players, and therefore more fun as players
can now use more than just a select few Weapons. Also this new System also stops those hilarious RangeFinder Kills in the Kill Feed ;)  
The New Unconscious System Aims to somewhat remove the old clunky System, by replacing it with a sort of tunnel Vision Effect combined with a short actual unconscious period, as well as the Unconsious Effect not lasting nearly as long, and less of a deciding factor in a Fire Fight
