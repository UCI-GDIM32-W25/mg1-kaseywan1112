[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## Devlog
Yaokun Wan, He/him

In my MG1 plan, the player is responsible for movement and planting seeds, which is implemented in the Player class.
In Player.cs, I used variables such as _speed and _playerTransform in the Update() method to control player movement based on keyboard input.

Planting is handled through the PlantSeed() method.
This method uses _plantPrefab to instantiate a plant at the player’s position, uses _numSeeds to track how many seeds the player starts with, and uses _plantCountUI to update the UI.
When the SPACE key is pressed, PlantSeed() checks if seeds are available and then updates the planted and remaining seed counts.

The UI portion of the plan is implemented using the PlantCountUI class, which is connected to the Canvas GameObject in the Unity scene.
The UpdateSeeds() method updates the TextMeshPro objects that display the number of seeds planted and the number of seeds remaining.


## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
