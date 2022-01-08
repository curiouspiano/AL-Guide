# Upgrading
There are a variety of ways to improve your chances to upgrade gear. We will also provide some snippets in [this file](src/base_chances.js) for example "base upgrade chances". (NOTE: These are not completely accurate, the chances vary based on several factors)


## Improving your chances
All those methods have different costs associated with them, which you will need to balance with the worth of an item. 

### Using a higher tier scroll
new_upgrade_chance = old_base_upgrade_chance * 1.2 + 0.01. Note, that this is the same for all scrolls of a higher tier so there is no use in using anything but the very next tier. The formula for compounds is slightly different and due to cscroll prices it is most of the time not worth to use a higher tier scroll

### Using an item
Using an item slowly builds up a bonus to the upgrade chance. However this process is really slow and best used for compounds. When trying to get the next accessory level it is best to switch out a used accessory with a new one and do the compound with the new one

### Failstacking
Failing upgrades adds a so called failstack to the upgrade chance of any other item of the same level and the level blow. Succeeding an upgrade removes all failstack at once. This can be used by failing cheap items on purpose to then have a higher chance for an upgrade with an expensive item. You might not see the effect at first, because the actual base chance is lower than the minimum chance you upgrade with, but failstacking will increase the chance eventually

### Offerings
Offerings like primlings `offeringp`, prims `offering` and primX `offeringx` will increase the upgrade chance most notably. These items will also enhance any other boni the item already has, so a prim on an item with some failstacking will get you a higher improvement to the upgrade chance than using the prim on an item without any failstacking

### Feeding offerings (NOT recommended)
You can "feed" offerings to an item by "upgrading" it with the offering and no scroll. It will always work but increase the chance only very little for the very high cost associated with this. Failstacking is the better option.