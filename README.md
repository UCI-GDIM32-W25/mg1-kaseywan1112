[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## Devlog
Yaokun Wan, He/him

In my MG1 plan, the player is responsible for movement and planting seeds, which is implemented in the Player class. In Player.cs, I used variables such as _speed and _playerTransform to control player movement in the Update() method. Planting is handled through the PlantSeed() method, which uses _plantPrefab to instantiate a plant, _numSeeds to track how many seeds the player starts with, and _plantCountUI to update the UI. When SPACE is pressed, PlantSeed() checks if seeds are available, spawns a plant at the player’s position, decreases the remaining seed count, and increases the planted seed count, directly matching the steps outlined in the MG1 breakdown.

The UI portion of the plan is implemented using the PlantCountUI class, which is connected to the Canvas GameObject in the Unity scene. The UpdateSeeds() method updates the TextMeshPro objects that display the number of seeds planted and remaining. The plant object itself exists only as a prefab, which is assigned to the Player script in the Inspector, ensuring that no plants are present in the scene at the start of the game. The Player and Plant GameObjects use different sprites, making them visually distinct and satisfying the MG1 requirements.


## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
