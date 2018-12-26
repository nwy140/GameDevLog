# Features Ideas Pack 1

Created: Dec 25, 2018 10:08 PM
Type: BrainStorm

---

## DYOM style Mission System

Gta Garage Documentation

Information | Files

Features

**Concepts**
There are four main concepts, which will first be briefly discussed, so it you can understand the rest of the features better.

1. **Objectives:** The most important things in the missions you create with DYOM are the objectives. If you have achieved all the objectives of a mission, the mission is passed. For your missions, you can set a number of objectives, which the player of the mission must achieve in sequence. For each objective you can choose one of the four available kinds: A checkpoint that must be reached, a actor that must be killed, a car that must be entered or a pickup thiat must be picked up.
2. **Special Objectives:** this isn't something the player has to do, but this is used to change the settings of the mission or make something between the objectives. So, for example, there is a change in the weather, a change in wanted level, a change in time limit or a cutscene.
3. **Select/Hide/Spawn:** Besides the objectives you can also add other items: actors (either enemy, friend or neutral), cars, pickups and objects. Items don't have to be available during the whole mission. You can design them to appear after a certain objective has been achieved and hide them after a certain objective has been achieved.
In designmode one of the objectives is "selected" which is indicated by a yellow marker, instead of the normal white marker over an objective. By default, the last added objective is selected, but you can select another one from the objective menu.
When you add an objective, they will be inserted behind the currently selected objective. When you add items to the game, they will appear during the mission after the currently selected objective has been achieved. Afterwards, you can use the "SPAWN" and "HIDE" menu-options to determine when the item spawns and disappears. These options change them to the time when the currently selected objective is achieved.
4. **Save and Distribute:** When you are making a mission, it is wise to save it from time to time. You can save when you select the option "Save Mission" in the "Mission Menu". You can save up to 8 missions at a time. These missions are saved in "San Andreas User Files", with the name dyomx.dat. The x can be a number between 1 and 8, depends on which slot you used to save the mission. This is comparable to the savegames from the normal GTA San Andreas.
Once you are finished, you can distribute the mission by uploading the dyomx.dat file to the DYOM website ([http://dyom.gtagames.nl](http://dyom.gtagames.nl/)).
If you want to play other people's mission, you have to download the mission (also a dyomx.dat file!) and put it in "San Andreas User Files". Then start DYOM, and select Mission Menu > Load Mission.
If you just use the "save mission" function, and distribute that file (so dyom1.dat until dyom8.dat), everyone can change your mission. If you want to prevent that, you can select "publish mission" in the "Mission Menu". Then you will find a dyom0.dat in San Andreas User Files. When you distribute this file, other people aren't able to change the mission.

**Mission Menu**

- Play Mission- Save Mission- Load Mission- Publish Mission (read-only version of the mission)- New Mission (the only way to be able to put your own name as author into the mission)

**Settings**

- Mission Name- Intro Text- Time of Day- Weather- Minimum Wanted Level- Maximum Wanted Level- Riot Mode

**Player**

- Position- Model- Weapon- Health

**Objective**

- Add Objective (Actor, Car, Pickup and checkpoint have the same features as the separate ones)
- Actor
- Car
- Pickup
- Checkpoint
- Special Objectives:
    - Cutscene (create your own custom cutscenes!)
    - Teleport
    - Countdown
    - Teleport to Car
    - Time Out
    - Weather Change
    - Set Time
    - Ped/Car Behaviour
    - Set Wanted Level
    - Adjust Time Limit
    - Start Timed Section
- Select Objective- Edit Objective- Delete Objective

**Actors**

- Add
- Position
- Model
- Weapons
- Animation:
    - Normal Animations
    - Enter, Sit and Leave nearest car (with this option you have all kind of possibilities for a driving car. You can make a route, let the actor follow you (friendly), let the actor attack you and much more!)
    - Walk and Run
- Health
- Gang (choose for neutral (only attacks when the player attacks first), enemy (attacks player) or friend (helps player))
- Accuracy
- Headshot
- Spawn- Hide- Edit- Delete

**Cars**

- Position- Add
- Model
- Primary Colour
- Secondary Colour
- Health
- Must Survive (mission is failed when car is destroyed)
- Bullet/Explosion/Damage proof
- Locked
- Tires invulnerable
- Spawn- Hide- Edit- Delete

**Pickup**

- Position- Add
- Weapon
- Health
- Armor
- Bribe
- Other (money, book, suitcase, etc)
- Spawn Once
- Spawn multiple times
- Spawn- Hide- Edit- Delete

**Objects**

- Position (rotate, tilt, coords)- Add- Spawn- Hide- Edit- Delete

**Tools**

- Teleport to Marker- Teleport to Objective- Jetpack- Spawn Test Vehicle- Browse Interiors- Play From Selected

**Texts**
Besides all this, you can enter your custom texts with everything. For example, your own name, the mission name, texts in a cutscene and for objectives.

---