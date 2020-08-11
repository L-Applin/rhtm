# rhtm
* Platformer / Puzzler / Musical game


Music platformer  
Musical 2D puzzle platformer  
Title ideas : « Rhythm »,  

Music interaction with level design will help player solve a mix of platforming and puzzling  

# 1) General ideas

## 1. Interaction between music, level design and player actions:  
### A. Player actions will influence the music of the game.  
### B. These changes in music will be reflected in the level itself. Ex. :    
* Door opens, spike removed, platform appears, etc;  
* Colors,  
* Enemies;   
* General change (gravity (?), level rotation (?), teleportation (?), etc).

### C.	Visual level elements (moving platform or obstacle, doors, etc) can be heard in the music.


## 2.	Listening to the music is required to solve puzzles/reach the end of the level :
### A.	Matching rhythm.
### B.	Matching pitch (melody, harmony, arpegio).
### C.	Musical hints located through levels ?


## 3.	Musical style :
### A.	Synthwave / 80’s synthesizer 
### B.	Vangelis / Daft punk / Depeche mode / Stranger things
### C.	SFX as musical elements.
### D.	Contrasting :
i.	Empty, slow at the begining of levels.
ii.	High tempo / arpegiated at the end, depending of the level.
E.	Each level’s music is similar, but has it’s own characteristics.
4.	Fast paced :
  A.	High player speed.
  B.	Fast and tight control.
  C.	Lots of moving elements.			
  D.	In the styel of « Super meat boy ».
  E.	Flight ? Boost ? Glide ?

5.	Physics oriented :
  A.	Pushing objects around.
  B.	Falling objects as obstacles.
  C.	Gravity to help or hinder the player.

6.	Simple graphics :
  A.	Basic shapes :
    i.	Square, triangle, simple polygon
  B.	Filled colors.
  C.	Grayscale-ish.
    i.	Game elements playing sound / music have brighter color.

7.	Playable on the internet :
  A.	Javascript.
  B.	Libraries :
    i.	Tone.js for sound synthesis (MIDI capabilities),
    ii.	matter.js for physics engine,
    iii.	p5.js for rendering and game loop.


2)	Game elements


1.	Player :


2.	Obstacles :

  A.	Lethal : must be avoided or else the player will be killed and forced to restart :
    i.	Spikes,
    ii.	Spike pits,
    iii.	Crushers (piston).
    iv.	Saws.

  B.	Non-lethal : prevent the player from advancing in the level without killing him:
    i.	Will be solve through collecting « keys » or resolving « sound shape » (see next point 2.3. Puzzle solving elements).
    ii.	Exemples :
      a.	Locked doors,
      b.	Too long gaps, etc.

  C.	 Bodies that the player must naviguate through :
    i.	Static platform,
    ii.	Moving platform :
      a.	Straight lines,
      b.	Oblique lines,
      c.	Pendulum,
      d.	Going up / left / right / down.
    iii.	Elevators,
    iv.	Slopes,
    v.	Irregular structures

3.	Puzzle solving elements :

  A.	« Keys »  :
    i.	Sprites in the level that the character will have to collect.
    ii.	Removed from the world and goes into player inventory upon contact.
    iii.	They usually have a positive effect on the level as they are required to solve the level/puzzle :
      a.	Unlock doors,
      b.	Remove spikes,
      c.	Add platform,
      d.	Etc.
    iv.	Permenent :
      a.	i.e. the door will stay unlocked if player has the « key » in it’s inventory.

  B.	« Sound shape » & « Sound platform » :
    i.	« Sound shape » are sprites (balls, boxes, etc) moved around the level by the player :
      a.	Pushed around
      b.	Jumped onto to move
      c.	Pushed by piston or conveyor belts or other elements ?
    ii.	They have an effect (like a « key ».) on the level only when placed on a specific « Sound platform » :
      a.	Temporary : Only works when the « sound shape » is in place, sitting over a « sound platform ».
    iii.	 Different effecst can happend based on which « sound platform» a « sound shape » is placed upon :
      a.	levels may have many « sound platform» and « sound shape ».
      b.	Numbers may or may not match
      c.	« Sound shape » must be matched to a specific « sound platform » to advance in the level.
        i.	Wrong match can either have no effect or make the level worse (see section 3.Puzzle).
      d.	Music elements will be added based on those combinations : 
        i.	If the combination is wrong, it will sound bad.
        ii.	If the combinaison is good, a coherent soundtrack will be created layer by layer.
        iii.	These serves as hints to solve the puzzle.
      e.	« Sound shape » and « sound platform » also change color together depending on those combinations.
        i.	Colors can also be used as hints.
    iv.	Only a specific combaination let the player advance, hint being given by the music and color.
    v.	« Sound shapes » can be destroyed by lethal obstacles (see section 2.2.A Lethal obstacles)

4.	World :

3)	Puzzles
  1.	Puzzle brainstorm
    A.	Keys
      i.	Key open doors.
      ii.	Key open door, access to sound shape  and/or sound platform.
      iii.	Key removes spike, let player/sound shape go.
      iv.	Key remove only some spikes, player has to parkour through.
      v.	Collect many keys in a semi-open level tyo open a multi locked (horizontal or vertical) door.
  B.	« Sound shapes » and « sound platform »

4)	Code structure

