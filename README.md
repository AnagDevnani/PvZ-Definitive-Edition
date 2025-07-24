# PvZ-Definitive-Edition
Aims to provide the best way to experience Plants vs. Zombies (2009).

# List of fixes
Includes fixes to bring the PC version of Plants vs. Zombies (more accurately, the [Steam version](store.steampowered.com/app/3590/)) to be more in line with the console and mobile releases by adding native widescreen support, multiple resolution support, improved higher quality sprites and controller support with other misc fixes as well.

## Original Dancing Zombie
Restores the original dancing zombie which was removed due to the zombie's appearance being similiar to Michael Jackson's Thriller appearance and due to the recency of MJ's death around when the game had released.

[This guide](https://steamcommunity.com/sharedfiles/filedetails/?id=1475427266) details the steps required to replace the sprite, however the size of the new sprite may not match the rest of zombies (will add a fixed version later)

## Low FPS during plant selection screen or when Dave is talking (on Linux)
1. Launch the game
2. Navigate to `~/.steam/steam/steamapps/compatdata/3590/pfx/drive_c/ProgramData/PopCap Games/PlantsVsZombies/` and locate `popcapgame1.exe`
3. Copy `popcapgame1.exe` to `~/.steam/steam/steamapps/common/Plants Vs Zombies/` and rename it to `PlantsVsZombies.exe` (remember to make a backup of the original `PlantsVsZombies.exe` file)
