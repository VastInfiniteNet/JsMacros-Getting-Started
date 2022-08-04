# Welcome
Hello there! The goal of this document is to teach one how to setup JS Macros Mod. 

This setup is targeted towards users: 
- using MultiMC, but similar principles *should* apply to other Minecraft launchers.
- running Minecraft 1.18.2, but same principles *should* apply to other Minecraft versions.


*If you already have JS Macros installed, and looking for instructions on how to run a script you downloaded, go to the "Running a script" section.*

# Getting Started
1. Open MultiMC!
    - If you haven't already, sign in into your minecraft account.
    - Similarly, make a new instance if you are using an existing one.


1. Install Fabric mod loader.

    1. Select instance and click `Edit Instance` on the righthand side.
    1. Select `Install Fabric`; select the most recent version, and click `OK`.
        - you should now see `Intermediary Mappings` and `Fabric Loader` in the Version list. Make sure both are checked off.
        Should look similar to: ![Image of Version list](https://pomf2.lain.la/f/n6ynseve.png)


1. Install Fabric API.

    1. Go to the [Fabric API mod page](https://www.curseforge.com/minecraft/mc-mods/fabric-api/files) and download the most recent version for the game version you are playing on. For 1.18.2: https://www.curseforge.com/minecraft/mc-mods/fabric-api/files/3891301.
    1. Now select `Loader mods` and the lefthand side, below `Version`, and click `Add` on the righthand side.
    1. Navigate to where you downloaded the Fabric API zip to, and select and open it.
        - You should now see `Fabric API` in the mod list.
        If this your first mod installed for the instance, the `Loader mods` list should look like: ![Image of Loader mods list](https://pomf2.lain.la/f/szt6ou1.png)


1. Install JS Macros.

    1. Go to the [JS Macros mod page](https://www.curseforge.com/minecraft/mc-mods/jsmacros/files) and download the most recent version for the game version you are playing on. Make sure it is the fabric verison! file name should look like `jsmacros-1.XX.X-FABRIC-X.X.X.jar`.
    For 1.18.2: https://www.curseforge.com/minecraft/mc-mods/jsmacros/files/3904779.
    1. Now add the mod. Click `Add` on the righthand side.
    1. Navigate to where you downloaded the Js Macros zip to, and select and open it.
        - You should now see `Fabric API` in the mod list.
        If this your first mod installed for the instance, the `Loader mods` list should look like: ![Image of Loader mods list](https://pomf2.lain.la/f/5dmxfjvr.png)


# Finding Where to Put a Script

The folder to put your scripts is typically `Macros/`. The full path will depend on where your MultiMC/launcher is, but generally looks like:

`E:/path/to/MultiMC/instances/INSTANCE-NAME/.minecraft/config/jsMacros/Macros/`

Drag any scripts you may want to run into that folder. It is fine if you add folders.

In the image below I placed a script I want to run, `helloWorld.js` in the `Macros/` folder. Note the path.

![Image of Macros folder that stores scripts to run.](https://pomf2.lain.la/f/srxnudqr.png)

# Running a script
So you wanna run a script someone else gave you? 

First make sure trust the script you are running. If you are able to read JavaScript or whatever language it is written in, give it a read before running it! Always practice some form of OPSEC.

1. Start the game!


1. Open the JS Macros menu.
    1. Find JS Macros menu key in the key bindings. Default should be `K`. Press it.

1. Add the script to a key.
    1. Click the `+` next to `Run`.
    1. Select the file to run by clicking the `./`. Navigate to where the script is, click it, and click `Select`
    1. Set the key binding by clicking on empty box to left of filename and pressing the key you want script to be binded to.
    1. Enable the binding by clicking on red `Disabled` button.
    
    In this case I am binding a script, `hellowWorld.js` to the `y` button: 
    ![Image of JS Macros keys menu](https://pomf2.lain.la/f/hlhvm8bs.png)

1. Run the Scripts!

- Press the button you binded the script to! 

