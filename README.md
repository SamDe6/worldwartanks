# worldwartanks

A small version inspired by the game Pocket Tanks

This game is based on java. This project is meant for academic purpose only. 
 
### GamePlay


There are two players. Each player has a tank and three types of weapons. 
The players need to fire weapons accurately at the other player in order to hit the player. 
If a weapon hits a player's tank, the score of firing player is increased based on weapon's damage strength and accuracy of shot.


All basic control is done by mouse. 

Left and Right arrow are for left and right movement of tanks


### Download


You can download the jar file of the game but you require java to run the game.

To download jar version download the folder PocketTanks-Jar.

### Running


Windows: Run PocketTanks file inside the folder to run the game.

Linux: Go to the PocketTanks directory and execute java -jar WorldWarT.jar


### Features
This is only the basic version of the game hence it contains only basic features.


1. Change names of players.
2. Three types of weapons.
3. Three types of explosions.
4. Limited movement of tanks.
5. Damage done by a weapon depending on the type of weapon and accuracy of shot.
6. Self Damage from explosion.
 

### Development
The folder src/main/java contains the source code of the game.

You can add your custom weapons and explosions. All you need to do is create your own customWeapon class and extend the original Weapon class and register it to WeaponType.java . Similarly for custom explosion your class must extend explosion class and register it to ExoplosionType.java. Remember that the explosion or weapon is only updated or rendered if it is in objectHandler's update or render list. All the images should be kept in src/main/resources/ folder.


### Resources
All images are custom. 

__Author__ : Soumalya Dey

