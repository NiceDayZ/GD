### Compozitia Echipei

|Nume|Grupa|
|--|--|
|Craciun Mihai-Cosmin|B3|
|Ionita Mihail-Catalin|B2|

[Youtube video](https://www.youtube.com/watch?v=EbtOOZzI3aA)

[Arhiva Proiect](https://drive.google.com/drive/folders/18iVYfz0BP-ebrDoqoc8UgOdXBsKQBnHy?usp=sharing)
---

### Spreadsheet with information about available creatures and spells:
[Creatures & Spells](https://docs.google.com/spreadsheets/d/1vicG7074kdIW6Vck_81Fmi02pwr_QhWuW-3WBgzMdrA/edit?usp=sharing)
---


### Type of Game:

#### Battle Card Game

---

### Core Gameplay: 

#### Each player must find the best use of given action points each round in order to summon different creatures, buildings or use spells to win the game by getting it's opponent health points to 0.

---

### Similar products/concepts:

#### Heartstone ([https://playhearthstone.com/en-us](https://playhearthstone.com/en-us))

#### GWENT ([https://www.playgwent.com/en/](https://www.playgwent.com/en/))

---


**Checkpoints for week#2**

 - Unity3D project has been created and minimal UI/UX has been implemented(buttons, healthbar etc)
 - Field components where a creature can be placed have been implemented.
 - Creature components have been added.
 - Added AR functionality using Vuforia 
 - Started working on networking using Normcore framework, made possible to share logic across the network.

**Checkpoints for week#3**

 - Added turns mechanic(each player have to work for his turn in order to play).
 - Improved networking and fixed bugs with the turn mechanic.
 - Added interactions between creatures at the end of each turn.

**Checkpoints for week#4**

 - AR functionalities were completely removed to make place for a desktop alternative approach.
 - New assets were procured from different online platforms such:https://assetstore.unity.com/ to better fit the game's aesthetics.
 - Improvements have been done for the camera system , now that AR is not available anymore adjustment for the player FOV have been made , we opted for a collection of cameras which display different angles for the player.

**Checkpoints for week#5**
 - Assets for replacing the old card items prefabs have been made and can be found in the Utils folder.
 - We worked on a skybox for enhancing user immersion.
 - Currently a version for only two players connecting to one common session is available due to interface changes that are worked on at the moment.There is also a room system to come.
 - Animations were introduced either by using the in-package animations or using the Adobe Maxon utility to produce basic movement(idle , attack , run) for **anthropomorphic** type creatures.

**Checkpoints for week#6**
 - Assets for implementing cards were fabricated. These can be found in the Utils folder as well
 - More improvements to the interface have been made, for instance now you can clearly see the Attack and HP values for a summoned creature
 - Mechanics such as sacrifice or evolution for cards were introduced to further spice up the gameplay
 - Most of the creatures attributes have been normalized and can be found in the linked spreadsheet above
 
**Checkpoints for week#7**
 - Debugging existing problems such as text clipping through its boundaries, fixes were introduced 
 - Some bug fixing to the network synchronisation aspect of the game.

**Checkpoints for week#8**

 - More balancing for a set of cards to promote a fair game. The results can be seen in the attached spreadsheet
 - Started working on an interface and functionality for a lobby based matching
 - Prototyped a basic animation system using Unity native Animator

**Checkpoints for week#9**

 - Implemented the interface for lobbies and matches but it still have issues to be solved on the syncronization aspect
 - Started working on a sound system but it is yet to be implemented since it has some problems

**Checkpoints for week#10**

 - Fixed some issues regarding monsters spawning outside of the map sometimes
 - Improved stability fixed some really nasty crashing problems.
 - Improved spawn chances for some cards. Stronger cards are less likely to be drawn from the card.
 
**Checkpoints for week#11**

 - Worked intensively on synching up the animation for both player, due to constraints imposed by Norm Core this proved to be a challenge.
 - Fixed bugs of interface, there were instances when some buttons won't do anything.

**Checkpoints for week#12**
 - Reviewed (again) the cards to make sure that everything is balanced as it should be.
 - Fixed bugs of interface, there were instances when some buttons won't do anything.

**Checkpoints for week#13**
 - There were some instances when the animation of a character would go haywire, this was fixed 
 - Stability of the game was improved , mostly fixed some really nasty crashes.

**Final week#14**
 - Sound effects and music finally added , there was no sound at all until this point. 
 - In addition to music which was implemented there is also a system that makes the music change depending on the state of the player's health
 - Some UI triggers were implemented to make the menu much more user friendly.
 - Improved animations , now there is a close-up when two creatures attack each other.
 - Additional spells were implemented.
 - The game is able to end now, an end screen was added which redirects the player back to the screen.



