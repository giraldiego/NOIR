
# Changelog

## 1.3.4

**Released at**: `Apr-??-2020`

**Info**:
In development...

**Changes**:

- Added [Obscure's College of Winterhold](https://www.nexusmods.com/skyrimspecialedition/mods/20514)
- Added [Immersive College NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/9252/)
- Added [Administer Potions and Poisons to Friendly NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/24127)
- Updated [Soul Cairn HD](https://www.nexusmods.com/skyrimspecialedition/mods/15481) to 5.0
- Updated [Requiem - Alternative Descriptions](https://www.nexusmods.com/skyrimspecialedition/mods/33663) to 2.1
- Updated [Lucien](https://www.nexusmods.com/skyrimspecialedition/mods/20035) to 1.5
- Updated [Requiem Patch Central](https://www.nexusmods.com/skyrim/mods/61621) to 3.16
- Better patch for [Combat Gameplay Overhaul SE](https://www.nexusmods.com/skyrimspecialedition/mods/33767), disabling the following:

```code
- Attacks have a 50% chance to glance off a block instead of bouncing back, letting you attack again
- Attacks in 2H grip get sweeping hitboxes that hit in a 180° arc in front of your character
```

- Included wilmoef's Circlets and Masks with all Robes and Hoods edits
- Fixed some inconsistencies in Minor Arcana for conjured spirits
- Hopefully fixed this time `SkyrimUncapper.ini` not being included in the modlist.
- Added more MCM default options in the patch.
- Disabled Followers' health regeneration after combat, so you need to heal them using the new mod.
- Tweaked [More Bandit Camps](https://www.nexusmods.com/skyrimspecialedition/mods/1994) to duplicate bandits only the 50% of the time.
- Tweaked Requiem - Lucien Patch from `Requiem Patch Central` to include NPCs added to the Lucien's quest.
- Minor fixes to Crafting Location Improved SE

## 1.3.3

**Released at**: `Apr-15-2020`

**Info**:
Added CGO and improved the Heritage patch again, it should be better than the previous one, BEWARE OF THE DIFFICULTY from the new enemies.

**Changes**:

- Added [Combat Gameplay Overhaul SE](https://www.nexusmods.com/skyrimspecialedition/mods/33767)
- Added [Furniture Height Size Fix Enhanced](https://www.nexusmods.com/skyrimspecialedition/mods/32010) as Optional
- Changed [Racial Body Morphs SE - Diverse body types and height by Race and Gender](https://www.nexusmods.com/skyrimspecialedition/mods/20684) to the Subtle version and forwarded its changes to the NOIR patch.
- Updated Heritage patch for Requiem.
- Fixed some missplaced things from Crafting Locationg Improved
- Fixed more informative console incompatibility with EUI
- Fixed LAL quests giving XP when using Experience Mod.
- Restore the vanity mirror to the prison cell in LAL, so you can change your look (but not your race).

## 1.3.2

**Released at**: `Apr-13-2020`

**Info**:
Another update due to perfomance textures update, a better Heritage patch this time.

**Changes**:

- Updated [performance optimized textures for SSE](https://www.nexusmods.com/skyrimspecialedition/mods/21166?tab=files)

## 1.3.1

**Released at**: `Apr-09-2020`

**Info**:
Small update due to perfomance textures update and to include Heritage and Skyrim Unlocked mods as Optional.

**Changes**:

- Updated [performance optimized textures for SSE](https://www.nexusmods.com/skyrimspecialedition/mods/21166?tab=files)
- Updated [360 Movement Behavior SE](https://www.nexusmods.com/skyrimspecialedition/mods/33139)
- Added [DOT CROSSHAIR](https://www.nexusmods.com/skyrimspecialedition/mods/8891)
- Added [First Person Camera Height Fix](https://www.nexusmods.com/skyrimspecialedition/mods/28091)
- Added [Heritage](https://www.nexusmods.com/skyrimspecialedition/mods/30017) (OPTIONAL, see SETUP.md)
- Added [Skyrim Unlocked](https://www.nexusmods.com/skyrim/mods/69420)(OPTIONAL, see SETUP.md)
- Reinstalled [Cinematic Dragon Soul Absorption](https://www.nexusmods.com/skyrimspecialedition/mods/12106?) without gender specific voice.
- Once again, ini changes in skse\plugins\EngineFixes.ini:
  
```[Experimental]
MemoryManager = false
```

In order to avoid CDTs when using Honed Metal features in certain NPCs. I will let that disabled from now on.

## 1.3

**Released at**: `Apr-7-2020`

**Info**:
This version includes snbcj's rebalances to Requiem, a new save is required.

**Changes**:

- Updated Nexus' SSE [Requiem - Mortal Enemies](https://www.nexusmods.com/skyrimspecialedition/mods/27292)
- Updated [Requiem - Dragonborn - Alternative Descriptions](https://www.nexusmods.com/skyrimspecialedition/mods/33663)
- Added [Requiem - Minor Arcana SSE](https://www.nexusmods.com/skyrimspecialedition/mods/25843?tab=files)
- Added [Requiem - Immersive Abilities 1.3](https://www.nexusmods.com/skyrim/mods/96880)
- Added [Requiem - Immersive Divine Blessings 1.31](https://www.nexusmods.com/skyrim/mods/88988)
- Added [Requiem - Standing Stone Rebalance 3.6](https://www.nexusmods.com/skyrim/mods/88988)
- Added [Racial Body Morphs SE - Diverse body types and height by Race and Gender](https://www.nexusmods.com/skyrimspecialedition/mods/20684)
- Added [Circlets or Masks with all Robes and Hoods](https://www.nexusmods.com/skyrimspecialedition/mods/3732)
- Added [More Bandit Camps](https://www.nexusmods.com/skyrimspecialedition/mods/1994)
- Added [Floating Damage](https://www.nexusmods.com/skyrimspecialedition/mods/14332)
- Added [More Vanilla Bandits](https://www.nexusmods.com/skyrimspecialedition/mods/28205)
- Added [Eradicate This Face (ETFF)-SE](https://www.nexusmods.com/skyrimspecialedition/mods/17535)
- Added [Realistic AI Detection 2 SE - Medium Interior, Medium Exterior](https://www.nexusmods.com/skyrimspecialedition/mods/2345)
- Added [All Thieves Guild Jobs Concurrently](https://www.nexusmods.com/skyrimspecialedition/mods/14883)
- Reverted ini edit on SSE Engine Fixes
- Added [Equipment Durability System](https://www.nexusmods.com/skyrimspecialedition/mods/19023)
- Added [Pick Your Poison](https://www.nexusmods.com/skyrimspecialedition/mods/23710)
- Disabled more informative console in order to use Extended UI, but you can activate it anytime for debbuging purposes.
- Fixed not inclusion of Skyrim Uncapper.ini in the previous modlist version
- Fixed Wolves yield a horse meat.
- ini changes in skse\plugins\EngineFixes.ini:
  
```[Experimental]
MemoryManager = true (default false) read documentation
```

Revert if you have CDT with any NPC and Honed Metal dialog.
  
## 1.2.3.5

**Released at**: `Apr-2-2020`

**Info**:
Fixing bugs as they are being reported.

**Changes**:

- Updated [LeanWolf's Better-Shaped Weapons SE](https://www.nexusmods.com/skyrimspecialedition/mods/2017) to 2.1.03  
- Added [Extended UI SSE](https://www.nexusmods.com/skyrim/mods/57873/?)
- Added [Finally First Person Magic Animation](https://www.nexusmods.com/skyrimspecialedition/mods/20375)
- Added [No Disarm (Unequip Instead)](https://www.nexusmods.com/skyrimspecialedition/mods/27188/) (This mechanic is buggy and unfair for DiD players in Requiem)
- Added [Realistic Conversations - No Greetings](https://www.nexusmods.com/skyrimspecialedition/mods/1717/?)
- Added [Serana Dialogue Edit](https://www.nexusmods.com/skyrimspecialedition/mods/16222?tab=description)
- Added [Unread Books Glow](https://www.nexusmods.com/skyrimspecialedition/mods/1296)
- Added [Creepier Daedric Princes](https://www.nexusmods.com/skyrimspecialedition/mods/15854?tab=description)
- Added [Daedratastic Rune Spells](https://www.nexusmods.com/skyrimspecialedition/mods/6359/?)
- Added [Holy Wards](https://www.nexusmods.com/skyrimspecialedition/mods/18535)
- Added [Beautiful Honey Signs - 2K Overhaul - 1K Optional](https://www.nexusmods.com/skyrimspecialedition/mods/1269)
- Added [Requiem - Dragonborn - Alternative Descriptions](https://www.nexusmods.com/skyrimspecialedition/mods/33663)
- Added [Noxcrab's Tweaks](https://www.nexusmods.com/skyrim/mods/78134)
  
- Enabled the use of Circlets and Masks with all Robes and Hoods
- Fixed a misplaced pot in WinkingSkeever on Distinct Interiors mod
- Disabled Vanilla and Vampire Start in ASLAL (some user reported not working)
- Disabled Surprise me! Start in ASLAL (to avoid the two above)
- Disabled Vanity Mirror in Prison Cell (it lets you change race and that's not recommended in Requiem)
- Disabled Import option for Inigo, Hoth and Lucien in NFF (not safe)
- Increased Friend and Ally hits allowed in combat to 2 (Requiem default is 1)
- Changed load order for NWSFollowerFramework to stop the warning message.
- Tweaked Experience.ini to take in account future inclusión of Atlas - Map Markers increase in discovereable places `iXPDiscOther=0`
- Reverted the following to avoid CDT with Lod and Honed Metal in Markarth (read documentation):

```skse\plugins\EngineFixes.ini:
[Experimental]
MemoryManager = false
```

## 1.2.3.4

**Released at**: `Mar-28-2020`

**Info**:

Still tweaking values in Skyrim Uncapper and Experience to my liking (review my settings before using it).

**Changes**:

- Updated [Requiem - Classic Alchemy Overhaul (R-CAO)] to 6.2

- Added Requiem - Classic Food and Drink (R-CFD) SSE

- Added UNP Female Body Renewal

- Added BlockSteal - Prevents accidentally pick up

- Added Mum's the Word

- Removed UNP Blessed Body

- Changed the placement of the Khajiit textures mods in MO left pane

- Changed the placement for the UNP Body Replacer to a more fitting section

## 1.0

**Released at**: `Feb-29-2020`

**Info**:
This is the initial release of the modlist based on NOISE 2.1.2.

**Changes**:

Added mods:

```+Immersive Animations
+Dual Wield Improved Animation SSE
+Blocking Animation Pack SSE
+360 Walk and Run Plus
+Cinematic Dragon Soul Absorbtion
+Nemesis
+Baka Haeun UNP
+Immersive CBP Config
+CBPC - CBP Physics with Collisions
+HDT-SMP (Skinned Mesh Physics)
+XP32 Maximum Skeleton Special Extended
+UNP Blessed Body
+TMB Vanilla Armors and Clothes SSE (Vanilla Style)
+Feminine Khajiit Textures (Grey Cat and Leopard) [UNP]
+[Cover Khajiits]
+Immersive Dragons
+Predator Vision - Night Eye and Thermal Vision Overhaul
+Equipment HUD SE
+3PCO - 3rd Person Camera Overhaul
+Skyrim Save System Overhaul
+Cooking Pots in Inns
+Lucien
+Hoth
+Unique Uniques SE
```

[OLD CHANGELOG](https://drive.google.com/open?id=1k5D8ccTMw-L-WZ3G8gjjZQsicsVRXf6Y)