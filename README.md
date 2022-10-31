# Lancer Battlegroup - PC Data
PC facing data for Lancer Battlegroup, made for use in the LANCER system of Foundry VTT

Inspired by Annatar's [Lancer Battlegroup NPC Data](https://gitlab.com/lancerbattlegroupforge/lancer-battlegroup-npc-data) module

This module is not an official Lancer product; it is a third party work, and is not affiliated with Massif Press. This module is published via the Lancer Third Party License.
Lancer is copyright Massif Press

Uses images made by Suki for the default hull, escort and wing tokens, which can be found here: https://sukirpg.itch.io/battlegroup-tokens

# Usage:
Add this module to your Foundry installation using a link to the provided manifest, then enable it in a world created with the Lancer System.

This will import all the compendiums in this module into your world, which can then be used to import the actors and items as needed.

The workflow for creating a battlegroup should be as follows. I recommend using the [Battlegroup Character Sheet](https://docs.google.com/spreadsheets/d/1B2mDih9nVdmUvATLborDgYwR-QjV-mo3SYWkQ3jSPBA/edit?usp=sharing) to create and stat out your fleet before transfering it to Foundry

### Workflow:
- Import a ship from the PC Hull Actors compendium
- Add the Flagship system from the PC Ship Systems compendium if this is your designated flagship
- Fill out weapons and systems by dragging and dropping from the relevant compendiums, keeping in mind the conventions used (described below)
- Import payload, escort and wing deployables for ease of tracking
- Name ship, change token image if desired
- Repeat until battlegroup is done

## Conventions:
- **Main** weapon slots are for **Primary** weapons
- **Heavy** weapon slots are for **Superheavy** weapons (Bracing included in actors as a bit of a hack to make them work well with base Lancer weapons)
- **Flex** and **Aux** weapon slots are for **Auxiliary** weapons
- **Systems** are used for both **Ship Systems** as well as tracking a ship's **Escorts** and **Wings**. SP is the number of System slots a ship has.
- **Ace Squadrons** are implemented as a Mech/Mech Frame instead of a Deployable, for ease of customizing with Ace Systems.

## Automation and Missing Features:
Flagship HP increase and System slot are automated. Bulwark Redundancies and Casque Armor's HP increases are automated.

Interdiction is not implemented in this module.
