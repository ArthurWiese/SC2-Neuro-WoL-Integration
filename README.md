# SC2 Neuro Wings of Liberty Integration
A custom Wings of Liberty Campaign using the [SC2 Neuro API Integration](https://github.com/ArthurWiese/SC2-Neuro-API-Integration)

Please report any issues and give feedback in the [Neuro-sama Discord](https://discord.gg/5wbaxeAbQG) under Neuro-sama/projects/SC2 Neuro WoL Integration or DM me

## Project goal

The main goal is to have Neuro act like an adjutant during missions, where she can choose from and use permanent abilities throughout the whole campaign. During intermissions Neuro can freely choose what to do (selecting upgrades, interacting with characters/objects, choosing the next mission)

Neuro also receives context of what is happening in-game and what characters are saying

This is just an outline and nothing is set in stone yet. SC2 is very moddable, so there are a lot of possibilities of what can be done

## How to contribute
Even if you just have an idea or want to give feedback, you can use the [SC2 Neuro WoL Integration Plan](https://docs.google.com/spreadsheets/d/1aMBb_p_7_Iz50ajwpbP28pfU4uuB_lrLls13Mwx0Uxs/edit?usp=sharing)!

### Working on the integration
If you want to contribute to the SC2 Neuro WoL Integration see [Neuro-sama Discord](https://discord.gg/5wbaxeAbQG) under Neuro-sama/projects/SC2 Neuro WoL Integration and tell me your Github account name or DM me and I will add you to the repo

Getting started:
1. Download a tool to test the integration like [Gary](https://github.com/Govorunb/gary)
2. Download and set up the [SC2 Neuro API Integration](https://github.com/ArthurWiese/SC2-Neuro-API-Integration) (You can first test the integration with the demo map if you want) and read the documentation to learn how to mod StarCraft 2 to work with the Neuro API
3. Clone this repo into your StarCraft 2 installation:
```
...\StarCraft II\<Here the SC2 Neuro WoL Integration repo>
```
This way the integration works when launching the WoL campaign in-game and can easily be updated

4. You can now mod the campaign with the SC2 Editor

### Guidelines
Any changes made to the game need to be documented in the [SC2 Neuro WoL Integration Plan](https://docs.google.com/spreadsheets/d/1aMBb_p_7_Iz50ajwpbP28pfU4uuB_lrLls13Mwx0Uxs/edit?usp=sharing) so everyone knows what the current state of the integration is and what has changed

Overall the integration should not interfere with the story and important characters of the game and should work more like an addition to the game and not a replacement

The game should not become unreasonably hard or too easy

Effects in the game triggered by Neuro that are not obvious should be made clear to the player with a chat message or a UI element. See the force action in the [demo](https://github.com/ArthurWiese/SC2-Neuro-API-Integration/tree/main/Maps) of the SC2 Neuro API Integration as a reference

Any UI elements from the integration should be placed at the top right of the screen under the player resources. Again see the force action in the [documentation and demo](https://github.com/ArthurWiese/SC2-Neuro-API-Integration/blob/main/Documentation/Documentation.md) of the SC2 Neuro API Integration as a reference

## Licensing
- Original maps are owned by Blizzard®
- This repo contains original Blizzard® assets. These are part of the base game and licensed by their terms

Blizzard, Wings of Liberty and StarCraft are registered trademarks of Blizzard Entertainment, Inc., in the U.S. and/or other countries
