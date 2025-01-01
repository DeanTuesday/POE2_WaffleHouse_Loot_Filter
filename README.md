# POE2_WaffleHouse_Loot_Filter

### How to Use
Download the desired filter or pull the latest commit.
Place the desired filter into the directory: `C:\Users\<YOU>\Documents\My Games\Path of Exile 2`
Note: do not place the filter into the `OnlineFilters` directory.

In game: open your options menu -> click on the Game tab -> select the desired filter from the Item Filter dropdown menu -> click save

### How to Personalize
There is a section in each Waffle House loot filter where you can add base items you would like to see. To reach it, open the filter in any text editor like Notepad++, and search for PERSONALIZED LOOT FILTER OVERRIDES. There is an example under that section which is currently commented out. It looks like this:
```
# WEAPON & ARMOUR BASE ITEM OVERRIDE
#Show
#    Mirrored False
#    Corrupted False
#    Rarity Normal Magic
#    BaseType == "Rattling Sceptre" "Stoic Sceptre" "Omen Sceptre" "Expert Heavy Crown"
#    SetFontSize 40
#    SetBackgroundColor 100 100 100 255
```

To add your own items, uncomment that section by removing the # at the beginning of each line starting at #Show, and update the BaseType argument according to your preferences.
Example:
```
# WEAPON & ARMOUR BASE ITEM OVERRIDE
Show
    Mirrored False
    Corrupted False
    Rarity Normal Magic
    BaseType == "Expert Crackling Quarterstaff" “Omen Sceptre”
    SetFontSize 40
    SetBackgroundColor 100 100 100 255
```
