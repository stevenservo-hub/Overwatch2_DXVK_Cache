# Overwatch2_DXVK_Cache
A dxvk cache that is automatically pushed weekly to ensure the latest cache for Overwatch2.

An up to date DXVK cache is needed to play without massive stutters. Usually you just have to play with the stutters while the cache is building.In this case im supplying an up-to-date cache for you. 

The Binary file (Overwatch.dxvk-cache) is hard linked to to my local git repo. I have a cronjob that pushes the updates upstream to github weekly to ensure the freshest DXVK cache. Please submit a ticket if you have any issues. 

###INSTALLING:

Depending on what graphical application you are using to manage Wine prefixes I.E. (Bottles, Lutris ETC..) will depend where your cache is located. If you have already started playing the game it should be easy enough to find with `find ~/ -name 'Overwatch.dxvk-cache*'` if not you will likely find it where your cache is stored for example if you use bottles it will be located in `$HOME/.var/app/com.usebottles.bottles/data/bottles/bottles/games/cache/dxvk_state/`. Still the best way to be sure if your not comfortable is to start a game so the cache is populated you can then use `find` or similar to get the exact location. 
