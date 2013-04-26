dragonchan
==========

A prototype script to transform any /b/ thread into a dragon slaying match.

Set up (or hijack) any thread using the template below and copy paste it's ID into this URL:


# Offical Domain
- Hosted on AppFog: `http://dragonslayer.eu01.aws.af.cm/[thread_id]`

# Domain Mirror's
- `http://slayer.pw/[thread_id]`
- `http://dragon.slayer.pw/[thread_id]`
- `http://mlp.pw/[thread_id]`


Disclaimer
==========
I`m not posting this threads, random people have been doing that. I have no control over it. If you have complains about the spam, sage the threads yourself.

If you have complains about being banned for posting too many dragon threads in one day, well, its not my fault either.

Please don`t spam with dragon threads or you will end up ruining it for other people.


Thread Template:
================
_Allways check this page for the correct template before posting. rules will be updated as the game evolves_
```
ITT: /b/ dragon slayer raid!

Rules:
This huge motherfucking dragon appears out of nowhere.
This thread last 2 digits x300 define its HP (plus a flat 3000)

If your ID starts with a number you are a HEALER.
If your ID starts with a vowel you are a BARD.
If your ID starts with a "/" or "+" you are a PALADIN.
If your ID ends with a "/" or "+" you are a DEATH KNIGHT.
If your ID starts AND ends with a "/" or "+" you are DRAGONBORN.
If your ID starts with "W","R","L","C" or "K" you are a WARLOCK.
Otherwise you are a KNIGHT

Your last 2 digits represent the damage you do
If you roll under 11 you DIE! (your posts will no longer do damage)

HEALERS revive fallen soldiers by targeting them and rolling an EVEN number
BARDS are here to motive troops! each time they post an image the next 3 posts will do bonus damage!
KNIGHTS can critical hit by rolling 5 or 0
KNIGHTS avenge fallen soldiers by targeting them and rolling an EVEN number. Avenging does more damage for the glory of the fallen mate.
PALADINS can avenge AND revive!
WARLOCKS can summon minions by posting an image. The last 2 digits of the image filename will be added to his damage. if his roll last digit matches his minion last digit he BURSTS massive damage.
DEATH KNIGHTS can continue attacking after they die. they will do x3 damage when dead but only 2/3 when alive.
DRAGONBORN can avenge and revive when alive, and will transform into a Death knight after death. this is the ultimate class!
you can be avenged/revived 6 times max
If you roll 00 or 69 you REVIVE everyone! their damage will count again!
The boss will enrage bellow 20% HP, the minimum roll will be 22. however, he will no longer heal himself

I have a webpage to track things, I will post a link to it here.
```



Changelog
=========
__v1.6- 27-04-2013__
   - New Class: 'Dragonborn'
   - Code Cleanup and new sprites
   - Changes to death knight damage output
   - Changes to warlock summon system
   - Adding element mechanics
   - Boss minimum HP is not set to 16.000

__v1.5- 24-04-2013__
   - New Classes: 'Death Knight' and 'Warlock'
   - Added memcache so it doesn`t stress the api
   - Replies to the killer blow now display bellow the winner notification
   - Small fixes on the autoupdater CSS

__version 1.4.5 - 22-04-2013__
   - Massive interface changes
   - new domain: `http://slayer.pw/{THREAD_ID}`
   - new domain: `http://dragon.slayer.pw/{THREAD_ID}`


__version 1.4.1 - 21-04-2013__
   - added: Top deaths stats
   - added: Top bard buff stats
   - adjustments to the fight template

__version 1.4 - 20-04-2013__
   - Added an ajax self updating status panel
   - JS Bookmarklet that opens the status panel on any /b/ thread
   - Fixed bug with bard buff only working on pair number roll

__version 1.3.1 - 19-04-2013__
  - added a json export of the current game `$THREADID/json`

__version 1.3 - 19-04-2013__
  - New classes: "Paladin" and "Bard"
  - New global bonus damage mechanic (Bard Buff)
  - Added Top Healer and Top Avenger information
  - Max revive now display a row for each resurection
  - Boosted monster HP by a flat 3000
  - Max revive count incresed from 3 to 6
  - Max avenge count incresed from 3 to 6

__version 1.2 - 19-04-2013__
  - OP is now a regular player. his posts will no longer be ignored

__version 1.1 - 16-04-2013__
  - Incresed chance of avenge/revive
  - Incresed Boss total HP ratio

__version 1 - 15-04-2013__
  - Class system. Knights and Healers
  - New target systems.
  - knights target for more damage
  - Healers target for revive
  - Max 3 targets
  - boss will enrage when bellow 20% HP
  - boss will heal for every kill he does
  - 69 added to the lucky mass revive roll

__v0 - 14-04-2013__
  - First game prototype
  - Last 2 digits represent damage
  - Rolls under 11 die
  - Rolls for 00 will revive everyone
