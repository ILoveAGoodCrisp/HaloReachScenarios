# HaloReachScenarios
A collection of Halo Reach Scenario BSPs in Blender. Ready to be exported back into the game.

Multiplayer BSPs have been fixed up to ensure pathfinding can be generated.

## Requirements

- [The Halo Reach Editing Kit](https://store.steampowered.com/app/1695793/Halo_Reach_Mod_Tools__MCC/)
- [Blender](https://www.blender.org/download/)
- [The Foundry Extension for Blender](https://github.com/ILoveAGoodCrisp/Foundry)

> [!IMPORTANT]
> If you already have Foundry installed, please ensure you are on the latest version before using the blends in this repo

## How to use
- Download the github repository via your preferred method. If you're unfamiliar with Github easiest way to do thisis to click the green `Code` button near the top of this page and select `Download Zip`
- Once downloaded, you can either work directly with the repository or copy the data folder over to your Halo Reach Editing Kit
- You can now open the blends contained within your repository to work on any of the scenarios of your choosing. Ensure that [Foundry](https://github.com/ILoveAGoodCrisp/Foundry) is loaded as an extension. A guide to install this extension can be found [here](https://github.com/ILoveAGoodCrisp/Foundry?tab=readme-ov-file#installation)
> [!NOTE]
> The campaign blend files are very large and viewport performance may be poor. Under Foundry Scene Properties there is a file split option which will split each scenario bsp into its own Blend file. You can then right click on a BSP collection in the Blender outliner and open the new blend directly
- To export a scenario and see it in game, simply press the `Export` button present in the Foundry bar within the Blender 3D viewport. Once the export is complete, you can press either the Sapien or Tag Test buttons in the Foundry Bar to load the scenario in game
> [!TIP]
> Instance imposters have been disabled by default on export, should you wish to generate imposters for your export you will need to undo this setting. Click the arrow besides the export button and uncheck `Disable Instance Imposters`

> [!TIP]
> Lightmapping can be done in Blender during export, however on larger files it is recommended to use a tool like [Osoyoos](https://github.com/num0005/Osoyoos-Launcher) for lightmapping due to the high memory usage of certain Blender scenes



## Contributers
- [Pepper-Man](https://github.com/Pepper-Man)
- [Crisp](https://github.com/ILoveAGoodCrisp)
- UndeadKiva
- [Krevil](https://github.com/Krevil)
