# Special Mentions

NOT WINDOWS FREINDLY (to fix at some point)

Based off Open Source Lan:

https://github.com/OpenSourceLAN/gameservers-docker

Credit to SirSquidness & Piorax for there massive support

# Current Setup

Set up to Work With Minecraft Version 1.14.4 this can be changed via editing files. 

I have disabled the use and creation of  egg's, golem's, minecart's and weither's due to players spawning mobs to lag out servers
This can be change see Customisation.

Currently show Pax Logo Bottom-left and RFlan logo on the Bottom-right

# Setup / Dynmap

Dynmap is on <IP>:8123
  

# Troubleshooting
  
To run a minecraft server command run : /minecraft:command,


# Customisation

To edit a live container use, docker exec -it bukkit_X bash (where X is you server no.)

To change Logo background:
 1.  Go to bukkit-hg\plugins\dynmap\web\css\leaflet.css
 2.  Edit line 327 change color to desired color 
 3.  Edit like 328 change border to desied setting

To edit what items are banned:
1.  Go to bukkit-hg\plugins\Essentials
2.  Edit config.yml

# List of things to fix

- Make it so plot world is generated on the creation of the server
- Make it so that plot world can be configured to hosts liking
- Find a better way of managing Lag Machines
