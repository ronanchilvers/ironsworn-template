---
created: 2023-07-07 11:29
banner: "![[banner.jpg]]"
banner_y: 0.41714
banner_lock: true1
---
# Sessions
```button
name Create new session
type command
action Quickadd: New Session
```
^button-new-scene
```dataview
List
From -"_templates"
Where contains(file.tags, "session") 
Sort file.name desc
```

# Characters
```button
name Create new character
type command
action Quickadd: New Character
```
^button-new-character
```button
name Create new creature
type command
action Quickadd: New Creature
```
^button-new-creature
```dataview
List 
From -"_templates"
Where contains(file.tags, "character") or contains(file.tags, "creature")
Sort file.name
```

# Maps
```button
name Create new map
type command
action Quickadd: New Map
```
^button-new-map
```dataview
List 
From -"_templates"
Where contains(file.tags, "map")
Sort file.name
```

# Setting
```button
name Create new setting detail
type command
action Quickadd: New Setting
```
^button-new-setting
```dataview
List 
From -"_templates"
Where contains(file.tags, "setting")
Sort file.name
```

# Places
```button
name Create new place
type command
action Quickadd: New Place
```
^button-new-place
```dataview
List 
From -"_templates"
Where contains(file.tags, "place")
Sort file.name
```

# Mechanics
```dataview
List
From -"_templates"
Where contains(file.tags, "mechanics") 
Sort file.name
```