# PearlHome Localisation

## Localisation files for [PearlHome](https://github.com/Pxl-8/PearlHome)

Please feel free to contribute to localisation! Get started below

# Contributing 

Get started by cloning this repo, learn how [here.](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)  
If you arent comfortable using the command line I highly recommend using [GitKraken](https://www.gitkraken.com/)

Once you have the files just copy and edit the [template.json](https://github.com/Pxl-8/PearlHome-Localisation/blob/master/assets/pearlhome/lang/template.json) to whatever language you want and rename it according to the languages in Minecraft which [can be found here](https://minecraft.gamepedia.com/Language).   
Find the corresponding locale code and save your file as <locale_code>.json

Learn how to create a pull request [here](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

# [template.json](https://github.com/Pxl-8/PearlHome-Localisation/blob/master/assets/pearlhome/lang/template.json) Format Guide

The template is fully ready to edit, just add your translated text in the blank spaces: `""`  
Find an example of usage [here](https://github.com/Pxl-8/PearlHome-Localisation/blob/master/assets/pearlhome/lang/en_us.json)

`text.pearlhome.teleport.success.home`  
> This is the message sent when teleporting to a bed  

`text.pearlhome.teleport.success.spawn`  
> This is the message sent when teleporting to spawn  
***
`text.pearlhome.teleport.warn.grounded`  
> This is the message sent when failing to teleport because the player is flying 

`text.pearlhome.teleport.warn.in_water`  
> This is the message sent when failing to teleport because the player is in water 

`text.pearlhome.teleport.warn.in_lava`  
> This is the message sent when failing to teleport because the player is in lava  

`text.pearlhome.teleport.warn.burning`  
> This is the message sent when failing to teleport because the player is on fire  

`text.pearlhome.teleport.warn.sneaking`  
> This is the message sent when failing to teleport because the player is required to be sneaking/crouching  
***
`text.pearlhome.misc.setspawn_info` 
> This is the message sent when the player sets their home by clicking a bed during the day  
> This message includes additional coordinate info in x, y, z format.  
> Use `%1$s` for x, `%2$s` for y, `%3$s` for z.  
> These values will be automatically replaced in game with the actual coordinates  

`text.pearlhome.misc.setspawn`  
> This is the message sent when the player sets their home by right clicking a bed during the day.  
> This version does not include the additional coordinate info  
***
`gui.pearlhome.portable_enderchest`  
> This is the display name of the portable ender chest inventory when you open it with an eye of ender/nether star  