# Changelog 

| modName    | Nuke's Tiny Pods (NtP)                                         |
| ---------- | ----------------------------------------------------------------- |
| license    | GPL-2.0                                                           |
| author     | zer0Kerbal                                                        |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209393-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/NukesTinyGirder)        |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/NukesTinyGirder)      |
| spacedock  | (https://spacedock.info/mod/3085)                                 |
| ckan       | NukesTinyGirder                                                   |

## Version 0.9.99.0-adoption - `<Thank you Nuke>` edition

* 16 Aug 2022
* Release for Kerbal Space Program [KSP 1.12.x]

### Adoption by zer0Kerbal

### Summary

* Split off from Nukes Tiny Parts
* this is the first in a series of updates to Nukes Tiny Girders
* smaller updates make updating the addon much more manageable.
* Included <ghostparts.cfg>

### Update License

* Updated License: GPL-2.0
  * was: Public Domain
* closes #24 - Updated  License

### docs/

* Add
  * [`_config.yml`]
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [Disclaimer.md] v1.0.1.0
  * [PartCatalog.md] v1.1.4.1
  * [Why.md] v1.1.0.0
* closes #25 - docs/

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* closes #26 - Asset Updates

### Localization 0.9.99.0

* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* updates #5 - Localization Master
* closes #6 - Localization - English <en-us.cfg>
* updates #23 - Part Localization
* closes #27 - Localization

### Add localized tags to parts

* Add
  * [NukesTinyPods.cfg] v1.0.0.0
    * adds localized tags to parts
* closes #28 - Add localized tags to parts

### Img

* Create
  * Hero.png
* closes #29 - Create Hero.png

### Parts 0.9.99.0

* Rename parts to unique names following the pattern `ntp-<PART-NAME>`
  * [halfMeterCockpit] --> [ntp-cockpit]
    * Update
    * based upon stock Mark1Cockpit
    * [TechRequired] = aviation // advFlightControl
    * entryCost = 5000 // 10500
    * cost = 1250 // 2100
    * tags = #autoLOC_500309
    * [ModuleCommand]
      * no hibernation
      * add control points
    * [ModuleSAS]
      * [SASServiceLevel] from nothing to 1
    * [ModuleReactionWheel]
      * [ElectricCharge] from 0.1 to 0.2
  * Internal
    * ntp-cockpit
  * Possible changes:
    * needs further input and discussion
    * based upon stock Mark1Cockpit
    * minimum_drag = 0.09 // 0.1
    * angularDrag = 0.9 // 2
    * maxTemp = 2100 // 1100
    * skinMaxTemp = 2750 // 2000
  * Add
    * <ghostparts.cfg> to attempt to prevent any damage to existing save games.
    * is not permanent. will be removed when the mod is updated to 1.0.0.0-release
* Rename filename to unique filenames following the pattern `ntg-<PART-NAME>`
  * <hmCockpit.cfg> --> <ntp-cockpit.cfg>
  * <PropConfig.cfg> --> <halfMeterCockpitInterior.cfg>

### Compatibility 0.9.99.0

* Create
  * [TweakScale.cfg] 1.0.0.0

### Status 0.9.99.0

* Issues
  * closes #1 - Nuke's Tiny Girder (NtG) 0.9.99.0-adoption `<Thank you Nuke!>`
  * closes #2 - 0.9.99.0 Create Legal Mumbo Jumbo
  * closes #3 - 0.9.99.0 Create Documentation
  * closes #4 - 0.9.99.0 Create Social Media

---

## Version 0.7.0.0 - `<unreleased>`

* yes, I have it

---

## Version 0.6.0.0 - `<6-ish>`

### compatible with newer versions > 1.0

* built in tweakscale support, replaces large varients of parts (requires mod man)
* ckan compatibility
* extra redundency
* the micro girder kit i teased about years ago now has rudementry textures.
* the readme wasnt snarky enough so i added mor snark.
* extra redundency
* 27% more new bugs
* some of my particle effects are now borked, they need to be remade under the new system (known issue)
* extra redundency

---

## Version 0.5.0.0 - `<fred 5>`

### the release that never was. mostly fixing things broke from the tansition to ksp 1.0

---

## Version 0.4.0.0 - `<delta 4>`

### KSP 0.20 compatibility (now uses new mod heirarchy)

* all textures are now png
* NEW! structural lattice construction kit
* some parts now come in a larger sizes
* better colliders for parts that had bad colliders (like the cockpit and the tail boom)
* depricated arrrghohn, all hall thrusters and mpd engines now use xenon
* resized fuel tanks to more strict specifications to make them compatible with the new lattice elements
* rebalenced some parts (mono tank is a lot less useless now)
* atmospheric vtol engine can now be throttled more quickly
* *known issue* 0.20 broke the sound effects so that badass mpd thruster sound doesnt work

---

## Version 0.3.0.0 - `<gamma 3>`

### moar parts

* a lot more parts
* some of them even work
* new resources
* atmospheric bits
* some ships
* and a cockpit
* also no longer calling it a beta since i dont need a reason
* this version requires at least ksp v.18

---

## Version 0.2.0.0 - `<beta 2>`

* fixed normal maps for long and short tanks, and the nosecone
* mpd thruster overheat animation looks better now
* mpd thruster now produces less heat and is less prone to self destruction
* mpd thruster weight reduction from 1.2 to 0.8
* gimbal ranges reduced on mpd thruster and gimballed engine to compensate for bang bang control

---

## Version 0.1.0.0 - `<beta 1>`

### Creation by Nuke

* initial release

---
