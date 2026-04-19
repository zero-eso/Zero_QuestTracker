# Zero Quest Tracker

Zero Quest Tracker is a continuation of **Ravalox' Quest Tracker**, which itself continued **Wykkyd's QuestTracker**.

This repository is intentionally moving forward under the **Zero Quest Tracker** name. It is **not** meant to be the ongoing maintenance home for "Ravalox' Quest Tracker" as a brand. Just like the project changed hands and identity before, this continuation is preserving the lineage and credit while taking the add-on in its own direction.

## Continuation Notice

- This project continues the quest tracker line that ran from Wykkyd to Ravalox/Calia and later through Calamath's maintenance work.
- This project is **not** an official mirror or future maintenance branch for the addon under the "Ravalox' Quest Tracker" name.
- This repository will ship **Zero Quest Tracker** features, branding, and release decisions going forward.

## Lineage And Credits

- **Wykkyd**: original quest tracker lineage.
- **Ravalox Darkshire** and **Calia1120**: built and maintained **Ravalox' Quest Tracker**.
- **Calamath**: carried the addon forward through later ESO updates, API changes, and rename work on the ESOUI release line.
- **Zero**: continuing from that maintained codebase and taking the tracker in a new direction as **Zero Quest Tracker**.

## Upstream Reference

- Original lineage / maintained ESOUI release page: [Ravalox' Quest Tracker on ESOUI](https://www.esoui.com/downloads/info13-WykkydsQuestTools.html)

## Special Thanks

Special thanks to **Calamath** for keeping this addon alive long after the original handoff. The recent maintenance work, API compatibility updates, and rename handling on the ESOUI release line are a meaningful part of why this continuation exists at all.

## Project Direction

Zero Quest Tracker is keeping the core tracker concept, but it is no longer aiming to be a quiet compatibility-only maintenance pass of the Ravalox release line.

The direction here is:

- keep the quest tracker stable on current ESO builds
- preserve proper credit to the addon lineage
- rename and brand the addon clearly as a **Zero** project
- add new feature work and UI behavior that go beyond the old maintenance scope

## Current Zero Changes In This Tree

The current source already includes several Zero-specific changes and upgrades:

- **Proper ESO font outlining support** for zone/category text, quest text, and condition/objective text
- Full outline/effect choices including **Outline**, **Thin Outline**, **Thick Outline**, soft shadow variants, and standard shadow support
- A dedicated **Quest Colorization Options** section in settings
- **Colorize Quests** support that can:
  - color the active zone/category differently from inactive zones
  - color the selected quest differently from other quest names
  - color non-selected quest names by **overall quest completion** using a readable pastel red-to-green range
  - color quest steps/objectives by incomplete vs complete state, with progress-aware interpolation where applicable
- A **Show Tracker Now** option in settings so the tracker can be forced visible while configuring it
- Optional **titlebar text** so the tracker can display the Zero Quest Tracker name in the header area
- Settings cleanup work, including clearer section organization and an **About** section
- Zero branding updates so the addon name is consistently presented as **Zero** in purple with the remainder in white

## Installation

1. Install the folder as `Zero_QuestTracker` under:
   `Documents/Elder Scrolls Online/live/AddOns/`
2. Install required libraries:
   - `LibAddonMenu-2.0` version 41 or newer
   - `LibCustomMenu` version 730 or newer
3. Start ESO and enable the addon from the AddOns menu.

## Current Addon Metadata

- Add-on folder: `Zero_QuestTracker`
- Saved variables: `QuestTrackerSavedVars`
- API version: `101049`
- Add-on version: `R0.0.1`

## Notes

- Open the settings panel with `/zqt`.
- This repository reflects the current local source tree and is being organized as the starting point for future Zero Quest Tracker development.
