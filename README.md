# A Maze
Starter project for the Udacity [VR Developer Nanodegree](http://udacity.com/vr) program.

- Course: VR Software Development
- Project: A Maze


### Versions Used
- [Unity LTS Release 2017.4.19](https://unity3d.com/unity/qa/lts-releases?version=2017.4)
- [GVR SDK for Unity v1.170.0](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.100.1)


### About the Starter Project
The included starter project represents a new Unity project where the following have been done:
- All assets needed to complete the project according to the project rubric have been imported.
- The imported models have been placed in the scene and organized in the scene hierarchy.
- Colliders have been added to the `Coin`, `Key`, `Left_Door`, `Right_Door`, and `The_Temple` game objects, and to the `Maze` game object's child game objects.


### Directory Structure 
- The Unity project is the child directory of the repository and named according to the associated lesson.
- The project uses a recommended version of Unity and Google VR sdk.
- The Unity project is 'cleaned' and includes my 'Assets', Build', 'ProjectSettings', 'Screenshots', and 'UnityPackageManager' folders, along with the README.md file.
- The The README file includes a description of the Maze project, the name of the main scene (Maze) that will be loaded first, along with the Unity and GVR SDK versions used for the project.
- It also includes the target deployment platform (Android and Windows PC).
- The Unity project does not include the 'Temp, 'Library', and 'Packages' folders, as they have been deleted.


### Related Repositories
- [VR Software Development - Creating Scripts](https://github.com/udacity/VR-Software-Development_Creating-Scripts/releases)
- [VR Software Development - Controlling Objects Using Code](https://github.com/udacity/VR-Software-Development_Controlling-Objects-Using-Code/releases)
- [VR Software Development - VR Interaction](https://github.com/udacity/VR-Software-Development_VR-Interaction/releases)
- [VR Software Development - Programming Animations](https://github.com/udacity/VR-Software-Development_Programming-Animations/releases)
- [VR Software Development - Physics and Audio](https://github.com/udacity/VR-Software-Development_Physics-and-Audio/releases)
- [VR Software Development - Advanced VR Scripting](https://github.com/udacity/VR-Software-Development_Advanced-VR-Scripting/releases)
- VR Software Development - A Maze


### Description of the Maze Project 
### Gameplay Functionality
Maze: The Maze is designed such that the user cannot identify a path to the Key from the start position.
Waypoints: Waypoints are placed throughout the Maze such that the users can navigate from the start position to all the game objects that can be interacted with; to collect the seven Gold Coins, access the Key, open the Door, and click on the SignPost.
Coins: There are Seven Gold Coins in the Maze for the users to collect during the game.
Key: There is a only one Key in the Maze that the users must search for and gain access to, in order to unlock the Door of the temple. .
Door: The Door prevents the users from navigating to the SignPost until it has been opened.
SignPost: The SignPost cannot be seen or interacted with before the Door is opened.

### Coin Behavior
Audio: A sound effect is played at the location of that Coin when it is clicked.
Collection: When a Coin is clicked, it is removed from the scene hierarchy, as it is collected by the users during the game.

### Key Behavior
Audio: A sound effect is played at the location of the Key when it is clicked.
Collection: When the Key is clicked, it is removed from the scene hierarchy, as it is accessed by the users to unlock the Door during the game.
Unlocking the Door: The Door becomes unlocked when the Key is clicked.

### Door Behaviour
Initial state: The Door is locked and closed when the game starts.
Locked state: The Door cannot be opened when it is locked.
Unlocking: The Door becomes unlocked only by clicking the Key.
Unlocked state: The Door starts opening when the Door is clicked and unlocked.
Audio: A sound effect is played at the location of the Door when the Door starts opening.
Animation: The Door is animated to an open position by code only, without using animation and animator controller.

### SignPost Behaviour
The Maze scene resets to its initial state when the SignPost is clicked, so that the game can be restarted/played again.


### My Reflection and Conclusion (Change This*)
- It took almost a week for me to complete the "Maze" project, as I worked very closely on it to ensure that it meets all the project specifications.
- I love working in Unity 3D, as I have keen interest to learn using it inside out. Therefore, I liked almost everything about the project.
- I really enjoy the fact that I was able to design and develop the "Maze" project from scratch, along with learning the ropes of coding using C#.

- I really enjoyed developing the 'Maze App' with most of the optional features and learned a lot during the process. 
- I am proud of my Final Project Output.

### References 
1. Student Hub. (n.d.). Retrieved May 10, 2019, from https://study-hall.udacity.com/rooms/community:nd105:673753-project-230?contextType=room
2. Technologies, U. (n.d.). Scripting. Retrieved May 10, 2019, from https://docs.unity3d.com/2017.4/Documentation/Manual/ScriptingSection.html


Kind Regards,
Sujatha.