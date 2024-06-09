# Starcraft II Terran Hotkeys

After playing **Terran** for several years using the standard hotkey setup I found that these changes made it easier to play:

## Reassigning default hotkeys placed on the RIGHT SIDE to the LEFT SIDE of the keyboard


| Unit           | Ability         | Default | New   |
|----------------|-----------------|---------|-------|
| SCV            | Patrol          | P       | Z     |
| SCV            | Build Bunker    | U       | Z     |
| Bunker         | Load            | L       | C     |
| Command Center | Load            | O       | C     |
| Command Center | Lift/Land       | L       | Space |
| Command Center | Upgrade To PF   | P       | F     |
| Factory Tech Lab| Blue Flame     | I       | F   |
| Ghost          | Nuke            | N       | X   |
| Armory         | Vehicle Plating | V       | V,A   |
| Battlecruiser  | Hyperjump       | T       | V   |


Command Center and Bunker Load ability gets reassigned to same hotkey as Medivac Load Ability hotkey.

Armory gets an alternative hotkey for Vehicle Plating that is the same as Infantry Armor hotkey. 

Battlecruiser Hyperjump ability gets reassigned to **V** so that Yamato Cannon can be used with rapid fire.

## Abilities with RAPID FIRE

| Unit            | Ability       |
|-----------------|---------------|
| Ghost           | Snipe         |
| Orbital Command | Calldown MULE |
| Cyclone         | Lock On       |
| Liberator       | Defender Mode |
| Battlecruiser   | Yamato Cannon |
| Raven           | Auto-Turret   |
| Reaper          | Granate       |

Pressing **T** while having one of these units selected will auto-cast their ability at your mouse location. You can still use the default hotkey for their ability but it will not have rapid fire.

## How to install these hotkeys

Create a custom hotkey profile in-game based on the standard hotkey profile and manually update your hotkeys

**OR**

Download [StandardTerran](https://github.com/Zaokret/sc2-terran-hotkeys/blob/main/StandardTerran.SC2Hotkeys) profile, and place it in:

> Documents -> StarCraft II - > Accounts - > Account_ID -> Hotkeys

StandardTerran.SC2Hotkeys
```
[Settings]
AllowSetConflicts=1

[Hotkeys]
AlertRecall=
TargetChoose=LeftMouseButton,T

[Commands]
Bunker/SCV=Z
BunkerLoad=C
CalldownMULE/OrbitalCommand=E,T
ChannelSnipe/Ghost=R,T
CommandCenterLoad=C
Hyperjump/Battlecruiser=V
KD8Charge/Reaper=D,T
Land=Space
LiberatorAGMode/Liberator=E,T
Lift=Space
LockOn/Cyclone=C,T
LocustMPFlyingSwoop/LocustMPFlying=
MovePatrol=Z
NukeCalldown/Ghost=X
ResearchHighCapacityBarrels/FactoryTechLab=F
TerranVehicleAndShipPlatingLevel1/Armory=V,A
UpgradeToPlanetaryFortress/CommandCenter=F
YamatoGun=Y,T

```
