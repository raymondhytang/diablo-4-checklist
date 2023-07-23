# Diablo IV Checklist

To view the checklist [click here](http://raymondhytang.github.io/diablo-4-checklist/).

This checklist was created by adopting the source code from the [Dark Souls 3 Cheat Sheet](https://github.com/ZKjellberg/dark-souls-3-cheat-sheet) created by [Zachary Kjellberg](https://github.com/ZKjellberg).

The walkthrough is thanks to [PowerPyx's Diablo IV Collectible Locations Guide](https://www.powerpyx.com/diablo-4-all-collectible-locations-100-completion/).

## Contribution Guide

If you are interested in contributing to this guide, I welcome Pull Requests.

For some background on how the guide code is written, here is a sample item on the checklist:

```
<li data-id="side_quests_3_14" class="f_side_quest"><b>Scorched Debts</b><br>In Bastard’s Pass, available when first arriving. Pick up the ledger and travel to the marked area to kill Andreea. Head to Ked Bardu and speak to the three people, then go to the marked area in Crown of Fiends and search for Lyruk. Head to the summoning ritual and kill Orrostus.</li>
```

The **data-id** is a unique ID used to store the user's progress. For example, ***side_quests_3_14*** is the 14th side quest in region 3. New data-ids must be used in ascending order, but you can place the new entries anywhere within a region.

The **class="f_side_quest"** field is used for the filtering system. This task provides the user with a side quest, so we use **f_side_quest**. The full list of filter classes is:

| Class   | Description |
|---      |--- |
| f_side_quest  | Side quests |
| f_side_dungeon  | Side dungeons |

If none of these filter classes match, use **class="f_none"**.
