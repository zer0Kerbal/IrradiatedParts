---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.7.0
Hot Beverage Inc - Irradiated Parts (HBI/IP)
created: 01 Oct 2019
updated: 18 Apr 2022 -->

<!-- based upon work by Lisias -->

# Hot Beverage Inc - Irradiated Parts (HBI/IP)

[Home](./index.md)

Hot Beverage Inc - Scalding Hot Parts! Now with more irradiation! For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `HotBeverageInc` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/HotBeverageInc/IrradiatedParts`
* Extract the package's `HotBeverageInc/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/HotBeverageInc` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/HotBeverageInc/IrradiatedParts`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/HotBeverageInc/IrradiatedParts`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/HotBeverageInc/IrradiatedParts`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [HotBeverageInc]
      + [IrradiatedParts]
        + [Compatibility]
        + [Config]
        + [Localization]
          ...
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * changelog.md
        * License.txt
        * readme.htm
        * IrradiatedParts.version
    ...
  * KSP.log
  ...
```

### Dependencies

* [Hot Beverage Inc (HBI)][HBI]

[HBI]: https://forum.kerbalspaceprogram.com/index.php?/topic/29844-* "Hot Beverage Inc (HBI)"
