Hello, I'm Ville Lindblad. I'm an experienced programmer capable of solving problems and building games.
I have several years of professional experience using the **Unity** engine and **C#**.
Other tech I have experience with includes **Git**, **Python**, **Bash**, **Java**, **C++**, **JavaScript**, **HTML** and **CSS**.
I'm also a fast learner of new technologies.

I strive for simple, easy to understand and maintainable code.
I make sure the projects I work on stay organized and follow best practices.
I try to reduce technical debt when I can.
I like helping others to solve issues, avoid blockers and improve workflows.

Some things I have worked on (Check the projects for more!):
- Gameplay features and tech
- UI features and tech
- Integrating SDK's, backend services and analytics to mobile apps
- Automation, tools and build scripts to speed up development
- CI/CD pipelines, setting up self hosted mac and windows runners
- Publishing apps to Google Play and App Store and making them pass the review
- Authoring technical design documents and onboarding guides
- Mentoring juniors and conducting code reviews
- Optimization (profiling, memory usage, build size, eliminating GC allocations, overdraw, draw calls)

My professional experience is in mobile games but I have interest in developing also for PC, VR or console.
I also have some interest in graphics programming, having done some shaders, procedural terrain, textures and mesh generation.

- [LinkedIn](https://www.linkedin.com/in/ville-lindblad/)
- [GitHub](https://github.com/villevli)

# Projects

## Dibs 🗺️
Playstack - iOS / Android

<a href="img/dibs.png"><img src="img/dibs.png" width="35%" style="float:right; padding-left:20px"></a>

Gamified engagement with brands in a location-based live-service game. Includes multiplayer and AR features.

- I worked as a Unity developer and C# programmer
- Collaborated in an agile team. Wrote documentation and tech design (Git, Jira, Confluence)
- Character movement on a tile based world map (Mapbox SDK) based on GPS location
- Character customization (assetbundles, scriptable objects, import tools for artists)
- Localization system (Google Sheets > download CSV and commmit to git)
- Social login (Firebase auth, Google, Apple, email)
- Seasonal events (remote configuration, assetbundles, scriptable objects)
- Gifting (UI, client side logic, helped design the backend api and MongoDB model)
- Utility code (GraphQL API pipeline, UI navigation stack, image downloader/cache, global event system, etc.)
- CI/CD pipeline in GitLab to test, build and upload the app and assetbundles for App Store and Google Play (yaml, git, bash, python, xcode, aws cli, self hosted runners)
- Runtime tools (Debug menu, console, inspector)
- Editor tools and workflow optimization (scene, user, server selector, etc.)
- Testing (unit tests, mockup backend for UI testing)
- Optimization of runtime performance, memory usage and build size
- Publishing (comply with Google Play and App Store requirements)
- SDK integrations (Firebase Auth, Crashlytics, Analytics, Google sign in, Sign in with Apple, OneSignal, Branch.io)
- Analytics (designed and implemented client events)

[View details about Dibs](projects/dibs.md)

<br style="clear:both">


## Glass Art 🎨
Playstack - iOS / Android

<a href="img/glassart-cut.png"><img src="img/glassart-cut.png" width="35%"  style="float:right; padding-left:20px"></a>

Artful hyper casual game where you can build stained glass artworks by cutting and combining pieces.

- I worked as a Unity developer and C# programmer
- Algorithm for cutting a 2d mesh / polygon by drawing a line and generating the mesh from the list of edge points
- Firebase Storage and Dynamic Links to share the artworks you create
- Optimized sprites and guided the artist

<br style="clear:both">


## Taxi Dash 🚖
Playstack - iOS / Android

<a href="img/taxi-dash.png"><img src="img/taxi-dash.png" width="35%" style="float:right; padding-left:20px"></a>

Infinite runner where you drive a taxi, pick up and drop off passengers and plow through obstacles.

- I worked as a Unity developer and C# programmer
- Floating origin (camera stays still, world moves) to enable infinite run without floating point issues
- "Air resistance" custom physics logic to make physics look correct
- Online leaderboard using Firebase Realtime Database

<br style="clear:both">


## Cubes ⛰️
Personal project - PC / Android

<a href="img/cubes-cave.png"><img src="img/cubes-cave.png" width="45%" style="float:right; padding-left:20px"></a>

A tech demo inspired by Minecraft.

Source code: [villevli/cubes-unity](https://github.com/villevli/cubes-unity)

- Procedural terrain made from blocks. Includes noise caves under ground
- Generated in 16x16x16 chunks
- Hidden surfaces are culled to make rendering very fast even with larger view distances
- Using the burst compiler for all heavy calculations to make it many times faster
- Using background threads to make traversal in the world smooth even when loading or generating chunks
- Procedural generation with perlin noises is done in a GPU compute shader. 4096 chunks (16.7 million blocks) generates in under 20 milliseconds on RTX 3070
- Raycasting to find block surfaces
- Break and place blocks

<br style="clear:both">


## Procedural planet shader 🌍
Personal project

<a href="img/procedural-planet.png"><img src="img/procedural-planet.png" width="45%" style="float:right; padding-left:20px"></a>

- Shader graph
- 3d fractal perlin noise
- Adapted from a tutorial video for Blender

<br style="clear:both">


## Defender arcade game prototype 👾
Personal project - PC / Android

Simple clone of the retro game Defender in Unity.

Source code: [villevli/vl-defender-arcade](https://github.com/villevli/vl-defender-arcade)

- Seamlessly looping game area
- Parallax background
- Minimap
- Keyboard, mouse, gamepad and touch controls using the new Input System


## 2d physics engine in JavaScript 🏀
Personal project. Started from a game physics course at Metropolia University of Applied Sciences

Try it here: [Physics2D](https://villevli.github.io/physics2d-js/)

Source code: [villevli/physics2d-js](https://github.com/villevli/physics2d-js)

- Physics simulation that calculates collisions and forces between polygons
- Uses no libraries, only the canvas api and JavaScript in browsers


## Mirror for firebase packages in Unity
Personal project. Need for this arised when working on Dibs at Playstack

[google-unity-packages-mirror · GitLab](https://gitlab.com/google-unity-packages-mirror)

- Built to avoid having to commit the large firebase core package into a project and instead download it from a git repository via the Unity package manager
- Runs a scheduled CI/CD pipeline every night to download the .tgz unity packages published by google and pushes them to gitlab giving each version a tag so it can be used via the Unity package manager


## Soludus ☀️
Metropolia Game Studio - SteamVR

<a href="img/soludus-vr.png"><img src="img/soludus-vr.png" width="45%" style="float:right; padding-left:20px"></a>

Virtual reality game teaching about the use of renewable energy.

Source code: [Soludus/Soludus2Enercity](https://github.com/Soludus/Soludus2Enercity)

- I worked as the sole programmer in Unity
- VR game controls using the SteamVR plugin
- Drag to move around game map using controls similar to Google Earth VR
- Day night cycle that continually adjusts light settings using curves and gradients. I designed this to fit the needs of our artist
- Integrated dynamically changing FMOD sounds from our sounds guy into the game logic

<br style="clear:both">


## Capitalistica 💰
Metropolia Game Studio - Android

<a href="img/capitalistica.png"><img src="img/capitalistica.png" width="35%" style="float:right; padding-left:20px"></a>

Mobile game teaching maths and financial management.

- I worked as a Unity developer and C# programmer

<br style="clear:both">


## Siimes 🌳
Metropolia Game Studio - WebGL

<a href="img/siimes.png"><img src="img/siimes.png" width="35%" style="float:right; padding-left:20px"></a>

Social game for use in elementary schools. Works in browsers using WebGL.

- I worked as a Unity developer and C# programmer

<br style="clear:both">


## Procedural voxel terrain ⛰️
My Bachelor's thesis at Metropolia University of Applied Sciences

Thesis (finnish): [Vokselimaaston käsittely ja renderointi](https://www.theseus.fi/handle/10024/349339)

- A tech demo with procedural generation of terrain and chunk based meshing to create an "infinite" world
- Multiple layers of perlin noise to create a signed distance field resembling mountains
- Marching cubes for generating a mesh from the signed distance field
- Multithreaded chunk loading and generation
- Realtime terrain modification using boolean operations on the distance field

<br>
<a href="img/voxel-terrain2.png"><img src="img/voxel-terrain2.png" height="300px" style="margin-left:1.5em"></a>


## Arkanoid 2016 🎮
Personal project at Metropolia University of Applied Sciences - PC / Android

A clone of the retro game Breakout/Arkanoid in the Unity game engine.

- Includes a level editor and leaderboard


## Nox Daemonica 🕸️
Team project at Metropolia University of Applied Sciences - PC

- A small 1-4 player LAN co-op action RPG dungeon
- Implemented using the Photon Unity Networking library


## Fleet Commander 🚀
Team project at Metropolia University of Applied Sciences - PC

<a href="img/fleetcommander.png"><img src="img/fleetcommander.png" width="45%" style="float:right; padding-left:20px"></a>

- A space battle simulator where you build your fleet and watch a simulated battle in 3d space
- Ships have "AI" steering and attack routines

<br style="clear:both">


## Space Incident 🌌
Team project at Metropolia University of Applied Sciences - PC

<a href="img/spaceincident-procedural-corridors.png"><img src="img/spaceincident-procedural-corridors.png" width="45%" style="float:right; padding-left:20px"></a>

- A point and click graphic adventure game where you solve a mystery in a space station
- Includes procedurally generated corridors

<br style="clear:both">


## Chess AI in C++ ♟️
Pair project at Metropolia University of Applied Sciences

- Pair programming for an AI chess competition
- Alpha-beta algorithm
- Optimizations like storing the 8x8 chessboard states in 64 bit integer bitmasks
- Our program won the competition 🏆


## Intro to OpenGL API in C++ 🐇
Graphics programming course at Metropolia University of Applied Sciences

- Drawing a mesh with a texture and shader using the OpenGL API


## Embedded ventilation fan controller in C++ 🔌
Pair project at Metropolia University of Applied Sciences

- Control the speed of a ventilation fan
- Fan is connected to an ABB frequency converter
- Converter is controlled using Modbus protocol
- Two operating modes: Manual and Automatic
- LCD user interface
- Arduino, LPCXpresso, UART, I2C


## Procedural voxel terrain with LOD ⛰️
Personal project

- 3d fractal noise
- Marching cubes meshing
- Chunk loading to create "infinite" world
- Octree loading for level of detail based on distance to camera


## Post Effect Mask
Personal project I started when a question at Unity Forums got my interest

[Applying image effects to specific objects - Unity discussions](https://discussions.unity.com/t/applying-image-effects-to-specific-objects/666124/12)

- Mask any camera post effects. Use e.g. to apply a post effect only to defined objects
- Draws an alpha mask and uses alpha blending to blend the processed image on top of the unprocessed image


## Portal mechanics
Personal project

- Created a seamless portal between any 2 points in the 3d world (like in the game Portal)
- Used cameras, shaders, render texture and stencil buffer
- Teleports any objects passing through and keeping the relative orientation and velocity
