# 1.1.0 Beta 6 Hotfix 2 (1.0.118)

- When pressing return on an element in the shop it will now switch to the buy button for quicker navigation.
- When going back from the store the screen is cleared correctly now.

# 1.1.0 Beta 6 Hotfix 1 (1.0.117)

- Instead of inserting, adding to the terminal keywords again to prevent mods not fortified for index changes to work again.

# 1.1.0 Beta 6 (1.0.116)

- New item: Tactical helmet
- Added Store and the ability to buy items to the portable terminal.
- Removed all terminal commands and nearly all previously added Terminal Code.
- Reworked how item weights, prices, item activations, moon prices etc. are applied to use transpilers.
- Added more meaningful NetworkConfig mismatch error information, so it's easier to pinpoint errors.
- Added a custom loading and saving routine which will add additional information to save files to restore the state of a save even when items were added by mods or removed by removing mods.
- Fixed a bug which occured when deleting a previously selected preset.
- Fixed a bug which resulted in weird shadows with the helmet lamp while looking down
- Fixed a couple of small bugs reported to me over the last few days

# 1.1.0 Beta 5 Hotfix 5 (1.0.115)

- **Nerfed the helmet lamp due to complains :3.**
- Fixed a bug which prevent client settings from being applied
- Selected client settings preset is now saved between sessions
- Selected server settings are now correctly saved in the game savefile
- All XP progress has been reset due to a new savefile. You can edit your savefile now as it is in JSON format.
- Fixed a bug which prevented items making sounds in your inventory.

# 1.1.0 Beta 5 Hotfix 4 (1.0.114)

- Added default presets

# 1.1.0 Beta 5 Hotfix 3 (1.0.113)

- Fixed a bug with removed the head equipment slot when vision enhancer was disabled but helmet lamp or headset not
- Added compability mode for BetterEmotes/MoreEmotes
- Added new library methods for other modders to add animation overrides and sync them.
- Fixed a bug with the headset not working correctly
- Fixed a bug which resulted in the headset still using battery when dropping it directly from an equipment slot.
- Removed legacy file configuration. Only in-game and JSON files from now on :)
- Added new configuration values for the hotbar. (Border thickness, min and max spacing)
- Fixed a typo on portable terminal

# 1.1.0 Beta 5 Hotfix 2 (1.0.112)

- Fixed a bug with relayed message overflow
- Fixed a bug with inventory slots not showing up immediately after purchase.

# 1.1.0 Beta 5 Hotfix 1 (1.0.111)

- Fixed a bug which prevented AdvancedCompany from saving due to the new backup system.

# 1.1.0 Beta 5 (1.0.110)

- Added the new portable terminal. Press X to open it. You will only be able to level your perks on the new portable terminal from now on.
- Changed the behaviour of cosmetics by spawning them on Layer 23 (The layer Mirror Mod uses to show own cosmetics in mirror) and changed SpectateCamera accordingly (added 23 to culling mask), so mods relying on spectator camera for third person views will work with own cosmetics out of the box. All other mods have to adapt.
- Hopefully fixed a rounding bug with the item weights
- Hopefully fixed a rare desync bug with client ids in lobbys (resulting in wrong perks being shown)
- Fixed a bug which resulted in players wearing their equipment after dying.
- Fixed a bug which prevented the [playerNum] fix to be applied.
- Fixed a bug which prevented the updated deadline to be shown when extending the deadline.
- Limited respec. You can only respec player on ship and ship at company building.
- Fixed a bug which prevented the flashlight from shutting down correctly when the batteries were used up.
- Extended the used font asset for all available unicode chars from 0000 to 2600
- Adjusted the helmet lamp color
- Added keybinds with LethalInputUtils
- Added a safety feature to prevent AdvancedCompany savefile corruption. (Backup before save and if backup is also corrupted, deleting save files)

# 1.1.0 Beta 4 Hotfix 4 (1.0.110)

- Added length checks to the new store to prevent mods from exceeding 26 character item names and prices over 5 digits

# 1.1.0 Beta 4 Hotfix 3 (1.0.109)

- Fixed an issue with bulletproof vest file config
- Fixed an issue with free moon file config
- Fixed an error with the new time setting
- Fixed an error which resulted in the cosmetics file to be written to the root of the hard drive
- Fixed an error which prevented equipment receiving their unequipped event when switching items in slots
- Fixed an issue with console not being able to show more than 10 levels. Will show them now but break layout instead of not working at all.

# 1.1.0 Beta 4 Hotfix 2 (1.0.108) 

- Fixed a bug which caused Jeb calling you when directly dropping the Headset from an equipment slot

# 1.1.0 Beta 4 Hotfix 1 (1.0.107) 

- Fixed new presets having wrong moon prices
- Fixed incompability of the headset with LECore.
- Fixed some values of moons not saving correctly.

# 1.1.0 Beta 4 (1.0.106) 

- Added new item: Headset
- Fixed a bug with the fall damage perk not applying correctly
- Fixed a bug with the damage reduction perk reducing fall damage
- Fixed a bug which caused the helmet lamp to be applied multiple times and not being removed when dying
- Fixed a bug which prevented buying items on the terminal (especially when the full name was entered)
- Fixed a bug which resulted in wrong items being delivered when other mods added items.
- Fixed a couple of small bugs
- Added the possibility to add own moon configs by name. (Enabling configuration of modded moons)
- Added the possibility to add own item configs by name. (Enabling configuration of items from other mods)
- Added scrap multiplier values for moons.
- Reworked a lot of the lobby code to stabilize it. Heavily tested this locally and joining as spectator should work very good now. Hopefully.
- Moved the cosmetics config out of the config folder to prevent all players having the same cosmetics when loading a profile via mod manager.
- Added new configuration value to define the length of day.
- Hopefully fixed masked players not wearing cosmetics :)
- Travel discount should now also affect modded moons.
- Added brightness slider for night vision

# 1.1.0 Beta 3 (1.0.105) 

- Added new item: Helmet lamp
- Hopefully fixed all configuration errors. Lets cross fingers.
- Added cosmetics to masked enemies. Also applies the selected suit to it.
- Fortified the netcode even further and added granular logging to find bugs.
- Fixed a bug which prevented clients from disconnecting when the lobby closes.
- Fixed small bugs here and there.
- Made equipment compatible with mirror mod and 3rd person of TooManyEmotes
- Hopefully fixed the bug with the vest not correctly reducing damge for good
- Fixed the jump stamina perk mistakenly making jumps cost more stamina :D

# 1.1.0 Beta 2 Hotfix 2 (1.0.104) 

- Hopefully fixed a bug which caused the bulletproof vest to heal you.

# 1.1.0 Beta 2 Hotfix "Potatoe was too tired and forgot to add the correct DLL" (1.0.103) 

- Title says it all.

# 1.1.0 Beta 2 Hotfix 1 (1.0.102)

- Fixed a bug which showed cosmetics on own players when Mirror mod wasnt present

# 1.1.0 Beta 2 (1.0.101)

- Hardened the handshake process to not fail when a part of the handshake failes
- Added compability with third person camera of TooManyEmotes and Mirror mod.
- Fixed a bug with the hotbar not appearing when entering a game.
- Fixed some more little sources of exceptions to ensure smooth gaming.
- Added a hint when you gained XP.
- You can now deactivate certain equipment slots by deactivating all items going into a certain slot.
- Fixed a bug which resulted in items being placeable in equipment slots.

# 1.1.0 Beta 2 (1.0.100)

- Fixed a bug with items showing up twice in the new store
- Fixed a bug with some configs getting multiplied by 100.
- Changed the save location of client presets. (File configs will still be shared but you can create new client presets which wont get shared)
- Changed positioning of flavour text when logo is replaced.
- Removed compability with ReservedSlots
- Fixed incompability with InsanityRemastered
- Change positioning of equipment slots resulting in the possibility to level up to 10 inventory slots if set by the lobby.
- Maybe fixed a bug from showing the main menu after cancelling lobby setup with certain mods
- Fixed a bug which resulted in the wrong players being removed from the connected players list in certain circumstances resulting in weird behaviour.
- Now also deactivated LateCompany and ShipLobby as they dont add any functionality and are more likely to break stuff.

# 1.1.0 Beta 1 (1.0.99)

- Introduced the first API calls:
  - AdvancedCompany.Lib.Mod.RegisterRequiredMod()
  - AdvancedCompany.Lib.Flavour.SetLogo()
  - AdvancedCompany.Lib.Sync.AddSyncHandler<T>()
  - AdvancedCompany.Lib.Sync.SyncHandler.ItemSynchronization.AddItemType<T>()
- Reworked the whole lobby netcode
  - You will only be able to see AdvancedCompany lobbies with the same all-clients mods as you (if they use RegisterRequiredMod).
  - Vanilla players joining will see a meaningful error message.
  - Mismatched all-clients mod registered with the new API will be communicated with the player.
  - Handshake is done during MainMenu resulting in less sync problems for player data.
  - Lobby size will now be communicated before scene initialization, resulting in only instantiating the max amount of players which can join.
  - Server configuration is shared before scene switching resulting in less config sync problems.
  - AudioMixer will only get replaced for player voices and its output is linked to the games audio mixer, resulting in less audio problems.
  - AudioMixer will expand depending on the max players in the lobby. (4, 8, 12, 16, 20, 24, 28, 32)
  - Added new experimental "Join after start" option.
  - Added custom synchronization code to prevent the errors of past mods.
- Added a new store to make the terminal more robust
- Added a fallback if item was not found making it possible to buy lightning rod with input like "lignting"
- Change the terminal text field to behave more nicely with its scrollarea.
- Fixed an error which only showed the simple death messages with Coroner
- Fixed an error with damage reduction perk
- Added lobby settings and presets 
- Added client settings and presets
- Added MoreCompany cosmetics compability
- Cosmetics can be changed while in-game
- Added custom death screen compatible for up to 32 players
- If MoreCompany is present (due to a dependency of a cosmetics mod or by choice) it will get deactivated at runtime.
- If MoreCompany is present the included cosmetics of MoreCompany will become available.
- Fixed an error regarding the save suits option
- When dying in a lobby without Save progress, the inventory slots will correctly reset now
- Fixed a bug which resulted in the activated flashlight not being shown active any longer when dropping an inactive one.
- Fixed a bug which resulted in the level screen not showing
- Fixed [playerNum] appearing in chat
- Fixed radar targets having the wrong name
- Fixed disconnected players appearing on endscreen.
- Selected server presets are added to the savegame, so the preset will stay selected.

# 1.0.10

- Removed debug hotkeys H and J for rescaling the Hotbar
- Fixed the screen observer. The hotbar should now automatically adjust to the screen correctly when the window is resized.

# 1.0.9

- Fixed the missile launcher not working as intended. Dont read further if you want to find it out yourself:
  - If being chased by dogs or giants, they will stop chasing and going to the fireworks
  - If being eaten by a giant the giant will drop you
  - Giants will ignore players and wont pick up players for 5s
  - Dogs will ignore players for around 7s
  - Still makes beautiful fireworks

# 1.0.8

- Fixed the hotbar bug
- Fixed the flipped steam avatars
- Added a new more fitting design for energy indicators

# 1.0.7

- Fixed a bug which resulted in some results on the endscreen not being removed correctly.
- Reworked the inventory slots to make it more consistent and work even better with ReservedSlots
- Added a check if a keybind for flashlight is set and if so removing the flashlight keybind from ReservedSlots
- Player avatars are now loaded during the run asynchronously which should prevent avatars missing in end screen and any hangs.
- Added missing foggy weather multipliers
- Added the ability to save your progress in your profile folder. Allowing you to create multiple profiles with different progress.
- Added the ability to change the hotbar alpha and scale
- Added more settings for when save progress is off to make the progression faster:
  - Starting XP
  - XP multiplier

# 1.0.6

- Fixed a bug which prevented users from inputting into the terminal
- Hopefully fixed a bug with the new endscreen freezing the game
- Added compability with ReservedSlots
- Added the ability to deactivate clothing slots by deactivating all items which can be worn in the config

# 1.0.5

- Fixed a bug with the map which might have led to unexpected behaviour.
- Added cause of death to the end screen.
- Added Coroner for cause of death integration. (If you have Coroner installed, the cause of death is read from that mod instead)

# 1.0.4

- Added a custom end screen to enable lobbies of up to 32 players to be displayed.
- Fixed a bug which prevented from spectating all players when playing with up to 32 players.
- Fixed a bug which prevented the correct names of players to be displayed in lobbys bigger than 4.
- Fixed a configuration bug with the Server/General.cfg. It should now show up correctly. Happy bundling mod packs out there! :)
- Fixed a bug with the synchronization of flashlights. They should now no longer desync.
- Fixed an error in one of the transpilers which could have led to unexpected behaviour when playing with more than 4 players. I am pretty sure by now that 32 players should be stable.

# 1.0.3

- Added configuration to moon prices and weather scrap modifiers, making them deactivateable. Deactivating moon prices will result in the travel discount perk to be disabled too.
- Added configuration to let the server keep track of all player XP and reset it after not meeting the quota. Players wont lose their permanent XP but cant use them in lobbys with this enabled. (SaveProgress in Server/General.cfg)
- Hopefully fixed 32 player lobbys not working for steam lobbies. I hope for feedback on this one :)
- Fixed a configuration error which resulted in default values not being set correctly. All affected configuration values will get overwritten after launching the game for the first time after this update. Affected perks were Critical strike chance and Loot Saver.

# 1.0.2

- Fixed a small bug which was introduced by 1.0.1 preventing the night vision and the jump height perk from working correctly.

# 1.0.1

- Slightly changed the missile launcher to aim more for the middle of the screen. Please give me feedback if it feels better now.
- Improved lobby handling and therefore increasing performance for lobbies smaller than 32 players greatly.
- Fixed wrong configuration paths so you can adjust the configs in ThunderStore correctly now.
- Added the ability to deactivate the bigger lobby patches. Please note: All connectings clients need to synchronize this setting before connecting to the server. I am pretty sure other bigger lobby mods will likely result in incompabilities when playing with more than 4 players but you can try it.