# Special Mentions

NOT WINDOWS FREINDLY (to fix at some point)

Based off Open Source Lan:

https://github.com/OpenSourceLAN/gameservers-docker

Credit to SirSquidness & Piorax for there massive support

Credit To LAN-slide, RFLAN and PAX AUS for allowing me to run this at your events,
This Ships with their logo's on the DynMap webpage by default.

LAN-slide: https://www.lanslide.com.au/
RFLAN: https://www.rflan.org/
Pax AUS: https://aus.paxsite.com/

# Current Setup

Set up to work with Minecraft Version 1.17 this can be changed via editing the Dockerfile. 

I have disabled the use and creation of  egg's, golem's, minecart's and weither's due to players spawning mobs to lag out servers
This can be change see Customisation.

Currently show PAX AUS Logo Bottom-left, LAN-slide and RFlan logo on the Bottom-right

# Setup / Dynmap

Dynmap is on <IP>:8123
  

# Troubleshooting
  
To run a minecraft server command run : /minecraft:command,

# Customisation

To edit a live container use, docker exec -it bukkit_hg-X bash (where X is you server no.)
  
To change Logo background:
 1.  Go to bukkit-hg\plugins\dynmap\web\css\leaflet.css
 2.  Edit line 327 change color to desired color 
 3.  Edit like 328 change border to desied setting

To edit what items are banned:
1.  Go to bukkit-hg\plugins\Essentials
2.  Edit config.yml

# List of things to fix

- Make it so that HungerGames world can be configured to hosts liking
