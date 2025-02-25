
[index]: #index "Back to top"
[terms-of-service]: https://support.na.square-enix.com/rule.php?id=5382&la=1 "Terms of service"
[discord]: https://discord.gg/7TJG9H8Xyf "Join us on Discord"
[download]: https://www.nexusmods.com/finalfantasy14/mods/1054?tab=files "Download on nexusmods.com"

[general-idea]: https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/general-idea.png "General Idea"
[main-hotbar]: https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/main-hotbar.png "Main Hotbar"
[install-trans]: https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/installation.png "Installation"

[custom-menu-gif]: https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/custom-menu.gif "Custom Menu"
[install-youtube]: https://www.youtube.com/watch?v=CnjSLgj-9QE "Youtube video on how to install"
[install-picture]: https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/installation.png "Picture on how to install"
[comprehensive-controller-guide]: https://docs.google.com/document/d/1q_i5_X01hecbCOZOIN_71zceuSjWSuaN-OJdU6ZPV6s "Comprehensive Controller Guide"

# Fr4nsson's FFXIV Config (FFC) | [Discord][discord] | [Download][download]
A complete config for FFXIV with a clean informational HUD layout. All jobs have their spells already assigned to hotbars. No files have been modified or created by third-party applications, all the files have been created and modified by the game. This is not against [TOS][terms-of-service], it is 100% safe to use.

## Index

1. [About](#about)
2. [Main Hotbar](#main-hotbar-)
3. [General Idea](#general-idea-)
4. [Backup](#backup-)
5. [Installation](#installation--youtube--picture-)
6. [What each files does](#what-each-files-does-)
7. [Custom Menu](#custom-menu-)
   1. [non-pvp](#non-pvp-areas-)
   2. [pvp](#pvp-areas-wolves-den-pier-)
8. [Frequently Asked Questions (FAQ)](#frequently-asked-questions-faq-)
9. [Keybinds](#keybinds-)
   1. [inventory](#inventory-)
   2. [mount](#mount-)
   3. [stance & weapon](#stance--weapon-)
   4. [marking targets](#marking-targets--combat-related-mostly-used-when-playing-as-tank-)
   5. [chat](#chat-)
   6. [general](#general-)
   7. [hud](#hud-)
10. [Controller](#controller--comprehensive-controller-guide-)

## About

This is a complete config for FFXIV that I've been working on for a very long time. It is very time consuming to figure out a good hud layout and then position all the hud elements and after that is done come up with good keybinds for your jobs, and if possible, keybinds that fits logically with other similar spells between jobs and remember, ffxiv has 20 jobs as I'm writing this (31 with professions included).

When you take all that into consideration it is not something that is easily done or something that you'd manage to do right away, it would take a lot of trial and error and you would change binds over time. I've done that journey for you so you can focus on playing the game instead. If you're one that likes to fiddle around with hud and keybinds and find enjoyment in that, like I do, this is probably not for you. This is for the people that don't wanna deal with that.

Obviously not everyone might like the layout or the keybinds, there may also be some stuff that I've missed or some spells that would fit better in a different slot. This is a work in progress after all. If you have any suggestions for improvements, feel free to post it on [discord][discord].

## Main Hotbar <sup>[⮝][index]</sup>
![main-hotbar][main-hotbar]

## General Idea <sup>[⮝][index]</sup>
![general-idea][general-idea]

## Backup <sup>[⮝][index]</sup>
1. Make sure the game is not running! 
2. Navigate to your ffxiv config location on your computer, it is usually under<br>
   <code>Documents\My Games\FINAL FANTASY XIV - A Realm Reborn</code>
3. Make a copy of the following items and put them somewhere safe<br>
   <code>FFXIV.cfg</code><br>
   <code>MACROSYS.dat</code><br>
   <code>FFXIV_CHR</code> folders
5. Done

## Installation | [Youtube][install-youtube] | [Picture][install-picture] <sup>[⮝][index]</sup>
1. Make sure the game is not running! 
2. [Backup](#backup-) your current config, installing this config will overwrite almost everything you have.
3. [Download][download] the correct resolution config
4. Navigate to your ffxiv config location on your computer, it is usually under<br>
  <code>Documents\My Games\FINAL FANTASY XIV - A Realm Reborn</code>
5. Open the zip file you downloaded 
6. Extract <code>FFXIV.cfg</code> and <code>MACROSYS.dat</code> into <code>FINAL FANTASY XIV - A Realm Reborn</code> folder and replace when prompted.
7. Extract files INSIDE of <code>CharacterData</code> into each folder starting with <code>FFXIV_CHR</code> and replace when prompted.
8. Done

![Installation][install-trans]

## What each files does <sup>[⮝][index]</sup>
<pre>
Fr4nsson's FFXIV Config.zip
|
|- FFXIV.cfg       : Settings in System Configuration.
|- MACROSYS.DAT    : Macros (Shared Tab).
|- CharacterData
   |
   |- ADDON.DAT    : UI Settings such as HUD and window layouts.
   |- COMMON.DAT   : Settings in Character Settings.
   |- CONTROL0.DAT : Keyboard/mouse mode settings.
   |- CONTROL1.DAT : Gamepad mode settings.
   |- HOTBAR.DAT   : Hotbar content, (spells placed on hotbars).
   |- KEYBIND.DAT  : Keybinds.
   |- LOGFLTR.DAT  : Chat log filter settings.
   |- MACRO.DAT    : Macros (Individual Tab).
</pre>

## Custom Menu <sup>[⮝][index]</sup>
![][custom-menu-gif]

The menu works by using jobs as a database and then assigning items, macros or gearsets to a hidden hotbar you normally don't use so if you want to change what appears in the menu you'll have to unlock some jobs. You don't need to grab the jobs in order to use the menu, you only need to do that in order to edit the menu. 

The logic behind the menu can be found under <code>ALT + U -> Shared Tab</code>

In order to change what is in the menu you need to change to the job that holds the information you're trying to change and press <code>9</code>.
A hidden hotbar (database hotbar) will appear in the top center of the screen on which you can drag other macros, items, gearsets, mounts or whatever to, when you're done with the changes press <code>9</code> again to toggle the visibility of the database hotbar.

Below is the currently used jobs, what information they contain in the database and where to get them. Switch to a job listed below and press <code>9</code> to toggle the database for that job.

#### Non-PvP Areas <sup>[⮝][index]</sup>

| Job           | Information | Quest                    | Quest Giver | Location                              |
| ------------- | ----------- | ------------------------ | ----------- | ------------------------------------- |
| Botanist      | Expand      | Way of the Botanist      | Leonceault  | Old Gridania (x6.4, y8.3)             |
| Miner         | Collapse    | Way of the Miner         | Linette     | Ul'dah - Steps of Thal (x11,y14)      |
| Fisher        | Dps         | Way of the Fisher        | N'nmulika   | Limsa Lominsa Lower Decks (x7,y14)    |
| Culinarian    | Tanks       | Way of the Culinarian    | Charlys     | Limsa Lominsa Upper Decks (x9,y7)     |
| Alchemist     | Healers     | Way of the Alchemist     | Deitrich    | Ul'dah - Steps of Thal (x9, y13)      |
| Weaver        | Professions | Way of the Weaver        | Maronne     | Ul'dah - Steps of Thal (x13.9, y13.2) |
| Leatherworker | Items       | Way of the Leatherworker | Randall     | Old Gridania (x12.5, y8.2)            |
| Goldsmith     | Hunt        | Way of the Goldsmith     | Jemime      | Ul'dah - Steps of Thal (x10, y13)     |
| Armorer       | Misc2       | Way of the Armorer       | G'wahnako   | Limsa Lominsa Upper Decks (x10,y15)   |
| Blacksmith    | Misc1       | Way of the Blacksmith    | Randwulf    | Limsa Lominsa Upper Decks (x10,y15)   |

#### PvP Areas *(Wolves' Den Pier)* <sup>[⮝][index]</sup>

| Job           | Information | Quest                    | Quest Giver     | Location                               |
| ------------- | ----------- | ------------------------ | --------------- | -------------------------------------- |
| Bard          | Expand      | Way of the Archer        | Athelyna        | New Gridania (x15,y12)                 |
| Machinist     | Collapse    | Savior of Skysteel       | Stephanivien    | Ishgard - Foundation (x8.1,y10.1)      |
| Dancer        | Dps         | Shall We Dance           | Eager Lominsan  | Limsa Lominsa Lower Decks (x9.8,y12.0) |
| Red Mage      | Tank        | Taking the Red           | Distraught Lass | Ul'dah - Steps of Thal (x14.1,y11.7)   |
| Black Mage    | Healer      | Way of the Thaumaturge   | Yayake          | Ul'dah - Steps of Nald (x7.3,y12.4)    |

## Frequently Asked Questions (FAQ) <sup>[⮝][index]</sup>

<details><p></p>
<summary>What version am I using?</summary>
You can always view your current version of the config by opening the macro menu 
<code>ALT + U</code> go to the <code>Shared Tab</code> and in the bottom right check the macro with the <code>Bread Icon</code>. Compare the version number to the newest version on nexusmods to see if you have the most current one.
<br><br><br><br><br><br></details>

<details><p></p>
<summary>Is this against TOS? can I get banned for using this?</summary>
No, this is not even a mod, it's only a config so it is 100% safe to use. There is no external files added, all the files have been created by the game and modified by the game. No files have been modified or created by third-party applications.
<br><br><br><br><br><br></details>

<details><p></p>
<summary>I've added the Sage and/or Reaper to the menu but it doesn't save, every time I switch it reverts back</summary>
If you want to include Sage in the custom menu you need to

1. Switch to job <code>Alchemist</code> (Alchemist job holds database information regarding healer jobs in non-pvp areas)
2. Press <code>9</code> a new hotbar will appear in the top center of the screen
3. Press <code>SHIFT + G</code> to bring up your gearsets, and drag the sage gearset onto the top center hotbar
4. Press <code>9</code> again to toggle the visibility of the top center hotbar

For Reaper you will follow the exact steps above, just replace <code>Alchemist</code> with <code>Fisher</code>. 

To do this in pvp-areas, tp to <code>Wolves' Den Pier</code> and follow the exact steps above but replace <code>Alchemist</code> with <code>Black Mage (Healer)</code> & <code>Dancer (Dps)</code> 

For more information on how the custom menu works, see [Custom Menu](#custom-menu--).
<br><br><br><br><br><br></details>

<details><p></p>
<summary>In expandable menu, when I click on job change icon, nothing happens, whats wrong?</summary>
Wrong gearset name, make sure at least one of each job has a gearset with default name, gunbreaker gearset should be <code>GNB(ilvl)</code> for example.<p></p>

If this happens in PvP areas it's because you're not currently a compatible job for PvP, i.e. professions and blue mage won't work in pvp area with custom menu since they don't have pvphotbars. 

Switch to a compatible job by bringing up gearset menu <code>SHIFT + G</code>.
<br><br><br><br><br><br></details>

## Keybinds <sup>[⮝][index]</sup>

#### Inventory <sup>[⮝][index]</sup>
```
I                   = Open all bags
SHIFT + B           = Open character screen, armoury chest and all bags and sort them (I mostly use this one)
SHIFT + I           = Open Chocobo Saddlebag
CTRL  + I           = Armoury Chest
```
#### Mount <sup>[⮝][index]</sup>
```
SHIFT + H           = Single Seat Mount
CTRL  + H           = Multiple Seat Mount
```
#### Stance & Weapon <sup>[⮝][index]</sup>
```
Z                   = Sheathe/Unsheathe Weapon
SHIFT + Z           = Change stance (Try it when holding a weapon, sitting or just standing with weapon sheathed)
```
#### Marking Targets / Combat Related (Mostly used when playing as Tank) <sup>[⮝][index]</sup>
```
ALT   + 1           = Mark primary target to attack
ALT   + 2           = Mark secondary target to attack
ALT   + X           = Mark target to ignore
ALT   + F           = Set Focus Target
ALT   + R           = Ready Check
ALT   + C           = Countdown
CTRL  + M           = Waymark Menu
SHIFT + M           = Signs Menu
```
#### Chat <sup>[⮝][index]</sup>
```
ALT   + S           = Switch chat mode to Say
ALT   + Y           = Switch chat mode to Yell
CTRL  + Y           = Temporarily switch chat mode to Shout
ALT   + P           = Switch chat mode to Party
ALT   + A           = Switch chat mode to Alliance / Raid
ALT   + G           = Switch chat mode to Free Company / Guild
```
#### General <sup>[⮝][index]</sup>
```
8                   = Toggle Keybind bar
9                   = Toggle Database bar
L                   = Limit Break
Mouse5              = Confirm (Used to spam through dialog or spam it when turning in items for seals at GC) 
NUMPAD 0            = Confirm (Used to spam through dialog or spam it when turning in items for seals at GC)
Mouse4              = Cancel
Mouse3              = Auto-run
NUMPAD 1            = Toggle spell effects/names
NUMPAD 2            = Toggle spell effects/names
NUMPAD 3            = Toggle spell effects/names
NUMPAD 4            = Toggle spell effects/names
NUMPAD 5            = Toggle spell effects/names
INSERT              = Toggle spell effects/names, preset 1 (all)
DELETE              = Toggle spell effects/names, preset 3 (limited)
HOME                = Return
CTRL + HOME         = Return (Eternity Ring)
END                 = Teleport Menu
Print Screen        = Screenshot
ALT + U             = Macro Menu
ALT + NUMPAD PLUS   = Continuously increase volume until stopped by pressing NUMPAD -
NUMPAD -            = Stop volume increase (Macro cancel)
NUMPAD +            = Toggle Master Volume On/Off
NUMPAD *            = Helm Visor
NUMPAD /            = RP Walk
SHIFT + ENTER       = Chat fullscreen
SHIFT + G           = Gear sets
G                   = Free Company / Guild Menu
H                   = Housing Menu
J                   = Journal / Quest Log
K                   = Key items
O                   = Friend list
SHIFT + O           = Party Members
CTRL  + O           = Party Finder
CTRL  + L           = Cross-world Linkshells
U                   = Duty Finder
P                   = Spells
SHIFT + P           = PvP Spells
, (comma)           = Currency
. (dot)             = Challenge Log
```
#### Hud <sup>[⮝][index]</sup>
```
Scroll Lock         = Toggle visibility for ALL hud elements (Nice for screenshots)
SHIFT + Scroll Lock = Toggle visibility on some hud elements (Clean Hud)
Arrow Keys          = Select a hud element in hud editor and use key to move hud element by pixel
CTRL + NUMPAD 0     = Toggle Hud Editor
CTRL + NUMPAD 1     = Hud Preset 1, config default (The one I play with)
CTRL + NUMPAD 2     = Hud Preset 2, larger
CTRL + NUMPAD 3     = Hud Preset 3, like Hud Preset 1, gauges and hp reversed
CTRL + NUMPAD 4     = Hud Preset 4, like Hud Preset 2, gauges and hp reversed
```
## Controller | [Comprehensive Controller Guide][comprehensive-controller-guide] <sup>[⮝][index]</sup>
```
Autorun
Left Analog Stick (Move It) then press L1

Sheathe/Unsheathe Weapon
L1 + R1 or L3

Sprint
R3 or double tap L2 then Dpad Up

Virtual Mouse
L1 + R3

Zoom In/Out
L1 + Right Analog Stick (Move It)
```
