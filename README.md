# GDIM32 In Class Activities
## Week1

### Activity1

1,Make sure you understand all code you have made.
2,Attend office hour.
3,listen the suggestions of play test report.

### Activity2

1,10
2,2
3,When game begin running, the console will print "hello world" again and again.
4,MonoBehavior.
5,x=10 is passed into PrintMassage and then x+10, the console print x=10.
6,the parameters, the code means that 0+10
7,the transform of Transform.Translate was wrong.
8,_playerTransform.Translate

### Activity3

[MG1 breakdown Google doc](https://docs.google.com/document/d/1RY8G4u76Aeqqu-rppdIJhAqMhHotRh3U2m445UlfjAs/edit?tab=t.0)

## Week2

### Activity1

![WechatIMG475](https://github.com/user-attachments/assets/95794091-a13d-450f-9f7f-6122641291d1)
### Activity2
I mainly constructed the general scene and added the corresponding components to each project. Then, I wrote the coding for the basic movement function of the player.
[MG2 in class activity](https://github.com/UCI-GDIM32-W25/mg2-JingyiBi/commit/51315f98f39b6425bd78173d1d834e28fdb9850e)
## Week3
### Activity0-2
Tina Meng  Jingyi Bi
### Activity3
![5071768962315_ pic](https://github.com/user-attachments/assets/5cd3a9a4-c50e-4fb1-bfed-a1e238ab084a)

## Week4
### Activity 0
Peiyi Xiong
### Activity 1
When the game runs, all extra Locator objects are automatically destroyed, leaving only one instance in the scene. This happens because of the Singleton logic in the Awake method: the script checks if a static Instance already exists, and if it does, it calls Destroy(gameObject) on the duplicate to ensure there is only one central "source of truth" for the pigeon reference.
### Acitivity2

![5221769568698_ pic](https://github.com/user-attachments/assets/d8d1c147-be13-4bfa-be68-51c6b9dd5bda)

### Acitivity 3
[MG4 in class activity](https://github.com/JingyiBi/HW4/commit/945a440466c5a2ca0fd81a22153175d871a617b4)
Imported assets, completed game screen setup, created the game folder, and imported GitHub materials.

## Week6
### Activity1
Using .gitignore to filter redundant files prevents code overwriting during simultaneous UI and singleton logic development by multiple contributors, while providing a "do-over" for core system iterations through undo and merge functions. The Gizmos tool visualizes complex spatial logic, enabling real-time debugging of NPC interaction ranges, delivery detection zones, and visual paths guiding customers to their homes within scenes—ensuring precise spatial experiences for players in Forest Town. Breakpoint debugging proves invaluable for optimizing MVC architecture and handling polymorphic logic. By setting breakpoints during DeliveryManager state transitions or NPC subclass interactions, we precisely track order flow and tip calculation values, efficiently pinpointing and resolving logical flaws in the delivery process.
### Activity2 
JingyiBi, Peiyi Xiong, Ruixuan Pan
[FP Draft in class](https://docs.google.com/document/d/1xBZf-TNesHDRlNGUnQIIlStqfWb3MOsQMGyXhkQuQ5s/edit?tab=t.0#heading=h.wm54rak5tgph)

## Week8 
### Activity1
Rendering & Playtesting Notes
Rendering Pipelines
A sequence of instructions for how everything in the game is drawn to the screen.
Technical Details: Pipelines are written in CPU code and coordinate resources between the CPU and GPU.
Built-in Pipeline: Unity's default, general-purpose pipeline with limited customization.
URP: Optimized for a wide range of platforms and easy to customize.
HDRP: Used for high-fidelity, cutting-edge graphics on high-end platforms.
Asset Compatibility: Shaders and materials must be made for the specific pipeline you are using; they are not universally compatible
### Activity2
Attendance: JingyiBi, Peiyi Xiong, Ruixuan Pan
### Activity3
The scene is very beautiful and the characters have distinct features. The UI can be further improved, and some of the interaction codes may also be enhanced. The overall game has taken shape and can now incorporate background music and sound effects (not have yet).
### Activity4
Add collision bodies to all objects to prevent model clashing.
Working with Mia to find UI bugs.
### Activity5
[Commit](https://github.com/JingyiBi/GDIM32-Final-AAA/commits/main/)
I added the required objects to the original scene, identified a UI bug, and then sourced the game's BGM and music.
