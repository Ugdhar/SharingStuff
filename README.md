# SharingStuff
For now, just sharing beginnings of a simple game written in Java and using libGDX.  
  
So far implemented tile map, character sprite, ASWD movement, hold left shift to run faster. simple f3 debug info.  
Collision should work for any tiles on the BaseBlocking layer
  
# Maps  
NOT infinite  
Left Up render order  
Can be whatever size height/width  
Layers: BaseForeground, BaseBlocking, BaseWalkable  
spawnX and spawnY (Float) properties can be added to the map to specify a spawn point, or it defaults to (1,1), the bottom left
  
If you put a testmap.tmx file in the same folder as the jar file, it will load that map.  
*** You must edit your tmx file with notepad or something, and change the image path to be ../tilesets/basictiles.png (or things.png) or it will crash.




Powered by https://libgdx.com/  
  
Also uses some graphics from opengameart.org:  
https://opengameart.org/content/tiny-16-basic by Lanea Zimmerman  
https://opengameart.org/content/tiny-16-more-character-animations by Lanea Zimmerman, Clint Bellanger, Charles Gabriel, basxto  
