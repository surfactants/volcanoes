# volcanoes
realistic volcanoes (and volcanic features?) for vintage story

shamelessly forked because i haven't done code mods and i can't find any primers for landforms on the wiki (or anywhere else). thank you to [the original author](https://github.com/itsELRe) for making this public and providing something well-structured, well-commented, and easy to read.

i also haven't written in C# before, so this will be interesting

## planned features
### types
#### cinder cones:
- perfect talus slopes, look up angles of repose and determine appropriate materials (tuff? scoria)
- flat or jagged tops
- small
- short-lived, so typically extinct
- can be part of larger volcanic system as the terminus of a sealed conduit

#### composite
- seems covered by the existing model but i haven't actually run the mod to check yet :x
- medium
- lava domes (not always!)
- steep but big
- magma chambers, conduits
- https://commons.wikimedia.org/wiki/File:Volcano_scheme.svg

#### shield
- very large
- very shallow slope
- very active (very fluid)
- mafic (basalt/peridotite)
- commonly volcanic islands
- magma chambers, conduits
- lava tubes?

#### mud volcanoes?
- wide variety of sizes/temps, but typically pretty small and hot
- would this require mud as a separate fluid type? can i even do that? is viscosity a thing??? i don't think so

#### extinct volcanoes?
for the most part this seems covered by regular game generation, cinder cones notwithstanding.

could seamounts be a thing?

### intrusions?
this one is interesting and could serve as the basis for a system based on magma chambers as the primary driver.

these features could then appear as either molten or cooled. (closer to surface = higher chance of being cooled? or should it be a whole cooled system, though with the chamber's world height still influencing it heavily)

- dikes
- sills
- necks
- batholiths
- laccoliths
- lopoliths

### eruptions???
seems necessary

#### larger volcanic systems?
- supervolcano calderas?
- lava fields?

## additional notes
- i havent found travertine yet, if that doesnt form terraces already investigate that too, but as a separate mod
- is columnar jointing possible to adequately represent in a voxl game? microblocks are nice but not so good for angles, and it seems awfully inefficient for a static generated feature)
- split/copy this into a discrete design doc
- geology additions as a potential dependency for rock types, or at least a compatibility patch