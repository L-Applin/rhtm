# rhtm
Platformer / Puzzler / Musical game


Music platformer  
Musical 2D puzzle platformer  
Title ideas : "Rhythm" ...

Music interaction with level design will help player solve a mix of platforming and puzzling  

# General ideas

## Concept
Interaction between music, level design and player actions:  
* Player actions will influence the music of the game.  
* These changes in music will be reflected in the level itself. Ex. :    
  * Door opens, spike removed, platform appears, etc;  
  * Colors,  
  * Enemies;   
  * General change (gravity (?), level rotation (?), teleportation (?), etc).

Visual level elements (moving platform or obstacle, doors, etc) can be heard in the music.


## Gameplay
Listening to the music is required to solve puzzles/reach the end of the level :
* Matching rhythm.
* Matching pitch (melody, harmony, arpegio).
* Musical hints located through levels ?


## Musical style :
* Synthwave / 80’s synthesizer 
* Vangelis / Daft punk / Depeche mode / Stranger things
* SFX as musical elements.
* Contrasting :
  * Empty, slow at the begining of levels.
  * High tempo / arpegiated at the end, depending of the level.
  * Each level’s music is similar, but has it’s own characteristics.
* Fast paced :
  * High player speed.
  * Fast and tight control.
  * Lots of moving elements.			
  * In the styel of « Super meat boy ».
  * Flight ? Boost ? Glide ?

* Physics oriented :
  * Pushing objects around.
  * Falling objects as obstacles.
  * Gravity to help or hinder the player.

* Simple graphics :
  * Basic shapes : Square, triangle, simple polygon
  * Filled colors.
  * Grayscale-ish: Game elements playing sound / music have brighter color.

## Game elements

### Player
todo

### Obstacles
#### Lethal obstacles
They must be avoided or else the player will be killed and forced to restart
* Spikes,
* Spike pits,
* Crushers (piston).
* Saws.

#### Non-lethal
They prevent the player from advancing in the level without killing them. Will be solve through collecting keys or resolving sound shape puzzles (see next point 2.3. Puzzle solving elements).
* Locked doors,
* Too long gaps, etc.

#### Platforming 
Bodies that the player must naviguate through
* Static platform,
* Moving platform: straight lines, oblique lines, pendulum, going up / left / right / down. elevators, slopes, irregular structures

### Puzzle solving
#### Keys
Sprites in the level that the character will have to collect. Removed from the world and goes into player inventory upon contact. They usually have a positive effect on the level as they are required to solve the level/puzzle :
* Unlock doors
* Remove spikes
* Add platform
* Etc
They are permenent, the door will stay unlocked if player has the « key » in it’s inventory.

#### Sound shapes & Sound platforms
Sound shapes are sprites (balls, boxes, etc) moved around the level by the player : Pushed around, Jumped onto to move, pushed by piston or conveyor belts or other elements. They have an effect (like a key) on the level only when placed on a specific Sound platform. Only works when the « sound shape » is in place, sitting over a sound platform. Different effecst can happend based on which sound platform a sound shape is placed upon. Levels may have many sound platform and sound shape.

### World
#### Puzzles
Puzzle brainstorm
* Keys: 
  * Key open doors.
  * Key open door, access to sound shape  and/or sound platform.
  * Key removes spike, let player/sound shape go.
  * Key remove only some spikes, player has to parkour through.
  * Collect many keys in a semi-open level tyo open a multi locked (horizontal or vertical) door.
* Sound shapes » and « sound platform: todo
