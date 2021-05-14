# ! You're probably looking for [pret/pokecrystal](https://github.com/pret/pokecrystal) !

## Pokémon Crystal (Personalized)

This is a disassembly of Pokémon Crystal with some minor QoL changes.

### Improvements
#### Done
* Sprinting/Running/Go Fast with B button (same speed as Bicycle)
* Instant text option

#### To-Do
* Remove artificial save delay
* Shorten beep for Low HP
* Restore GS Ball Celebi Event

### Bug Fixes
#### Done
* BRN/PSN/PAR catch rate increase changed from 0 to +5
* Moon Ball affects Pokemon that evolve by Moon Stone instead of Burn Heal
* Love Ball now checks for the opposite gender instead of the same gender
* Heavy ball now uses correct weight value for Kadabra, Tauros and Sunflora
* Fast ball now boosts catch rate properly instead of for just 3 pokemon
* In-Battle Ellipses lowered 2px
* Fixed inconsistency in some trainer overworld sprites

#### To-Do
* `HELD_CATCH_CHANCE` has no effect
* Glacier Badge boost doesn't apply in specific scenario
* Battle transitions don't account for enemy level (the fix for this seems to be causing much longer and glitchy transitions, might not implement if i can't figure out why)

### Credit
* [pret/pokecrystal](https://github.com/pret/pokecrystal) - used as the starting point + tutorials (bug fixes + improvements)
