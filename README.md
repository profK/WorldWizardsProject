# WorldWizardsProject

![Alt Text](images/WWimage.png)

WorldWizards open source world builder

The proposed project is to build a new world building kit that overcomes all of these limitations.  It will be built a modern 3D Game engine (Unity3D) both lowering the cost of creation as well as leveraging the ongoing development of the Unity3D team to keep its visual content up to date.   
This project would be built in stages as a series of sub projects:
1.	World Builder
Goal is a functional true 3D tile based world assembly system built for VR environments.  Tiles would be organized in matching tile-sets that are run-time loaded and arranged on a 3D grid.  Level change tiles (stairs, pits, elevators, etc) would be implemented as filling multiple grid spaces.  Tiles would have enough connectivity information to allow for auto-assembly (just like most 2D grid systems), and carry their own collision and navigation information that can be stitched together at run-time.

Objects will be place-able and movable on tiles at run-time.  Doors would be listed in separate “door sets” and door anchor points baked into the tiles.  Door motion will be controllable through scripting hooks.

2.	Creature Interface
Goal is to enable both humanoid and non-humanoid creatures to be placed in the environment.  These creatures will have a combination of a standard action interface (move to, pick up, mele attack, etc) and additional creature specific commands that they will advertise into the editing environment.

3.	PC Creator
Goal is a flexible modern parameterized character avatar creator that can be used to create customized humanoid characters wearing changeable clothes.  PCs will support the same creature interface as NPCs do, with a PC control layer ontop.

4.	Inventory Manager
Goal is the ability for PCs and NPCs to pick up, drop and chose items to use or store.  PCs will get an inventory UI, NPCS will be code driven by eventual AI.

5.	Default Combat System
A game combat system will be chosen and implemented in a plug-replaceable fashion.

6.	Server System
A remote server will be implemented capable of supporting large numbers of players with some reasonable modicum of game state security.

From here many individual projects open up using the platform as a base
.
Deployment and Future Work
Just like Neverwinter Nights I see this becoming both a platform for teaching and research.  The codebase and assets will be open—sourced to encourage third party development participation.
Once the base system is completed there is an almost unlimited scope of experimental world simulation systems that could be built on top.   Some areas I see of potential future work include AI/artificial life experimentation, immersive user interface and control research, and experimental game rule systems.  
