# NT-RPG-Configs-And-Assets

Third party config files in this Repository are for use with [NT-RPG](https://github.com/NeumimTo/NT-RPG) are a set of configurations from random users, who were willing to share their work to provide basic examples.

These configs might not be always up to date to latest.
-

The conf files in this repository use an additive style of stats; Where in the total sum of the bonuses are used as the bonus, not the highest value (NT-RPG defaults)

Because of this you **must** use the Settings.conf provided;
**or** change `line 61` in your in your personal Settings.conf from `"WEAPON_MERGE_STRATEGY":2` to `"WEAPON_MERGE_STRATEGY":1`

**_NOTE_**
To solve an issue related to a change in Sponge; in global.conf in your main sponge-server directory find and change
`max-entities-within-aabb=8` to `max-entities-within-aabb=64`

Otherwise some skills will not function correctly.
