# 1.0.2
+ Tweaked the min and max pitch for the TTS for dead players. The min was previously 0.1, but I didn't realize how broken it was with any pitch below 0.5.
+ The new min pitch is 0.5, and the max pitch remains at 2.0, but will default to 1.5 when generating a new config.

# 1.0.1
+ Fixed typo that caused the TTS pitch for dead players to not sync up properly.

# 1.0.0
+ Changed the lower limit for TTS volume in the config for dead players to 0, to effectively mute them while still displaying their TTS text.
+ Removed the config for the TTS audio pitch for dead players, and replaced with a lower and upper range.<br>
Each player will now have a random pitch for each level based on the min and max pitch in the config. Pitch may not always sync up perfectly between players if players have differing min/max pitch values.

# 0.1.2
+ Minor tweaks

# 0.1.1
+ The text UI for TTS of dead players should properly disappear with distance as normal.

# 0.1.0
+ Release