# 3D Printer Emulator In Minecraft

[Downloads](https://github.com/MrJohnWeez/3D_Printer_Emulator_In_Minecraft/releases)

## About

This repository contains a Java 1.15 Minecraft world with 6, 3D-printer emulator datapacks plus a resource pack.

A datapack running

![Printing A Line](Repository_Resources/Gifs/3D_Printer_Head.gif?raw=true "Printing a basic line on slow")

Modeled nozzle and particles

![Printer Nozzle](Repository_Resources/Gifs/Nozzle_Close.gif?raw=true "Particles and more create a 3d printer nozzle")

## Print Examples 

Below are a few of the examples of what these datapacks can create

### T-Rex (Print time 12 mins)

![T-Rex Time Lapse](Repository_Resources/Gifs/T_rex_Timelapse.gif?raw=true "Time lapse of printing a flxable t-rex model. (print time 12 mins)")

### Geo-Planter (Print time 12 mins)

![Geo-Planter Time Lapse](Repository_Resources/Gifs/Geo_planter.gif?raw=true "Time lapse of printing a geometrical planter (print time 12 mins)")

### Minecraft Logo (Print time 9 mins)

![Minecraft Logo Time Lapse](Repository_Resources/Gifs/Minecraft_Logo.gif?raw=true "Time lapse of printing the Minecraft Logo (print time 9 mins)")

Download the world save file. It contains all needed assets (Void world, Datapacks, Resource pack)

## How To Load the Minecraft World

1. Download **3D_Printer_Emulator_World.zip**
2. Extract and place in Minecraft saves folder
   1. Right click on .zip file and hit Extract Here
   2. Windows+r
   3. Type in %appdata%
   4. Open the folder .minecraft
   5. Drag and drop the extracted **3D_Printer_Emulator** folder into the saves folder
3. Run Minecraft version 1.15 (latest version) and open world
4. Type */reload* into the Minecraft chat
5. Watch the 3D printer run at 0,0,0 (X Y Z)

## The Datapacks

The datapacks listed in **Example Datapacks** can be used in any world

**WARNING!** The world will be cleared at the world position 0,0,0 -> 255,255,255

### How to use the Datapacks
1. Once a datapack has been placed in a world's datapacks folder, type */reload* into the Minecraft chat
2. A menu will be brought up

    ![Datapack Menu](Repository_Resources/ScreenShots/DatapackMenu.png?raw=true "Chat after typing /reload")

   - **[Start]** Clears the print bed and starts up the 3D printer
   - **[Stop]** Stops the 3D printer (Do this before starting any other prints)
   - **[Pause]** Toggles the pause state of the printer
   - **[Options]** Quality settings of the printer (number of particles)

        ![Options Menu](Repository_Resources/ScreenShots/OptionSettingsMenu.png?raw=true "Chat after clicking on the [Options] menu option")

3. The UI when printing

    ![Printing UI](Repository_Resources/ScreenShots/PrintingUI.png?raw=true "What a player sees when an object is printing")

    - **minecraft_logo print progress**: How much left there is to print
    - **LineNumber**: The Gcode line number that the printer is printing

## Create Your Own Datapack/Object

If you want to create you own datapack that prints out objects download the
[Gcode_To_Minecraft_Datapack_Converter](https://github.com/MrJohnWeez/gcode_to_minecraft_datapack_converter/releases)

![Gcode to Datapack Converter](Repository_Resources/ScreenShots/Gcode_To_Datapack_Converter_Screenshot.png?raw=true "The simple tool to create a 3D printer datapack")
