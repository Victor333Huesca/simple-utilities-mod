# Simple Utilities Mod (Minecraft 1.16.3)

Available to download from [Curseforge](https://www.curseforge.com/minecraft/mc-mods/simple-utilities).

Built using [Fabric Example Mod Template](https://github.com/FabricMC/fabric-example-mod) and made with the [Fabric](https://fabricmc.net) modding toolchain for Minecraft.

A Minecraft Mod that enhances the Game's HUD with some simple utilities like the following:

- **HUD Features:**
    - Simplified coordinates that are available at all times on the screen (Example: `39, 64, 200` as `X, Y, Z`)
    - Cardinal directions and which Coordinates are increasing/decreasing (Example: `(East X+)` when looking East, where the `X` coordinate is increasing)
    - Current armour and hand items and their durabilities, available at all times on the screen
        - Different colors based on how low the durability is
    - Current Game time in AM/PM format
    - Current sprinting status
    - Current framerate
    - Current Biome the player is on

---

## Images

![In-game HUD Example](images/ingame_hud.png)

---

## Installation

- Install [Fabric Loader](https://fabricmc.net/use/) on your Minecraft client
    - Recommended to install with the [MultiMC](https://multimc.org/) Minecraft client, which allows you to install Fabric in one click in the Minecraft instance settings
- Download latest Mod `.jar` from [Github](https://github.com/johnvictorfs/simple-utilities-mod/releases/latest) or from [Curseforge](https://www.curseforge.com/minecraft/mc-mods/simple-utilities)
- Put the downloaded Mod `.jar` in the `.minecraft/mods` folder
    - Or if you're using MultiMC, open the Minecraft instance settings you're using, and look for the option to add a Mod, then select the `.jar` file you downloaded
- Done!

---

## Building from source

- Clone the project with `git clone https://github.com/johnvictorfs/simple-utilities-mod.git`
- Cd into the project's directory `cd simple-utilities-mod`
- Run `./gradlew build` to build the `.jar`
- Built Mod `.jar` files will be located at `build/libs`
    - Example: `build/libs/simple-utilities-mod-1.0.0.jar`
    - This will be the Mod `.jar` file you can put in your `.minecraft/mods` folder

---

## Planned features

- Allow the User to toggle the HUD utilities, both individually and as a whole, could be done either with Hotkeys or with a Settings interface, possibly both
- Add current status effects duration to HUD
- Add Sun/Moon icons to the current game time, so it's easier to notice if it's Day or Night

---

## FAQ

- **Does this Mod work on older versions?**
    - Yes but to a very limited range of versions. This mod was started with version 1.15 so all versions between this version and 1.16.3 are supported. Also 1.14 *might* work with some modifications but nothing can be guaranted. But older versions are **not** supported since this mod relies on Fabric which was started with Minecraft 1.14.

- **Will this Mod get me banned from *X multiplayer server*?**
    - Maybe, maybe not, the Mod is entirely Client-sided and does not require it to be installed on the Server, and mostly shows things already available to you at all times like coordinates and Cardinal directions, like an extended but simplified F3 Menu, but it has some exceptions, like very specific Game time, so some servers may not allow it, do look into the Server's rules carefully before using it, do **not** create issues here asking about that, since I won't know.

- **Will you add '*X feature not present in the [Planned Features](#planned-features) section*'**?
    - Maybe, and only if it fits with the other features of the mod, create [an issue](https://github.com/johnvictorfs/simple-utilities-mod/issues/new) about it, I only on this project on my spare time, but I'd be happy to add wanted features in my spare time.
