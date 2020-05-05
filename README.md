# esx_repairkit [![Release](https://img.shields.io/badge/Release-V%203.0-blue)](https://github.com/clementinise/esx_repairkit/releases/latest)

RepairKit script for FiveM ESX servers - https://forum.cfx.re/t/fork-esx-esx-repairkit-repairkit-item-for-car/1133523

## FEATURES
* Repair Kit Item, Tire Kit, and Body Kit Item
* More realistic since it needs you to be next to the vehicle engine, near the tyre, or near the car to actually repair
* Repair Kit does not repair the visual aspect of the car, only the engine
* Body Kit repairs the visual aspect of the car
* Player can abort the repair by pressing "X"
* Message if players attempt to repair the car and are not in front of the tire or engine
* English language included
## RepairKit, TyreKit, and BodyKit easily configurable: 
* **Config.RepairTime, Config.TyreKitTime, Config.BodyKitTime**
Set in seconds, how long should a repair take
* **Config.RealisticVehicleFailure**
 If you're using [Realistic Vehicle Failure](https://forum.cfx.re/t/release-realistic-vehicle-failure/57801) then you can set it to true (Since “RealisticVehicleFailure” change how cars work, this config option allow to set the engine repair value lower than usual so the repaired vehicle is not indestructible)
* **Config.ExplosionChance**
The lower it is, the more it has a chance to make the engine fail and the car explode. (1 = 100%, 2 = 50%, 4 = 25%, 10 = 10%, 100 = 1%, etc)
*If you don't want this feature, set **Config.ExplosionOnFailedRepair** to false*

Some new features will be added soon:  t̶i̶r̶e̶ ̶k̶i̶t̶,̶ ̶%̶ ̶f̶a̶i̶l̶u̶r̶e̶,  can't be used again after X times, change key for cancelling the repair in config file, etc

### Requirements
* [es_extended](https://github.com/ESX-Org/es_extended)

### Installation
Download the [latest release](https://github.com/Demo4889/esx_repairkit) and rename the folder to esx_repairkit.

Import `esx_repairkit.sql` to your database
Drag the folder into your `<server-data>/resources/[esx]` folder and add this to your server.cfg
```
start esx_repairkit
```
