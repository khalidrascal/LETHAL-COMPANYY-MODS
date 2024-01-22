# AdvancedCompany

![Logo](https://www.potatoepet.de/lethal_company/logo.jpg)

The most stable and solid lobby expansion mod including many quality of life improvements and new items. Fully configurable in-game with presets.

It's about time the company supplies you with the latest tech created from all the scrap you've collected.

Trailer: https://www.youtube.com/watch?v=DHA0Y8P89Tg

## New in 1.1

### In-game configuration

#### Client config

Clientside configuration including the new cosmetics feature. You can install all cosmetics mods compatible with MoreCompany as they will get automatically converted. You can open this configuration while in-game and change the cosmetics on-the-fly.

![Config](https://www.potatoepet.de/lethal_company/config1.gif)

#### Server config

Serverside configuration will get synched will all connected clients. Enables you to customize your experience. If you deactivate a perk the base value of that perk will still get applied, making it possible to use the system as a simple tweaks mod.

![Config](https://www.potatoepet.de/lethal_company/config2.gif)

### Reworked netcode

The rewrorked netcode enables AdvancedCompany to better sync games for people joining late (even on moons). Feel free to report reamining desyncs. Also new interfaces and classes are open to other mods enabling them to add their own data syncs in the handshake of a connecting client.

## Key features
* Expanded lobby size of **32** players.
  - Enables late joining (Even on the moons surface. Puts players into spectator mode)
  - Better sync for late joiners (Syncing animation states of objects, doors, lights of the ship etc.)
  - Synchronization framework for other mods to work with. (Synchronizing data at handshake)
  - According to testers offers the most stable and least lagging experience even in big lobbies.
  - Adding custom UI to make 32 players fit.
* Adds cosmetics from MoreCompany. If you have MoreCompany installed it will get automatically deactivated but the standard cosmetics will get selectable.
  - Cosmetics can be changed while in-game.
* A **clothing system** consisting of helmet, body and boots slots which actually display on the player models.
  - Clothing slots can be removed by deactivating all items which can go in them in the lobby config.
* Adding **new items** to the store:
  - Missile launcher
  - Lightning rod
  - Nightvision goggles
  - Flippers
  - Bulletproof vest
  - Rocket boots
* A comprehensive **perk system** including ship perks (saved on servers savegame) and player perks (saved locally)
* An intelligent **flashlight key** and rework of how flashlights work:

  You can only have one flashlight on at any given time. If you pick up an active flashlight while having one active, the picked up one will automatically be turned off for example.
* **Hotkeys** for inventory slots.
* **Battery indicators** beneath your items in your inventory.
* The ability to **extend your deadline** by one day per quota. (For the price of the current quota)
* **Balancing changes** regarding weather effects. You will get more loot in more dangerous conditions.
* All functionality can be **fully customized**.
  - Expansive in-game config options with presets.
* **More scrap!**

## Content Creation
You are free to create content with this mod. I would be glad if you add a link to this mod or tell your viewers where to get this mod :)

## Compability
As this mod changes a lot many mods might not be compatible. When players give me feedback about the compability of other mods I will add them here.

Fully compatible (Adde fixes):
- Coroner
- Mirror

Currently confirmed working are:
- Skinwalker
- Mimics
- ShipLoot
- SpectateEnemies
- TooManyEmotes
- Helmet Cameras
- AlwaysHearActiveWalkies
- YippeeMod (most importantly)
- MoreSuits
- LethalThings

  Utility belt wont work correctly. So deactivate it.
- LethalProgression

  Deactivating all inventory based upgrades.
- LateGame Upgrades
- BetterTerminal
- cirnofumoscrap
- Dissonance Lag Fix
- Door Fix
- Health metrics
- Terminal Clock
- LCBetterSaves
- Better ItemScan

Not compatible:
- ReservedSlots
  Due to a conflicting philosophy of adding more slots to the user this is basically due to conflicting ideas. I might add the possibility to remove all inventory handling from AdvancedCompany later, making ReservedSlots compatible again.

## Clothing system
The clothing system consists of three new slots in your inventory.

![Clothing slots](https://potatoepet.de/lethal_company/clothing.png)

All equipped items will be shown on the player. You can press and hold Alt to access the equipment inventory.

Equipment slots can be hidden by deactivating all items which go into a certain slot.

![Equipped clothing](https://potatoepet.de/lethal_company/clothing_equipped.gif)

## Missile launcher
The missile launcher will launch firework. The perfect and most stylish way to celebrate a new quota... or to distract enemies from a mile away. One missile launcher comes with 3 preloaded missiles. Empty its even more worthless than scrap.

![Fireworks](https://potatoepet.de/lethal_company/fireworks.gif)

## Lightning rod
It's stormy outside and some of your team mates dont want to go out of the landing ship? Take the initiative and place a lightning rod outside. After being deployed you can't pick it up again but at least it is working. No excuses to not go to stormy planets!

![Lightning rod](https://potatoepet.de/lethal_company/lightning_rod.gif)

## Nightvision goggles
Afraid of the dark? The company has the perfect solution for you. But beware. The battery life is limited. If mapped to the same button as the flashlight the night vision will be prioritized. When empty you can use the flashlight button for flashlights again.

![Nightvision goggles](https://potatoepet.de/lethal_company/nightvision.gif)

## Flippers
With flippers you can finally swim like a fish. Be a good asset and go to the flooded planets! You will swim in the direction you are looking at. Press the jump key to ascend or the crouch key to descend.

![Flippers](https://potatoepet.de/lethal_company/flippers.gif)

## Bulletproof vest
Tired of dying to turrets? Protect yourself with this bulletproof vest. It **ONLY** protected from projectiles. Depending on the origin of the projectile the vest will take different amounts of damage. You can fully configure the vest to your liking. With standard configuration a vest has 90HP. Turrets will reduce the HP by 5, a shotgun shot by 30. If reaching 0HP the vest will get destroyed. At 100% HP it will reduce 100% of the incoming damage. At 0% only 50%. Damage is shown on the item itself in 3 stages.

![Bulletproof vest](https://potatoepet.de/lethal_company/bulletproof_vest.gif)

## Rocket boots
You need a little extra height? Then the rocket boots are perfect for you. They allow you to perform a double jump.

![Rocket boots](https://potatoepet.de/lethal_company/rocketboots.gif)

## Perks

The perks system gives you something to progress in beyond a single session. You can open the perks system on your terminal with the "**perks**" command.

![Perks overview](https://potatoepet.de/lethal_company/perks.jpg)

### Player perks

Player perks are saved locally on every clients PC. So earned XP will stay as long as you dont reset them.

![Player perks](https://potatoepet.de/lethal_company/playerperks.jpg)

- **Sprint speed**

  Increases the speed of sprint.
- **Jump height**

  Increases the height of your jumps. (Also affects the rocket boots double jump)
- **Jump endurance**

  Reduces the stamina usage for jumping.
- **Sprint endurance**

  Reduces the stamina usage for sprinting.
- **Reinforced legs**

  Increases the heights for the damage and death zone of falls.
- **Protective skin**

  Increases your protection against damage from enemies. (Wont protect you from instant kills like mines or dogs)
- **Weight reducer**

  Reduces the strain weight has on your stamina.
- **Carry bags**

  Increases the inventory size.
- **Strong arms**

  Increases the chance for a critical attack (one-hit) on enemies.
- **Climbing speed**

  Increases the speed you can climb on ladders.

### Ship perks

Ship perks and XP are saved in the hosts save file for the session. So if the host removes the savefile, the ship XP and perks are lost.

![Ship perks](https://potatoepet.de/lethal_company/shipperks.jpg)

- **Scanner distance**

  Increases the distance from which items can be scanned.
- **Batterypack**

  Increases the size of batteries for all items.
- **Deadline discount**

  Reduces the price to extend your deadline by a day.
- **Landing speed**

  Reduces the time needed for landing and taking off.
- **Express delivery**

  Reduces the time needed for items to arrive with the dropship.
- **Loot saver**

  Increases the chance for loot items to stay on your ship when all players die.
- **Travel discount**

  Reduces the price to travel to moons.

### Respec

If you join a lobby with a configuration in which your player perks would result in a negative XP or you having levelled a skill which is deactivated or has fewer levels in the current lobby, you will get auto respecced. If you want to manually respec your character or reset the progress you can do so in the respec menu. If you are hosting the lobby you can also respec or reset the ship.

![Respec](https://potatoepet.de/lethal_company/respec.jpg)

## Expanded lobby

Currently all lobbies can hold up to 32 players. This feature is somewhat experimental and only added due to other solutions not being testable in LAN mode for me and as they are most likely incompatible with this mod. But as many people like to play with more than 4 players I decided to implement my own solution for bigger lobbies.

In later updates you will be able to configure the max size of your lobby per session. I also want to add a custom end screen.

## Intelligent flashlight key

You can bind a key for toggle flashlight (standard: 'F'). The flashlight toggle mechanics is rewritten completely.

When you press F what happens is determined by multiple factors which are chosen to ensure it always does what you want it to do:
- If you have bound night vision to the same key, prioritize night vision. If night vision is empty go to next step:
- Check if any flashligh is currently activated. If so: Deactivate it. Otherwise:
- Select flashlight with highest tier and battery charge in inventory. Pro flashlight is prioritized over normal flashlights. Activate this flashlight.

Activation of a flashlight, either by pressing the flashlight key or by pressing the activate key when holding it will result in the following behaviour:
- Search for all other flashlights in the inventory and deactivate them.

If you pick up a flashlight which is turned on it will get deactivated when you already have an activated flashlight in your inventory.

## Hotkeys

You can bind hotkeys for the inventory slots. (Standard Alpha 1 - 0)

## Battery indicators

Underneath your items you can see a battery indicator:

![Battery indicators](https://potatoepet.de/lethal_company/battery_indicators.jpg)

## Extend your deadline

If you feel you need a little bit more time you are able to extend the deadline **by a single day once per quota** (You can deactivate this functionality in the config). To do so, go to your terminal and enter the command "**extend**". The standard price for this is the current quota. With the "Deadline discount" perk you can reduce that cost.

![Extend deadline](https://potatoepet.de/lethal_company/extend_deadline.jpg)

## Balancing changes

Depending on the weather on a moon there is a scrap amount and value modifier applied. The standard values are:

- No weather:

  100% loot amount, 100% loot value
- Rainy weather:
  
  110% loot amount, 110% loot value
- Flooded weather:
  
  130% loot amount, 120% loot value
- Stormy weather:
  
  150% loot amount, 150% loot value
- Eclipsed weather:
  
  180% loot amount, 150% loot value

Another small balancing change is that you will keep the bought suits. Which makes this mod work so beautiful with mods like MoreSuits. You can deactivate this behaviour in the config.

## Configurability

The config is split into multiple files in two directories. One for server-side configuration (Which will get applied to all connected clients as well) and client-side configuration (which can differ from client to client).

### Server\General.cfg

#### General
- **Enable extend quota** (default value: true)

  Enables the ability to extend the deadline on the terminal by one day one time per quota.
- **Enable cosmetics** (default value: true)

  When deactivated players wont show their cosmetics.
- **Keep open** (default value: true)

  When activated will keep the Steam lobby open and allow players to join when in orbit.
- **Keep open on moon** (default value: false)

  When activated will keep the Steam lobby even open on moons and allow players to join as spectators.
- **Save suits after death** (default value: true)

  Determinse if bought suits should be saved after not meeting the quota. 
- **Save progress** (default value: true)

  Determinse if progress should be saved by clients and server. When deactivated every player starts with 500XP and every session starts with 0 Ship XP.
- **XP multiplier** (default value: 100)

  Defines the multiplier for gained XP. **NOTE: Will only be used when Save progress is off.**
- **Starting XP** (default value: 500)

  Defines the starting XP. **NOTE: Will only be used when Save progress is off.**

### Server\Items.cfg

All items in this configuration can be configured with the following properties:
- **Active** (default value: true)

  Is this item purchaseable by players?
- **Price** (default value: item-dependent)

  The price of this item.
- **Max discount** (default value: item-dependent)

  The maximum discount this item can have.
- **Weight** (default value: item-dependent)

  The weight of this item

The following items can be configures:
- Boombox (price: 60; max discount: 80; weight: 16)
- Extension ladder (price: 60; max discount: 60; weight: 0)
- Flashlight (price: 15; max discount: 80; weight: 0)
- Jetpack (price: 700; max discount: 80; weight: 52)
- Lockpicker (price: 20; max discount: 80; weight: 16)
- Pro flashlight (price: 25; max discount: 80; weight: 5)
- Radar booster (price: 60; max discount: 80; weight: 19)
- Shovel (price: 30; max discount: 80; weight: 19)
- Spray paint (price: 50; max discount: 80; weight: 0)
- Stun grenade (price: 30; max discount: 80; weight: 5)
- TZP inhalant (price: 120; max discount: 80; weight: 0)
- Walkie talkie (price: 12; max discount: 80; weight: 0)
- Zap gun (price: 400; max discount: 80; weight: 10)
- Swimming fins (price: 80, max discount: 40; weight: 5)
- Rocket boots (price: 100; max discount: 50; weight: 5)
- Night vision (price: 200; max discount: 50; weight: 8)
- Missile launcher (price: 150; max discount: 50; weight: 8)
- Bulletproof vest (price: 100; max discount: 50; weight: 15)
- Lightning rod (price: 120; max discount: 50; weight: 50)

The following items have extra configuration properties:
- **Bulletproof vest**

  - **Max damage** (default value: 90)

    The maximum amount of damage the vest can withstand.
  - **Turret damage** (default value: 5)

    The damage a turret bullet will deal to the vest.
  - **Shotgun damage** (default value: 30)

    The damage a shotgun bullet will deal to the vest.
  - **Damage reduction at full health** (default value: 100)

    The damage reduction the vest will have when at full health in percent.
  - **Damage reduction at no health** (default value: 50)

    The damage reduction the vest will have when at zero health in percent.
  - **Destroy at no health** (default value: true)

    Should the vest get destroyed when reaching its damage reaches max damage.
- **Night vision**

  - **Battery time** (default value: 180)

    The time in seconds of charge.

### Server\Moons.cfg

#### Moon base prices
- **Experimentation** (default value: 0)

  The price for Experimentation.
- **Vow** (default value: 0)

  The price for Vow.
- **Experimentation** (default value: 0)

  The price for Experimentation.
- **Assurance** (default value: 0)

  The price for Assurance.
- **Offense** (default value: 0)

  The price for Offense .
- **March** (default value: 0)

  The price for March.
- **Rend** (default value: 550)

  The price for Rend.
- **Dine** (default value: 600)

  The price for Dine.
- **Titan** (default value: 700)

  The price for Titan.
- **Deactivate custom prices** (default value: false)

  Activating this option will remove all moon price logic from the mod. (Travel discount perk will automatically be removed)

#### Weather multipliers
- **Clear scrap amount** (default value: 100)
  
  The amount of scrap in percent. 100% being vanilla.
- **Clear scrap value** (default value: 100)

  The value of scrap in percent. 100% being vanilla.
- **Foggy scrap amount** (default value: 100)
  
  The amount of scrap in percent. 100% being vanilla.
- **Foggy scrap value** (default value: 100)

  The value of scrap in percent. 100% being vanilla.
- **Rainy scrap amount** (default value: 110)
  
  The amount of scrap in percent. 100% being vanilla.
- **Rainy scrap value** (default value: 110)

  The value of scrap in percent. 100% being vanilla.
- **Flooded scrap amount** (default value: 130)
  
  The amount of scrap in percent. 100% being vanilla.
- **Flooded scrap value** (default value: 120)

  The value of scrap in percent. 100% being vanilla.
- **Stormy scrap amount** (default value: 150)
  
  The amount of scrap in percent. 100% being vanilla.
- **Stormy scrap value** (default value: 150)

  The value of scrap in percent. 100% being vanilla.
- **Eclipsed scrap amount** (default value: 180)
  
  The amount of scrap in percent. 100% being vanilla.
- **Eclipsed scrap value** (default value: 150)

  The value of scrap in percent. 100% being vanilla.
- **Deactivate multipliers** (default value: false)

  Activating this option will remove all multiplier logic from the mod.

### Server\PlayerPerks.cfg

All perks share the same parameters (besides "**Inventory size**" missing a change property).

Deactivated perks will still apply their base value to the player. So if you don't want to play with the perks system but still want to adjust some parameters of the players, deactivate all perks and change the base values accordingly.

The following parameters are available per perk:
- **Active** (default value: true)

  Determines if this perk is purchaseable.
- **Base value** (default value: perk-dependent)

  The base value every player starts with in percent.
- **Change** (default value: perk-dependent)

  The change in percent per perk level in percent.
- **Costs** (default value: perk-dependent)

  Comma separated list: The XP price per level. The number of values determine the max level.

The following perks are available:
- **Climbing speed**
- **Critical strike chance**
- **Damage reduction**
- **Fall damage reduction**
- **Inventory size**
- **Jump height**
- **Jump stamina**
- **Sprint speed**
- **Sprint stamina**
- **Weight influence**

### Server\ShipPerks.cfg

All perks share the same parameters.

Deactivated perks will still apply their base value. So if you don't want to play with the perks system but still want to adjust some parameters, deactivate all perks and change the base values accordingly.

The following parameters are available per perk:
- **Active** (default value: true)

  Determines if this perk is purchaseable.
- **Base value** (default value: perk-dependent)

  The base value every player starts with in percent.
- **Change** (default value: perk-dependent)

  The change in percent per perk level in percent.
- **Costs** (default value: perk-dependent)

  Comma separated list: The XP price per level. The number of values determine the max level.

The following perks are available:
- **Delivery speed**
- **Extend deadline discount**
- **Extra battery**
- **Landing speed**
- **Loot saver**
- **Scan distance**
- **Travel discount**

### Server\Lobby.cfg

Allows you to deactivate the bigger lobby functionality of the mod. Other bigger lobby mods probably wont be entirely compatible with this mod. All connecting clients need the same settings for this file as they cant be synchronized as they decide how to patch the game assemblies.

- **Active** (default value: true)

  Activates the bigger lobby functionality. Please ensure that all connecting clients have the same settings or else this will lead to desyncs. Other bigger lobby solutions might not work at all or suffer from bugs when playing with more than 4 players.
- **Max players** (default value: 32)

  The maximum size for the lobby. 32 is the max.

### Client\File.cfg
  
#### Local progress
- **Save in profile** (default value: false)

  If the progress of your player should be saved in the profile folder or globally.

### Client\UI.cfg
  
#### Hotbar
- **Alpha** (default value: 13)

  How transparent the hotbar becomes when not used or carrying a two handed item. 0% = invisible, 100% = opaque.
- **Scale** (default value: 100)

  Scale for hotbar slots.
  
### Client\Keybinds.cfg
#### Inventory
- **Inventory Slot 1** (default value: <Keyboard>/1)

  Keybind for first inventory slot.
- **Inventory Slot 2** (default value: <Keyboard>/2)

  Keybind for second inventory slot.
- **Inventory Slot 3** (default value: <Keyboard>/3)

  Keybind for third inventory slot.
- **Inventory Slot 4** (default value: <Keyboard>/4)

  Keybind for fourth inventory slot.
- **Inventory Slot 5** (default value: <Keyboard>/5)

  Keybind for fifth inventory slot.
- **Inventory Slot 6** (default value: <Keyboard>/6)

  Keybind for sixth inventory slot.
- **Inventory Slot 7** (default value: <Keyboard>/7)

  Keybind for seventh inventory slot.
- **Inventory Slot 8** (default value: <Keyboard>/8)

  Keybind for eight inventory slot.
- **Inventory Slot 9** (default value: <Keyboard>/9)

  Keybind for ninth inventory slot.
- **Inventory Slot 10** (default value: <Keyboard>/0)

  Keybind for tenth inventory slot.
- **Invert scroll direction** (default value: true)

  Invert the scroll direction.

#### Items
- **Flashlight** (default value: <Keyboard>/f)

  Keybind to toggle flashlight.
- **Night Vision** (default value: <Keyboard>/f)

  Keybind to toggle night vision.

## Support
If you speak German you might find interest in my content:

https://www.youtube.com/PotatoePet

https://www.twitch.tv/PotatoePet

If you really want to financially support me, you can do so here:

https://ko-fi.com/PotatoePet

# Credits
**Programming:**
- PotatoePet

**3D Models:**
- PotatoePet

- Rocket boots are based on the model of Shao-Khan

  https://www.cgtrader.com/free-3d-models/character/clothing/dirty-shoes

- Warplane toy based on 3D scan of adekvat
  
  https://www.cgtrader.com/free-3d-models/scanned/various/old-ussr-soviet-metal-toy-airplane

- Tank toy based on 3D scan of adekvat

  https://www.cgtrader.com/3d-models/scanned/various/old-ussr-soviet-metal-toy-tank-scan-high-poly

- Toy car based on 3D scan of adekvat

  https://www.cgtrader.com/3d-models/scanned/various/old-ussr-soviet-metal-toy-car-ural-juices-water

- WML-H2 by Mayess

  https://sketchfab.com/3d-models/wml-g2-04f05da3b9a8400f904f70500081402d
  
- PBR Tactical Helmet by Simon Coenen

  https://sketchfab.com/3d-models/pbr-tactical-helmet-ad5de2de22af429cbcaf2a96e3520b80
  
**Sounds:**

- CC0 from freesound.org

  Edited by **PotatoePet**

**Tester:**
- Zesicion
- xxXDerJokerXxx
- xPapaWolfix