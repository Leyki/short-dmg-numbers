### What it do

It divides the damage you deal by the value set in the script, by the default being `10000`. This can be changed to your liking via editting the `divisor` value found in `tera-short-dmg-numbers\settings.json`. The module can be set to load disabled by setting `enabled` to false as well. There's also in-game commands, wow.

There's also a preset file for completely blocking damage from certain skills, booling them to `false` will do the trick. `tera-short-dmg-numbers\damage_block_preset.js`

#### In-game Commands

* ***`smn`***  *`[on/off]`* turns on and off the whole module functionalities.
######
* ***`smn`*** *`divisor` `new divisor value(number)`* sets a new damage divisor.

*Note: Settings will be autosaved if using Caali's proxy when exitting the game. I have no idea why it's broken with pony's proxy, will probably fix it later /shrug.*