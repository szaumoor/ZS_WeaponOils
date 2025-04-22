# ZS_WeaponOils
This small mod simply adds a new class of items called "weapon oils". Essentially, they are consumable potions that apply a somewhat mild melee/ranged effect to your weapons. They are distributed to stores so far and a few select creatures. Compatibility with IWDEE not established yet, because I can't be bothered to check what stores there are and how to decide which stores make the most sense to place the items in. Feel free to offer feedback on this.

Note that you cannot stack oils with themselves or each other, they are all set up so only one of them can be active. This of course can be abused with any other mods that may add similar items. If any of you can think of another mod that adds stuff like this, I can add some code to handle it so balance is not broken.

Also, I'm not a good writer, so the descriptions are pretty boring, and most of the icons were lazily made, but I think they're visually  distinguishable enough.

These are the list of available oils:

### Igneous Oil
Base price: 500 gp

This oil will make your weapons inflict fire damage when coated with it. Since it is a natural substance, it won't be stopped by Magic Resistance.

STATISTICS:

Damage: 1d2+1 fire damage (Save vs. Breath for half)<br>Duration: 1 turn

Weight: 1

### Caustic Oil
Base price: 500 gp

This acidic oil will make your weapons inflict acid damage when coated with it. Since it is a natural substance, it won't be stopped by Magic Resistance.

STATISTICS:

Damage: 1d2+1 acid damage (Save vs. Breath for half)<br>Duration: 1 turn

Weight: 1

### Gelid Oil
Base price: 500 gp

This super-cooled oil will make your weapons inflict cold damage when coated with it. Since it is a natural substance, it won't be stopped by Magic Resistance.

STATISTICS:

Damage: 1d2+1 cold damage (Save vs. Breath for half)<br>Duration: 1 turn

Weight: 1

### Scintillating Oil
Base price: 500 gp

This electrically charged oil will make your weapons inflict electric damage when coated with it. Since it is a natural substance, it won't be stopped by Magic Resistance.

STATISTICS:

Damage: 1d2+1 electric damage (Save vs. Breath for half)<br>Duration: 1 turn

Weight: 1

### Arcane Oil
Base price: 1000

This oil is charged with magical energy and will make your weapons inflict magic damage when coated with it. Since it is a magical substance, it may be stopped by Magic Resistance.

STATISTICS:

Damage: 1d4+2 magic damage<br>Duration: 1 turn

Weight: 1

### Noxious Oil
Base price: 1200

This noxious oil will make your weapons inflict poison damage when coated with it, and may indeed poison the target if they can't resist it. Dealing with poisons is a delicate task, only those of remarkable dexterity can use it without risking poisoning themselves.

Since it is a natural substance, it won't be stopped by Magic Resistance.

STATISTICS:

Damage: 1d2+1 poison damage<br>Poisoning: Save vs. Death at +2 or suffer 6 points of poison damage over 2 rounds<br>Self-damage: User suffers the same effect if their Dexterity is below 16<br>Duration: 1 turn

Weight: 1

### Drow Soporific Oil
Base price: 1750

This oily soporific poison was created originally by the drow. When coated with it, affected creatures may fall in a deep slumber for 1 turn. Dealing with poisons is a delicate task, and as such, only those of remarkable dexterity can use it without risking poisoning themselves.

Since it is a natural substance, it won't be stopped by Magic Resistance.

STATISTICS:

Damage: None<br>Poisoning: Save vs. Death or fall into a deep slumber for 1 turn. Receiving further damage will awaken the target.<br>Self-damage: User suffers the same effect if their Dexterity is below 16<br>Duration: 1 turn

Weight: 1

### Sanctified Oil
Base price: 2500

This oil was blessed by a priest with anti-undead properties, which will make your weapons inflict extra damage to undead, with a chance of weakening them. While it is technically a magically-infused substance, it pierces through the defenses of undead as if they had no such resistances, including Magic Resistance.

STATISTICS:

Damage: +4 irresistible damage against the undead (no effect against others)<br>Special: Undead targets must Save vs. Death at +2 or become Slowed and Weakened (-3 Strength, -2 Armor Class) for 10 seconds. This effect doesn't stack with itself.<br>Duration: 1 turn

Weight: 1

### Profane Oil
Base price: 2500

This oil was infused by a priest with Negative Plane energies, which will make your weapons inflict extra damage to living creatures, with a chance of weakening them. While it is technically a magically-infused substance, it pierces through the defenses of the living as if they had no such resistances, including Magic Resistance.

STATISTICS:

Damage: +4 irresistible damage against the living (no effect against others)<br>Special: Living targets must Save vs. Death at +2 or become Slowed and Weakened (-3 Strength, -2 Armor Class) for 10 seconds. This effect doesn't stack with itself.<br>Duration: 1 turn

Weight: 1

### Kuo-Toan Oil of Stunning
Base price: 2000

The recipe of this oily poison was originally created by Kuo-Toan alchemists. When coated with it, hit creatures may become stunned for 2 rounds, unable to defend themselves. Dealing with poisons is a delicate task, and as such, only those of remarkable dexterity can use it without risking poisoning themselves.

Since it is a natural substance, it won't be stopped by Magic Resistance.

STATISTICS:

Damage: None<br>Poisoning: Save vs. Spell at +2 or become stunned for 2 rounds.<br>Self-damage: User suffers the same effect if their Dexterity is below 16<br>Duration: 1 turn

Weight: 1

### Dragon Bile Extract
Base price: 3000

This very rare, and very expensive poison was created by harvesting pure bile from dead dragons. When coated with it, hit creatures will have their Strength sapped. Dealing with poisons is a delicate task, and as such, only those of remarkable dexterity can use it without risking poisoning themselves.

Since it is a natural substance, it won't be stopped by Magic Resistance.

STATISTICS:

Damage: +1 poison damage (non-dragons)<br>Poisoning: Save vs. Death or have Strength and movement speed reduced by half for 5 rounds. Only true dragons are unaffected by this effect, and as such, close relatives like faerie dragons, dragonborn, half-dragons and wyvern will be affected.<br>Self-damage: User suffers the same effect if their Dexterity is below 16<br>Duration: 1 turn

Weight: 1

### Dragonsbane Oil
Base price: 4000

This oily poison was specifically formulated for one purpose: to cause pain and death to dragons and other draconic creatures. When hit by it, dragons, half-dragons, and wyverns suffer damage and have their breath drained out of their lungs, while other living targets are less affected. Dealing with poisons is a delicate task, and as such, only those of remarkable dexterity can use it without risking poisoning themselves.

Since it is a natural substance, it won't be stopped by Magic Resistance.

STATISTICS:

Damage: 1d3+1 poison damage (non-draconic only), or 1d6+2 poison damage (draconic only)<br>Special: Dragons, half-dragons and wyverns suffer the following effects if Save vs. Spell is failed:<br>  – APR reduced to 1/2 for 1 round<br>  – Strength is reduced by 40% for 2 rounds<br>  – Casting speed, THAC0, and Armor Class are damaged by 5 points for 3 rounds<br>  – The pain it causes may affect concentration: 50% chance of disrupting Stoneskin or Improved Invisibility.<br>Self-damage: User suffers the same effect if their Dexterity is below 16<br>Duration: 1 turn

Weight: 1

---

## Compatibility
Should be compatible with everything as far as I know. Please offer feedback on balance and the supply of oils throughout the game if you try this.

## Known issues
The noxious oil sometimes seems to not offer log feedback indicating whether the poisoning was resisted or not. I don't think it affects functionality though.

Additionally, applying the oils through the inventory will be through a button that states "drink potion", which doesn't make sense (trust me, don't drink them for real, you'll die), but I don't think that can be helped.

## Future improvements
- Maybe introduce it into some random treasure
- Maybe add a few more oils (precision, keen edge, perhaps)

Offer feedback on this if you can and what else could be added or modified.

## Acknowledgments and credits
Many thanks to zenblack for providing great icons for the oils, as well as other modders such as The Artisan in the discord servers that helped me figure out some of the issues and ideas I've had for this mod.

