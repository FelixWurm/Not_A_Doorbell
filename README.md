# Not_A_Doorbell
This is a project aimed to build a custom "HotKey" board or mini Keyboard, using the raspberry pi pico (rp2040), an old recyceld controller (can by replaced with a standart alps encoder) and a qmc firmware. The used switches are cherry MX and compatiblt options.  It also uses RGB leds for some sweet lighing effects

The Name of the Project was selected because an early render of the device looked somewhat like a Doorbell, mainly because i only renderd the Encoder but not the buttons. 

# The Goal of the Project

I had purched a old "Video schnittpult" second hand (Televela T701), to use the housing and some of the parts for a different Project. However, the very nice encoder (also nown as jog/shutter wheel) was not realy needte. I howeve always whanted something to controll playing music with, so the idear was born to build my owen mini Keyboard.

#some tips:
in oder tu use the full potential of the endoder when usung linux set I recomend chnaging the amount the Volume chnages pear rotation to one ore two. To du this (if you are on ubuntu ):
- ``` gsettings get org.gnome.settings-daemon.plugins.media-keys volume-step ```
 - to get the currently set value
- ``` gsettings set org.gnome.settings-daemon.plugins.media-keys volume-step 1```
 - to set it to one
 
 
# PCB and Scematic

The pcb is designt in KiCad and manufacured by JLC PCB in china. THE CUURENT VERSION OF THIS PCB HAS SOME ISSUES! the issues are:
- Missing resistors for clampung voltage to 3.3 on the imput of the pico
- wrong hole placment of the lower mountung hole from the encoder
- general mounting hole misplacment

# Enclusure
- the optiginal idear for the hosing was to use wood, however in the current state that could by difficult to do with the mashines i have acsess to. 
- a STL housing that could by 3d Printet as well as a keyplate is in development
- there is a possibility for a CNC carved housung 

# ToDo 
- Fix the PCB
- Create the software
- Upload Pictures 
- Create the STL Files for the case
