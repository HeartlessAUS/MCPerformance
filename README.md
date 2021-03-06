# Getting the best performance for 1.16.1
### Things to note:

1. Probably not compatable with alot of mods.
2. Probably still not compatable with Optifine/OptiFabric.
3. Will probably never be made for forge, because forge sucks now.
4. Don't have a potato of a machine? skip all of this and just download Optifine instead: [here](https://optifine.net/downloads) (check preview builds)

## lets start:

#### 1. You'll need to download fabric by yourself

  - Go [to this link](https://fabricmc.net) and download the recent release.
  - Run the Installer, and install as a new instance.
  - This will be the Minecraft Instance you will use for this pack to work.
  
#### 2. [Download this mods.rar](https://www.dropbox.com/s/2oz9k5sqqyx84y0/mods.rar?dl=0)
  
  - This mod folder will need to go into your Minecraft directory. (C:\Users\USERNAME\AppData\Roaming\\.minecraft)
  - To get here easier, Press Win + R and type "%appdata%" this should take you to your "Roaming" folder.
  - Simply extract the Rar to your Minecraft directory.
  - [See here for help](https://i.gyazo.com/b27434f7f7b1406db7df28ff68e71a04.mp4)

#### 3. Start Game and make sure it works. (Make sure its on the correct instance!)

#### Mods that were included in this pack:
  - FabricAPI (Required for most mods to function)
  - CleanView (Less performance help, more cleaning up Mojang's mistakes in making particles get in yo face)
  - Mod Menu (A cute little modmenu for fabric)
  - Phosphor (Cleans up Minecraft's crappy light coding)
  - Lithium (Optimises a number of systems in minecraft's code)
  - Sodium (The big cleaner, basically fixes all of Mojang's mistakes with... well everything)

## Bonus stuff
#### WARNING: These are more advanced and could have issues if done incorrectly!
#### If you dont know what you are doing, don't bother with these!
#### If you have a 32bit PC, don't do with this, if you don't know if you do or not, don't bother.

#### Java 14

  - Downloading Java 14 can really help with Minecraft's dumb code.
  - [Go to this link](https://adoptopenjdk.net/releases.html?variant=openjdk14&jvmVariant=hotspot), and download the latest OpenJDK 14 zip. [See here](https://gyazo.com/393a17c809aac84f91ce952e646ff0bc)
  - Extract the zip to your java folder. (Usually C:\Program Files\Java)
  - Now in the Minecraft launcher, change your instances java executable to your new Java version. [See here for help](https://i.gyazo.com/035ae2df332a6677c04f8c205707b8bf.mp4)
  - All done.
  
#### JVM Arguments

  - In the same instance, change your JVM Arguments to the following: -Xmx4G -XX:+UnlockExperimentalVMOptions -XX:+UseZGC
  - NOTE: This gives Minecraft 4GB of memory to use, If you don't have that much to spare for Minecraft alone, do not change this.
  - Changing "-Xmx4G" will change the amount of memory Minecraft can use, but putting it too high will cause more issues.
  - Safe ranges vary from person to person, in my personal opinion, 2GB up to 10GB are safe.
  
## Other Stuff

  - Personally, I recieve a massive perfomance boost in fullscreen, give it a try.
  - Turn render distance down to 10-12, that should be enough.
  - Try different settings ingame to see if anything helps for you.
