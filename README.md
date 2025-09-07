[TOC]

# MGS.Assemblyman

## Summary
- Editor to analyse assembly.

## Ability
- Show assemblies reference by a lib.
- Show assemblies reference to a lib.
- Show assemblies reference mutual.

## Install

- Unity --> Window --> Package Manager --> "+" --> Add package from git URL...

  ```text
  https://github.com/mogoson/MGS.Assemblyman.git?path=/Assets
  ```

## Usage

1. Find the menu item "Tool/Assemblyman" in Unity editor menu bar and click it or press key combination Alt+M to open the "Assemblyman" editor window.
2. Input keywords into the left text box to filter the assemblies that you do not wan to care.
3. Input keywords into the right text box to select the assemblies that you need care.
4. The workspace view will show assemblies references infos.
   - Main assemblies show as white color.
   - Reference assemblies show as gray color.
     - Assemblies referenced by the main assembly show before the separator "-><-" line.
     - Assemblies referenced to the main assembly show after the separator "-><-" line.
   - Reference mutual assemblies show as red color.

------

Copyright © 2025 Mogoson.	mogoson@outlook.com