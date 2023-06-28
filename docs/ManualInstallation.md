---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.0.1.0
Nuke's Tiny Pods (NtP)
created: 16 Aug 2022
updated: 27 Jun 2023

TEMPLATE: ManualInstallation.md v1.1.9.1
created: 01 Feb 2022
updated: 26 Apr 2023

based upon work by Lisias -->
## [Nuke's Tiny Pods (NtP)][mod]

[Home](./index.md)

Tiny part addon that adds Nuke's Tiny Pods (okay, just one for now) for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `Nuke` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/Nuke/NukesTinyPods`
* Extract the package's `Nuke/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/Nuke` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/Nuke/NukesTinyPods`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/Nuke/NukesTinyPods`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/Nuke/NukesTinyPods`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [Nuke]
      + [NukesTinyPods]
        ...
      + [NukesTinyPods]
        + [Assets]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        + [Spaces]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * changelog.md
        * GPL-2.0.txt
        * ManualInstallation.htm
        * NukesTinyPods.version
        * readme.htm
      ...
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Nuke's Unlimited (NU)](https://www.curseforge.com/kerbal/ksp-mods/NukesUnlimited)

THIS FILE: CC BY-ND 4.0 by [zer0Kerbal](https://github.com/zer0Kerbal)
  used with express permission from zer0Kerbal

[mod]: https://www.curseforge.com/kerbal/ksp-mods/NukesTinyPods "Nuke's Tiny Pods (NtP)"