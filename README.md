# LootGoblin
## Easiest way to locate Treasure Maps, Resource Maps and to keep track of all items you wanna sell or buy!  
![image](https://user-images.githubusercontent.com/52481026/132117634-e7fd5b71-7dc9-4c25-a989-91f03e9e1e03.png)


## [Click here to download](https://github.com/Hanebu/Loot-Goblin/releases/download/v1.0/LootGoblin.exe)

## How to use

Open the Tome or Treasure Map you want to read.  
Make sure that they are completly visible. However, they don't have to be in the black area of the client.
   ![image](https://user-images.githubusercontent.com/52481026/119891287-1453a800-bf39-11eb-845a-2a7e92ee3461.png)



## Buttons
   ![image](https://user-images.githubusercontent.com/52481026/119892522-85478f80-bf3a-11eb-8cbd-5921807e25e0.png)
   
### Import:
   
   Will scan the screen for the opened Tomes and Treasure Maps.
   
### Export sell:
   
   Will export all active ( ![image](https://user-images.githubusercontent.com/52481026/119893481-b4123580-bf3b-11eb-930e-9ac07977e460.png)
) Mastery Scrolls, Aspect Items and Items in the "Items to sell".
   It will create a string in the clipboard, so you can directly post it in Discord using CTRL+V.
   
### Export buy:
   
   Will export all active ( ![image](https://user-images.githubusercontent.com/52481026/119893481-b4123580-bf3b-11eb-930e-9ac07977e460.png)
) Custom Items in the "Items to buy".
   It will create a string in the clipboard, so you can directly post it in Discord using CTRL+V.

### Example Export string:
```
- ### Valueable Mastery Scrolls ###
  4x Alchemy 12k
  4x Animal Lore 35k
  4x Animal Taming 35k
  5x Discordance 10k
  4x Peacemaking 10k
  3x Poisoning 10k

- ### Trash Mastery Scrolls (2 @ 7k) ###
  1x Arms Lore 7k
  1x Detect Hidden 7k

- ### Aspect Cores ###
 25x Air Core 10k
  8x Earth Core 4k
  6x Poison Core 3k
 18x Shadow Core 6k
 14x Water Core 6k

- ### Aspect Extracts / Distills ###
  3x Air Extracts 10k
  2x Earth Extracts 5k
  1x Lyric Extracts 12k
  1x Poison Extracts 4k

- ### Armor ###
 Invulnerability Leather Cap 50k
 Invulnerability Armor pieces 5k

- ### Books ###
 Codex of Archery 55k
 Codex of Fencing 55k
 Codex of Macing 55k
 Codex of Swordsmanship 55k
 Codex of Shields 55k
 Summoner's Tome 55k
 Taming Bestiary 55k
 Wizard's Grimoire 55k

- ### Services ###
  120 Alchemy 
  120 Blacksmithy 
  120 Carpentry 
  120 Cartography 
  120 Cooking 
  120 Inscription 
  120 Lockpicking 
  120 Poisoning 
  120 Remove Trap 
  120 Tailoring 
  120 Tinkering 
```


## Treasure Maps / Resource Maps / Fishing Maps
After the succesful import of any Map, the location of the Map will be shown on the button (e.g. 1087, 2648).
By pressing the button, [ExploreOutlands.com](http://www.exploreoutlands.com) will be opened with the exact coordinates of the location.

It will also directly show you which Rune Tome and which Recall Rune you should use for this specific location.
Currently are three different number systems supported:

  1. General Map System ([More info](https://forums.uooutlands.com/index.php?threads/outlands-treasure-map.3051/#lg=attachment4455&slide=0))
  2. Witchers Map System ([More info](https://forums.uooutlands.com/index.php?threads/witchers-guide-to-tmaps-how-you-can-and-why-you-should-be-running-your-own-tmaps.3439/))
  3. BlackDragons Map System ([More info](https://forums.uooutlands.com/index.php?threads/blackdragons-advanced-tmapping-guide-auto-tmap-helpers.3654/))

The colored square, next to the Rune Tome, is indicating the Rune Tome color. The number or name, next to the Rune, tells you which rune to recall to.
The number behind the footsteps is the approximately distance from the marked rune to the Treasure Map location in a straight line.

![image](https://user-images.githubusercontent.com/52481026/119893882-36025e80-bf3c-11eb-8392-2bd18500b0b3.png)



## Custom items to sell or buy
To add custom items to buy or sell, simply press ![image](https://user-images.githubusercontent.com/52481026/119897370-985d5e00-bf40-11eb-8b41-f0ab4be14b74.png) on the gump. You can now add you own items to buy or sell. 

The first textbox is the name of the item and should be filled.  
The checkbox indicates if the item will be exported or not.  
The second textbox is the amount, you can enter any string (e.g. "500", "50k" or "5m"). This textbox is optional.  
The third textbox is the price, you can enter any string (e.g. "500", "50k" or "5m"). This textbox is also optional.  
The fourth textbox is the group name, all items with the same group name will be under the same header when exporting.

![image](https://user-images.githubusercontent.com/52481026/119897329-8a0f4200-bf40-11eb-9bbd-4f9e723c4a77.png)



## New in version v1.1   
### BlackDragons Rune System for the Expansion Land added
The new runes locations for the expansion has been added.
Witchers system will follow soon, stay tuned!

## New in version v1.0  
### New Mastery Scrolls and Aspect Items added
Of course the Mastery Scrolls and Aspect Items for 'Year 3 Anniversary Expansion' are added!  
![image](https://user-images.githubusercontent.com/52481026/130442699-5d5e8ea0-a205-4e87-95f1-1195d61894da.png)
![image](https://user-images.githubusercontent.com/52481026/131492844-355c0d1f-b99c-4921-8eef-a085646c35c3.png)


### BlackDragon's Rune System
Added the Rune System of BlackDragon. Now all major Rune Systems are implemented.  
Thanks for everyone who contributed!  
![image](https://user-images.githubusercontent.com/52481026/131493200-d81c39af-776a-44d4-8364-83a23cbaa327.png)


### Item color indicator  
All items are now colored depending on their state.  
Gray: Item not for sale  
Brown: Trash Scroll  
Black: Regular Item  
![image](https://user-images.githubusercontent.com/52481026/121256658-14469700-c8ad-11eb-9495-9bd66021a978.png)

### Added CheckBoxes for Aspect Extracts and Distillations
With the newly added CheckBoxes for Extracts and Distillation you can select very detailed what you want to sell.  
![image](https://user-images.githubusercontent.com/52481026/131469399-12156f48-3947-4e02-ae72-79bcefb2620f.png)

### Link to GitHub
If you press the LootGoblin logo, the GitHub page will be opened. 
Easiest way to check for updates and the download link.

### Bugfixes / Changes
- Fixed a bug where Water Extracts were not imported at all.
- Fixed a bug where the mouse cursor was reverting to its default windows cursor when hovering the ScrollBar area.
- Added a total amount of all Trash Scrolls (does not matter if they are for sale or not).

## New in version v0.2  

### Trash Mastery Scroll price threshold
You can now set a custom price threshold for Trash Mastery Scrolls.  
If you change the value, all Mastery Scrolls that were set to the old threshold will have their price adjusted accordingly.  
![image](https://user-images.githubusercontent.com/52481026/120161379-82c58e00-c1f7-11eb-8e9d-c66b652fe828.png)  

### Sum of each item group and sum of all items for sale
Each item group will now have displayed their sum for all active items displayed in the bottom right hand corner:  
![image](https://user-images.githubusercontent.com/52481026/120161539-b86a7700-c1f7-11eb-87bb-42fe5af11e93.png)  

In the Control gump, you can also see the sum of all sub sums (= total value of all items for sale):  
![image](https://user-images.githubusercontent.com/52481026/120161641-d506af00-c1f7-11eb-936d-2788fc48cb4d.png)

### Bugfixes / Changes
- Fixed a bug where Maps that were surrounded on 3 sides by water were located incorrectly.
- Added hovereffect for the add and remove item buttons.
- Added hovereffect for the sorting buttons.
