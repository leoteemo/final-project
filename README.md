# Final Project!

## Final submission (due 12/5)

https://www.youtube.com/watch?v=B9qcNq_mkDs
Video is also in the github directory. 
You can run the program in the build folder. 
The project file is too large and github gives errors when pushing. 

![](final0.png)

Post mortem: How did your project go overall? My project went pretty well overall. I learned a lot of things about procedural map and making creative works in unity.
Did you accomplish your goals? I did accomplish my goals. The end product as we see in the demo, the end product is very close to the map that minecraft dungeon has in the 2d view.This is what I was looking to achieve. 
Did you have to pivot? I didn't have to pivot much. I am looking to put a player in for the future work.

## Project planning: Design Doc (due 11/8)
Before submitting your first milestone, _you must get your project idea and scope approved by Rachel, Adam or a TA._


### Design Doc
Group Size = 1

#### Introduction
- I played some games where I have to walk through some cave or dungeon terrains. I think they are cool and fits with some of the ideas that we have been learning in class. And in the class the professor said we could do a game level, so I think a procedurally generated cave would be fun to do.  

#### Goal
- Design a dungeon game level and make a playable character to move through it


#### Inspiration/reference:
- Some references that I will look into:
https://www.redblobgames.com/x/1652-voronoi-moba-mapgen/
https://www.redblobgames.com/x/1939-planetary-dungeon/
https://simblob.blogspot.com/search/label/maps

-Some inspiration from other games, Pokemon Let's Go, and Minecraft Dungeon: 
![](art/Picture1.jpg)

![](art/Picture2.jpg)

![](art/Picture3.jpg)


#### Specification:
- A game level, it would be a dungeon or cave looking map
- It has specific paths inside the dungeon that the player can walk on
- A playable character to move through this map
- Cube based like, minecraft

#### Techniques:
- Software: Unity
- Techniques: BFS, Finding Shortest Path, learn from other Procedural Map Generators

#### Design:
- The idea is that map will likely be generated at once. Thus it would be maps -> add on features -> playable character, designed in this order.  

#### Timeline:
- Milestone 1: Determine which algorithms I will use, possibly create a base prototype of map.
- Milestone 2: Create a working map, add tools or options for variety.
- Milestone 3: Create a playable player that can move through the map.
- Final: Give the map and player textures, fine tune and make things look complete.

Submit your Design doc as usual via pull request against this repository.
## Milestone 1: Implementation part 1 (due 11/15)

In the first week, I was doing some research on how other generation maps work. I read some articles on redblobgames.

## Milestone 3: Implementation part 2 (due 11/27)

In this week, I got started with my dungeon generator. I haven't been able to create the entire dungeons. However, I have find ways to place random blocks and form an island. Here is an early work image. 
![](final_image/pic0.png)

## Topic Suggestions

### Create a generator in Houdini

### A CLASSIC 4K DEMO
- In the spirit of the demo scene, create an animation that fits into a 4k executable that runs in real-time. Feel free to take inspiration from the many existing demos. Focus on efficiency and elegance in your implementation.
- Example: 
  - [cdak by Quite & orange](https://www.youtube.com/watch?v=RCh3Q08HMfs&list=PLA5E2FF8E143DA58C)

### A RE-IMPLEMENTATION
- Take an academic paper or other pre-existing project and implement it, or a portion of it.
- Examples:
  - [2D Wavefunction Collapse Pokémon Town](https://gurtd.github.io/566-final-project/)
  - [3D Wavefunction Collapse Dungeon Generator](https://github.com/whaoran0718/3dDungeonGeneration)
  - [Reaction Diffusion](https://github.com/charlesliwang/Reaction-Diffusion)
  - [WebGL Erosion](https://github.com/LanLou123/Webgl-Erosion)
  - [Particle Waterfall](https://github.com/chloele33/particle-waterfall)
  - [Voxelized Bread](https://github.com/ChiantiYZY/566-final)

### A FORGERY
Taking inspiration from a particular natural phenomenon or distinctive set of visuals, implement a detailed, procedural recreation of that aesthetic. This includes modeling, texturing and object placement within your scene. Does not need to be real-time. Focus on detail and visual accuracy in your implementation.
- Examples:
  - [The Shrines](https://github.com/byumjin/The-Shrines)
  - [Watercolor Shader](https://github.com/gracelgilbert/watercolor-stylization)
  - [Sunset Beach](https://github.com/HanmingZhang/homework-final)
  - [Sky Whales](https://github.com/WanruZhao/CIS566FinalProject)
  - [Snail](https://www.shadertoy.com/view/ld3Gz2)
  - [Journey](https://www.shadertoy.com/view/ldlcRf)
  - [Big Hero 6 Wormhole](https://2.bp.blogspot.com/-R-6AN2cWjwg/VTyIzIQSQfI/AAAAAAAABLA/GC0yzzz4wHw/s1600/big-hero-6-disneyscreencaps.com-10092.jpg)

### A GAME LEVEL
- Like generations of game makers before us, create a game which generates an navigable environment (eg. a roguelike dungeon, platforms) and some sort of goal or conflict (eg. enemy agents to avoid or items to collect). Aim to create an experience that will challenge players and vary noticeably in different playthroughs, whether that means procedural dungeon generation, careful resource management or an interesting AI model. Focus on designing a system that is capable of generating complex challenges and goals.
- Examples:
  - [Rhythm-based Mario Platformer](https://github.com/sgalban/platformer-gen-2D)
  - [Pokémon Ice Puzzle Generator](https://github.com/jwang5675/Ice-Puzzle-Generator)
  - [Abstract Exploratory Game](https://github.com/MauKMu/procedural-final-project)
  - [Tiny Wings](https://github.com/irovira/TinyWings)
  - Spore
  - Dwarf Fortress
  - Minecraft
  - Rogue

### AN ANIMATED ENVIRONMENT / MUSIC VISUALIZER
- Create an environment full of interactive procedural animation. The goal of this project is to create an environment that feels responsive and alive. Whether or not animations are musically-driven, sound should be an important component. Focus on user interactions, motion design and experimental interfaces.
- Examples:
  - [The Darkside](https://github.com/morganherrmann/thedarkside)
  - [Music Visualizer](https://yuruwang.github.io/MusicVisualizer/)
  - [Abstract Mesh Animation](https://github.com/mgriley/cis566_finalproj)
  - [Panoramical](https://www.youtube.com/watch?v=gBTTMNFXHTk)
  - [Bound](https://www.youtube.com/watch?v=aE37l6RvF-c)

### YOUR OWN PROPOSAL
- You are of course welcome to propose your own topic . Regardless of what you choose, you and your team must research your topic and relevant techniques and come up with a detailed plan of execution. You will meet with some subset of the procedural staff before starting implementation for approval.
