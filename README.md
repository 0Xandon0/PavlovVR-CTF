# PavlovVR-CTF
To add this gamemode to your map simply copy the content folder into your Pavlov Unreal Engine 4 project. The content folders should then merge. After that move the CTF-Gamemode folder inside of your UGC or SVR folder. Inisde of your definition you will need to check the custom gamemode box. Then inside of your map delete any other Gamelogics and drag in CTF-Gl. In the content browser double click CTF-GL to configure the gamemode to your preferences. Then you will need to add the appropiate flag spawns and possibly team bases if you wanted to use win volumes. You should then add the spawns provided into the map. Next you need to either disable Waiting rooms in CTF-GL or add one to your map. If you are using shack then disbale the maze for the Waiting room. If you are using shack then please check shack mode in the CTF-GL. This will turn down the graphics of the flag from the PC mode and make some other optimizations.

I have also added some launch pads and admin teleporters to the modkit. To use the launch pads you will need to put an empty actor as the end point and select from the launchpad in the world. Both ends need to be above the ground. You can also cange the amount of arc that the launcher has.

If you choose to use teamless mode where both teams try to capture the same flag then do not use team bases. Instead put red and blue flag spawns. If red team gets the teamless(magenta) flag to the red flag spawner then they will be awarded a point.

to update this you will need to do the same as above but then swap out the old gamemode folder and change the config.

BUGS:
Invulnerability needs to be 0.
Waiting room is broken.

If you have any questions or need help troubleshooting please DM me \_Xandon\_#2088 on discord.
