---
layout: default
title: Configuration Settings
nav_order: 7
parent: Getting Started
---

# Toggling Settings
Sentience has a number of settings that can be toggled to adjust your play experience, with some on by default, but others requiring your intervention to set.

| toggle | default | effect |
|:-------|:--------|:-------|
| afk | off | Toggles the 'afk' setting. Easier to just use the command directly, as that allows you to specify a reason. |
| autoeq | on | Hides the display of empty gear slots, only showing slots where you currently have items equipped. |
| autoexit | on | Shows the `[Exits: <directions>]` line below the room description. |
| autogold | on | Automatically attempt to take money from slain foes. |
| autoloot | on | Automatically attempt to take all objcts from slain foes. |
| autosac | on |  Automatically sacrifice empty corpses after looting. |
| autosplit | on | Splits looted coins betwen party members. |
| autosurvey | off | Attempts to automatically survey while on ships. |
| battlespam | on | Hide lines where no damage is done in combat. |
| brief | off |  Hides map and room descriptions. |
| colour | varies | Toggles colour printing. | 
| compact | off | Cuts out extra lines before prompt. |
| formstate | on | Shows current health percentages of your party. |
| map | on | Shows the minimap to the left of room descriptions. |
| nochallenge | on | Prevents you from being challenged to arena combat. |
| nofollow | off | Prevents you from being followed. |
| nolore | off | Prevents you from automatically using the lore skill when looking at items or npcs. |
| noreckoning | off | Prevents you from participating in [the Reckoning](reckoning), but you will not get bonus experience. |
| noresurrect | on | Prevents other players from resurrecting you. |
| nosummon | on | Prevents players from summoning you. |
| nowake | off | Prevents players from waking you from sleep. |
| notify | on | Displays a message when players log in. |
| prompt | on | Shows your prompt (see `channels` command to view your current prompt) |
| pursuit | off | If you have the 'pursuit' skill, attempts to chase fleeing opponents automatically. |
| quiet | off | Toggles quiet mode |
| sacrifice_all | off | Allows sacrifice of corpses that still contain items. |
| mobile | on | Currently unused. Tells game to enable bandwidth-saving settings for mobile users. |
| favskills | off | Hides all skills not currently marked as 'favourites'. |

# Bust-A-Prompt!
Your prompt is information that appears at the end of every room, round of combat, or update. By default, it will show your current hp, mana, and movement, but this can be modified.

There are a large number of codes that you can use to modify your prompt, and they are detailed in `help prompt` in the game, but are also reproduced here for your convenience. Be aware that you can also set [colour](Colour in Sentience) codes in your prompt.

Default prompt: `{B<{X%h{Bhp {X%m{Bm {X%v{Bmv>{X`

Prompt options:

| code | effect |
|:-----|:-------|
| %h | Current HP |
| %m | Current mana |
| %v | Current moves |
| %H | Max HP |
| %M | Max mana |
| %V | Max moves |
| %x | Current experience |
| %X | Experience needed to next level |
| %g | Gold on hand |
| %s | Silver on hand |
| %a | Alignment |
| %r | Room name |
| %e | Exits in NWSEUD format |
| %c | Line break|
| %w | Current weight |
| %W | Max weight |
| %q | Quest points |
| %Q | Quests completed |
| %p | Practices |
| %P | Pneuma |
| %t | Trains |
| %b | Bank balance |
| %C | Weight of carried coins |