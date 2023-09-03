# Phoenix Client
# *YET TO BE DEVELOPED*
is a mash up of different client mods typically used for technical Minecraft. It consolidates the most useful rules from those mods, and merges rules that can be combined. It also adds some rules of its own! Primarily, Phoenix Client is to serve as a quality of life utility for Minecraft players.

### Discord Server:
[![Phoenix Discord](https://discordapp.com/api/guilds/802017282728525895/widget.png?style=banner3)](https://discord.gg/invite/wg2w7nvJEV)

# Features
[[NEW] betterPingDisplay](#betterPingDisplay) 

## autoCleanContainer
Automatically drops everything in an opened container and then closes the container [^tis] 
* Category:
* Default value: `N/A`,
* Default toggle state: `false`
* Required mod(s): Item Scroller

## autoCleanContainerBlackList
Items that will NOT be thrown out of a container with `autoCleanContainer` [^tis]
* Category:
* Default value: empty
* Required mod(s): Item Scroller

## autoCleanContainerListType
The restriction list type for `autoCleanContainer` [^tis]
* Category:
* Default value: empty
* Available options: `None`, `Black List`, `White List`, `Both`
* Required mod(s): Item Scroller

## autoCleanContainerWhiteList
Items that **WILL** be thrown out of a container with `autoCleanContainer`
* Category:
* Default value: empty
* Required mod(s): Item Scroller

## autoFillContainer
Automatically fills an opened container with the most common item in your inventory, or from every inventory slot (excluding hotbor & offhand), then closes the container. [^tis]
* Category:
* Default value: `N/A`
* Default toggle state: false
* Required mod(s): Item Scroller

## autoFillContainerMode
Set `autoFillContainer` to fill a container with the most common item in your inventory or from every inventory slot (excluding hotbor & offhand) [^tis]
* Category:
* Available options: `Common`,`Inventory`
* Default toggle state: `Common`
* Required mod(s): Item Scroller

## autoSwitchElytra
Automatically switch to Elytra upon double clicking your spacebar and back to Chestplate upon landing
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## autoVillagerTradeFavorites
Automatically trade favorited Villager trades from Item Scroller upon opening Villager GUI
* Category:
* Default value: `N/A`
* Default toggle state: `false`
* Required mod(s): Item Scroller

## barrierParticleAlwaysVisible
Makes Barrier Blocks always visible even if not holding it  
Only affects Creative mode
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## betterPingDisplay
Changes ping bars in player tab to actual numbers
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## boxPreviewForEChest
Adds Ender Chest previews using Tweakeroo's `shulkerBoxPreview`
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## carpetAlwaysSetDefault
Automatically sets Carpet rules as default
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## copyPasteSigns
Adds copy-paste functionality to signs
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## disableBeaconBeamRendering
Disables beacon beam rendering
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## disableCameraSubmersionFog
Disables visual fog when inside block or fluid
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## disableDarknessEffect
Disables Darkness effect given by Sculk Shriekers
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## disableNarrator
Disables narrator keybind (CTRL + B)
* Category:
* Default value: `N/A`
* Default toggle state: `true`

## disableSlimeBlockBouncing
Disables bounciness effect of Slime Blocks and Beds
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## disableUnderSeaDarknesss
Disables darkening of horizon and sky when below sea level (Y62)
* Category:
* Default value: `N/A`
* Toggle state: `false`

## disableUselessToasts
Disables "new recipe" and turorial pop-ups
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## fasterMalilibMangement
Adds stars to favorite any rules of MaLilib mods and a quick access dropdown menu
* Category:
* Default toggle state: `false`

## friendlierEasyPlace
Allows `easyPlace` can open block inventories and no longer give the "failed to place block" prompt
* Category:
* Default value: `N/A`
* Default toggle state: `true`
* Required mod(s): Litematica

## ghostBlockRevealer
Reveals ghost blocks around you
* Category:
* Default value: `N/A`

## handRestockBlackList
Listed items WON'T be restocked to your hand
* Category:
* Default value: `N/A`
* Required mod(s): Tweakeroo

# highlightPersistentMob
Give mobs that won't despawn artificial glowing effect
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## infoViewBeacon
Displays beacon effects
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## infoViewBeaconRenderStrategy
When to display `infoViewBeacon`
* Category:
* Default value: `Hold`
* Available options: `Hold`, `Toggle`

## openScreenshotDirectory
Opens "screenshots" folder instead of file
* Category:
* Default toggle state: `false`

## periManager
Displays blocks and liquid sources listed in `periManagerWhitelist`
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## periManagerWhitelist
* Category:
* Available options: empty

## printFurnaceXP
Print a furnace's stored XP amount to chat
* Category:
* Default value: `N/A`

## renderBookTrade
Displays the first Enchanted Book trade that any Librarian Villager offers and its price  
Color of text indicates the quality of the book trade.  
GREEN: perfect trade  
BLUE: optimal trade  
YELLOW: mediocre trade  
RED: terrible trade

## renderRestockTime
Displays in real time a villagers next restock event.
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## renderVillagerCuringTime
Displays in real time the conversion time of Zombie Villagers being cured.
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## replayAccurateTimestamp
Makes the Replay Mod timeline timestamp more accurate
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## safeAfk
Kicks you when you've taken a certain amount of damage
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## safeAfkHealthThreshold
Health points you must have to be kicked by `safeAfk`
* Category:
* Default value: `4`
* Available options: `1` - `26`

## saveBotCommands
Allows you to save `/player` commands (or lists of commands) from Carpet mod to client to use later with `/clientplayer`
* Category:
* Default toggle state: `false`

## shulkerItemContentHint
Most common item in a Shulker Box will be displayed
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## shulkerItemContentHintScale
The scale with which `shulkerItemContentHint` will shown
* Category:
* Default value: `3`
* Available options: `1` - `10`

## switchToTotem
Health points you must have to auto switch a Totem of Undying
* Category:
* Default value: `2`
* Default toggle state: `false`
* Available options: `1` - `26`

## toggleTab
Toggles playerlist
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## villagerMaxTradeDisplay
Displays use and limit of Villager trades
* Category:
* Default value: `N/A`
* Default toggle state: `false`

## villagerRenderers
Enables `renderRestockTime`, `renderBookTrade`, and `renderVillagerCuringTime`
* Category:
* Default value: `N/A`
* Default toggle state: `false`
