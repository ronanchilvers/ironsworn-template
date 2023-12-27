---
created: 2023-07-07 11:29
---
![[banner.jpg]]

> [!abstract]- The Adventure Seed
> Add the adventure seed here. Give a rough overview of the general plot - what's happening, what the characters are supposed to do, etc

# Scenes
```button
name Create new scene
type command
action Quickadd: New Scene
```
^button-new-scene
```dataview
List
From -"_templates"
Where contains(file.tags, "scene") 
Sort file.name desc
```

# Characters
```button
name Create new character
type command
action Quickadd: New Character
```
^button-new-character
```dataview
List 
From -"_templates"
Where contains(file.tags, "character")
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

# Creatures
```button
name Create new creature
type command
action Quickadd: New Creature
```
^button-new-creature
```dataview
List
From -"_templates"
Where contains(file.tags, "creature") 
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