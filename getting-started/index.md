---
layout: default
title: general_observations
nav_exclude: true
---

Login flow:
- Name
- Confirm create character
- Password
- Retype password
- Email
- Ask for colour
- Choose an alignment. What does this do??
- Choose race
- - Can see help for races
- - No note that your available races are restricted by alignment
- Choose sex
- Choose class
- - Can see help for classes
- Choose subclass
- - No notice that these were restricted by alignment
- - Can see help for each subclass
- Dropped into game with several settings enabled.
- - Toggles:
- - - autoeq (hiding all unused eq slots)
- - - autoexit (shows exit string above objs in room)
- - - autogold (???)
- - - autoloot (take all carryable loot from corpses)
- - - autosac (automatically sacrifice empty corpses)
- - - autosplit (split gold gained in combat with party)
- - - autosurvey off (why?)
- - - battlespam (show all lines in combat)
- - - brief off
- - - colour (decided by initial selection)
- - - formstate (show %health of party members)
- - - map (show minimap)
- - - nochallenge (cannot be dragged to arena)
- - - nofollow off
- - - nolore off
- - - noreckoning off
- - - noresurrect (cannot be resurrected by players)
- - - nosummon (cannot be summoned)
- - - nowake off
- - - notify (see players on notify list log in)
- - - prompt (show prompt)
- - - pursuit off (chase fleeing targets)
- - - quiet off
- - - sacrifice_all off
- - - mobile on (unused)
- - - favskills off

Initial room has a parchment scroll that tells you how you can move. There is nothing to indicate how to look at the scroll. `look at scroll`. Someone new to muds may be entirely stuck here, frustrated.

Hints channel begins spamming you immediately. 'channels' lists a number of things that are also covered by the toggle menu, and do not necessarily have easy ways to toggle on and off from here if you did not know about the `toggle` command.

toggle afk seems superfluous, as 'afk' also exists, and allows you to set an afk message. Remove this toggle?

In channels, notify, quiet, battle spam, and form state are all covered by the toggle menu. Battle spam cannot be toggled via channel command. Form state is not a channel. Remove notify, battle spam, and form state from `channels`?

Prompt could maybe go on `prompt` command if no argument given, and the on/off for showing it require `toggle prompt`

channels
channel        status
---------------------
announcements  ON
gossip         ON
OOC            OFF
yell           ON
flaming        OFF
war            ON
quotes         ON
tells          ON
auction        ON
music          ON
notify         ON
quiet mode     OFF
battle spam    ON
form state     ON
hints mode     ON
Your current prompt is: <%hhp %mm %vmv> 
You currently have no flag.
You will not see player flags on any channels.