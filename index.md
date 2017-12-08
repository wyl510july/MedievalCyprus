## Welcome to Medieval Cyprus



### User Overview

-**Interface**: In this game, the user acts as the primary storyteller. You will use the joystick on the right-hand controller to walk through the scene and interact with NPCs. Pointing to an NPC and hitting the A button will begin the conversation.

-**Purpose**: Inspired by the dynamic nature stories as they were told in medieval times, this game allows the user to experience how stories change and adapt according to their audience within a realistic and historically accurate setting. The stories that are told in this game are based off of One Thousand and One Nights, Floris and Blanchefleur, the Story of Silence, Yde et Olive (also known as Huon de Bordeaux), the story of L'Escoufle, as well as our own interpretations. These five stories are believed to all be variations of one story, and show how time and audience have influenced their final versions.
In this game, the user tells stories to various other people, gaining storytelling experience and learning preferences about each individual. After the user has successfully told stories to several villagers, the user gains access to the King’s palace and has the ability to finally tell the King a story in hopes of impressing the King.

-**Language**: This game was developed in Unity with C# as its primary programming language and the stories are written in English. 


### Read Me

-**Installation**: Download the Oculus software and create and Oculus account, following any on screen instructions for [setup](https://www.oculus.com/setup/).

-**Development Environment**: Download the [Unity game engine](https://store.unity.com/download?ref=personal) for development and follow any onscreen instructions for setup. This game was developed using Unity 2017.2.

-**Hardware**: This game is compatible with the Oculus Rift system, which consists of a headset and two [Rift](https://www.oculus.com/rift/) controllers.

-**Software**: This game did not require additional software and was built completely using Unity, scripted in Unity’s Monodevelop in C#, and assets were taken from those available in the Unity Asset Store.

-**Warnings**: Developers should consider the large size of assets and overall build that is needed for this project due to the high-poly nature of the assets used to create a realistic scene. Developers should check that they have adequate space available on their hard drive as well as appropriate computing power and time to download or commit revisions. 
Users should consider some mild adverse effects of playing this game, including dizziness or fatigue. If any discomfort is experienced, users should consider limiting the amount of time they spend within the Medieval Cyprus game.


### Future developer

-**Environment**
Our recommendation for environment development is to modularize each subscene and build them one at a time. For our development, we first developed the marketplace, then followed with the village and finally created the city and the king’s court. Our focus for the environment was the create a realistic scene rather than create an interactive environment, so there is limited movement of trees or building accessories. 
Future development of the environment could include additional subscenes such as a seaside port with ships, the interior of a home, or the caravan of the storyteller. Low-poly or cartoonish assets should be avoided to maintain the detailed feel of the environment.

-**NPCs**
The role of NPCs in this current version is to act as the recipient of the story. Each NPC is associated with both an occupation and a story preference, which can be explored in the NPCController.cs file as well as associated plain text files that are named NPC[type].txt. NPC movement is controlled using a basic premade script for natural standing movement. 
Future development of NPCs could include a greater number and variety of characters. While this version of the game primarily drew premade characters from the asset store due to a need to find characters that were historically accurate, there is certainly the potential to create your own characters. Additionally, NPCs are currently stationary so that the user may approach the NPC to tell a story, future iterations could allow NPCs to move from one subscene to another to create a more realistic depiction of daily life in medieval times. 

-**Controller**
Hardware control is primarily implemented in the PlayerControl.cs. The VR_HandTouch method reads hardware interaction and triggers the dialogue for NPC interaction. Currently, a pointer extends from the right-hand to show the intended target NPC, and a collision with the NPC begins the interaction. 
The text engine is supported in the NPCController.cs file. This file interprets all associated text files that contain each story as well as NPC preferences. This code was intentionally written to be modular and easy to read by outsiders, and operates by working through greetings, storytelling, and then evaluation and goodbye. Developers should play the executable game prior to exploring the code in order to understand the text engine.


### Mentor section 
Our mentor, Professor **Lynn Ramey**, proposed a storytelling project that realistically showcased the diversity of people and their stories in Medieval Cyprus. Her introduction of the project can be found [here](https://drive.google.com/open?id=1XcTmBbJ3Bl49RQn7U-xF8Aqv7r2X4pUD) .

Through this game, we not only created a way to understand how stories evolve, but we also experienced storytelling interpretation on our own. We initially began the project with three text sources, A Thousand and One Nights, Floris and Blanchefleur, and the Story of Silence. In order to portray a storyteller’s decision making, we chose to give users the option to tell their story line by line. We rewrote each story in parallel; we changed character names of protagonists to all be the same between each story, and chose to display the stories simultaneously line by line. To add a layer of complexity, we asked Professor Ramey for additional sources that are also believed to have stemmed from the same historic background and received two more stories, Yde et Olive and the story of L'Escoufle. We also created our own interpretation of the story, which is integrated into the game as the “Invented” story. 

This game now tells six stories side by side and showcases how stories that have diverged throughout history can still be woven back together.

### Video walkthrough

### Playable build
