---
layout: default
title: Common Conventions
nav_order: 1
parent: Getting Started
---
# Common Conventions
---
As a text based game, there are a few common conventions in use here that you may not be familiar with.

The shortest explanation is that only words necessary for executing a command are typically recognized. For example, in Interactive Fiction games, it is common to do something like, `look at <object>`, while in Sentience, this would be `look <object>`.

| action | natural example | sentience syntax | generic sentience example |
|:-------|:--------|:----------|:-------|
| look at an rock | `look at rock` | `look rock` | `look <keyword>` |
| look at an additional rock | `look at second rock` | `look 2.rock` | `<verb> #.<npc>` |
| put a rock into a box | `put rock into box` | `put rock box` | `put <item> <container>` |
| step into a portal | `walk through portal` | `enter portal` | `enter <keyword>` |
| interact with a door or container | `open the door` | `open east` | `open|close|lock|unlock <container|direction>` |
| interact with furniture | `sit on the couch` | `sit couch` | `sit <keyword>` |

{: .note}
`look in <container>` is a notable exception to the above conventions.

You can further combine these as needed as part of your interaction with the world. To get the sword "Vengeance" from Scarm's Coffin, equip it, and attack a guard, you would use a set of commands such as the following:

```
get vengeance coffin
equip vengeance
kill guard
```