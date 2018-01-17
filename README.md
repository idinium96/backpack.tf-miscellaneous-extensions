# backpack.tf - Miscellaneous Extensions
_____________________________________________
This is an userscript to add miscellaneous functionality to backpack.tf (which I would have liked for myself).
Currently included is:
* In inventories add a Sort by paint
* In inventories add a Sort by spell
* In inventories add a Sort by level
* Allow the reversion of the groups from a sort
* Filter by class on backpack.tf/effect/<effect>
* Marketplace link for any item



## Installation
_____________________________________________
Use an extension which can execute userscripts (F.e. [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) for [Chrome](https://www.google.com/chrome/) or [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)  for [Firefox](https://www.mozilla.org/firefox))
and then install using this link: [backpack.tf extended sorting.user.js](https://github.com/NetroScript/backpack.tf-miscellaneous-extensions/raw/master/backpack.tf%20extended%20sorting.user.js).

(Or paste / install it manually for your plugin)

## Changelog
_____________________________________________


#### 0.1.8

Added:
* In the class menus on the effect / unusual pricing pages add Miscs as class (meaning unusuals which you can equip over other unusuals) (Should I miss some there feel free to send me a message)

#### 0.1.7

Fixed:
* Marketplace link appearing multiple times when hovering multiple times
* Marketplace link now only appears if no price is known

#### 0.1.6

Added:
* In the popover of an item, show a link to the marketplace item (So you have a link even when there are no sales)

#### 0.1.5

Added:
* Like with my custom sorting methods you can now reverse the groups of the already implemented sorting methods (so you can switch f.e. between old to new and new to old when sorting by time)

#### 0.1.4

Added:
* On the pricelist page of unusual effects you now can filter them by class like the unusual by item page

#### 0.1.3

Fixed:
* added missing spell (Halloween Fire)
* reset last sort when non custom sort was used
* fixed filtering for items with custom sorts (meaning added complete new filtering which additionally searches for f.e. strange parts, spells, custom name)

Added:
* Sort by level
* Possibility to write code to change the order of the backpack pages

#### 0.1.2

Added:
* generic sort can now ignore empty pages
* spells are visually marked (green for 1 spell, red for multi-spell)
* added sorting using spells

#### 0.1.1

Fixed:
* generalized Sorting functions
* removed emtpy item containers which were used for spacing the normal inventory pages

Added:
* sorting the single pages (f.e. sorting Paints by price)
* meta data to automatically update the script

### 0.1

* Released with additional sort by paint


## Planned features
_____________________________________________
* Sort by Effect
* Sort by Lowcraft
* Sort by Killstreak
* Sort by Tier (and wear secondary)
* Sort by discout



## Preview
_____________________________________________

Paint sorting:
![Preview](https://raw.githubusercontent.com/NetroScript/backpack.tf-miscellaneous-extensions/master/preview1.png)



Spell sorting (green dots mean a single spell, red dots mean multi spell):
![Preview](https://raw.githubusercontent.com/NetroScript/backpack.tf-miscellaneous-extensions/master/preview2.png)



Level sorting:
![Preview](https://raw.githubusercontent.com/NetroScript/backpack.tf-miscellaneous-extensions/master/preview3.png)



Filter the unusual hats by class on the unusual effects pricelist page :
![Preview](https://raw.githubusercontent.com/NetroScript/backpack.tf-miscellaneous-extensions/master/preview4.png)
