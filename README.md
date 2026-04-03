# YigitDutarRollABallGame

## About The Project
This repository contains my midterm project for the Unity Roll-a-Ball tutorial. The Unity project itself is named `RollABallGame`. This README serves as my game development diary, documenting the steps I took, the concepts I learned, and the overall process.

## Development Diary & Steps Completed
Following the class instructions, I successfully implemented the following stages:

1. **Setting up the game:** Created the initial Unity project, set up the basic scene, and organized the project structure with meaningful folder names (`Scenes`, `Materials`, `Scripts`, etc.).
2. **Moving the player:** Added a Sphere to act as the player, attached a Rigidbody component for physics, and created a script to handle movement using Unity's Input System.
3. **Moving the camera:** Created a camera controller script to ensure the main camera smoothly follows the player object by maintaining a constant offset, without rotating alongside the ball.
4. **Setting up the play area:** Built the physical environment by adding a ground plane and walls to keep the player within bounds.
5. **Creating collectibles:** Designed cube prefabs to act as collectible items ("PickUps"), added a simple rotation script for visual appeal. 

## What I Learned
Through developing this project, I gained hands-on experience with several core Unity and game development concepts:
* **Physics and Rigidbodies:** Understanding how to apply forces to objects to make them move realistically.
* **Input Handling:** Capturing user input to control a GameObject seamlessly.
* **Camera Manipulation:** Using vector math to calculate and update camera positions in the `LateUpdate` method.
* **Colliders and Triggers:** Differentiating between physical collisions (walls/ground) and trigger events (collectibles).
* **Prefabs:** Creating reusable GameObjects to efficiently populate the scene.
* **Version Control:** Properly configuring a `.gitignore` file to ensure large, auto-generated files (like the `Library` folder) are not pushed to the repository, keeping the commits clean and meaningful.

## Challenges and Problem Solving
The development process went very smoothly. By carefully following the steps we covered in class and organizing my workflow, I did not encounter any errors with Unity, the C# scripts, or my GitHub repository. Because the process was error-free, I didn't need to use any AI tools for debugging or error resolution.