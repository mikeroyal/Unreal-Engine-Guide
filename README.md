<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/162537763-308611ef-a619-4fcd-99bf-bfe328c50f27.png">
  <br />
  Unreal Engine Guide
</h1>

#### A guide covering Unreal Engine including the applications, libraries and tools that will make you a better and more efficient Unreal Engine developer.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/162537753-7c37a7a9-6513-49a6-848e-75784119a587.png">
  <br />
</p>

# Table of Contents

1. [Getting Started with Unreal Engine](https://github.com/mikeroyal/Unreal-Engine-Guide#getting-started-with-unreal-engine)

    - [Unreal Engine Tools](https://github.com/mikeroyal/Unreal-Engine-Guide#unreal-engine-tools)

    - [Unreal Engine Learning Resources](https://github.com/mikeroyal/Unreal-Engine-Guide#unreal-engine-learning-resources)
    
    - [Xbox](https://github.com/mikeroyal/Unreal-Engine-Guide#xbox-development)
      
    - [PlayStation](https://github.com/mikeroyal/Unreal-Engine-Guide#playstation-development)
      
    - [Nintendo Switch](https://github.com/mikeroyal/Unreal-Engine-Guide#nintendo-switch-development)
      
    - [Steam Deck](https://github.com/mikeroyal/Unreal-Engine-Guide#steam-deck-development)

2. [VS Code Development](https://github.com/mikeroyal/Unreal-Engine-Guide#vs-code-development)

    - [VS Code Extensions for Developer Productivity](https://github.com/mikeroyal/Unreal-Engine-Guide#VS-Code-Extensions-for-Developer-Productivity)

3. [Xcode Development](https://github.com/mikeroyal/Unreal-Engine-Guide#xcode-development)

4. [Game Development](https://github.com/mikeroyal/Unreal-Engine-Guide#game-development)

5. [Augmented Reality (AR) & Virtual Reality (VR)](https://github.com/mikeroyal/Unreal-Engine-Guide#augmented-reality-ar--virtual-reality-vr)

6. [Vulkan Development](https://github.com/mikeroyal/Unreal-Engine-Guide#vulkan-development)

7. [Metal Development](https://github.com/mikeroyal/Unreal-Engine-Guide#metal-development)

8. [DirectX Development](https://github.com/mikeroyal/Unreal-Engine-Guide#directx-development)

9. [Computer Vision Development](https://github.com/mikeroyal/Unreal-Engine-Guide#computer-vision-development)

10. [Photogrammetry Development](https://github.com/mikeroyal/Unreal-Engine-Guide#photogrammetry-development)

11. [Geometric optics](https://github.com/mikeroyal/Unreal-Engine-Guide#Geometric-optics)

12. [Autodesk Development](https://github.com/mikeroyal/Unreal-Engine-Guide#autodesk-development)

13. [LiDAR Development](https://github.com/mikeroyal/Unreal-Engine-Guide#lidar-development)

14. [Linear Algebra](https://github.com/mikeroyal/Unreal-Engine-Guide#linear-algebra)

15. [Algorithms](https://github.com/mikeroyal/Unreal-Engine-Guide#algorithms)

16. [Machine Learning](https://github.com/mikeroyal/Unreal-Engine-Guide#machine-learning)

17. [Deep Learning](https://github.com/mikeroyal/Unreal-Engine-Guide#deep-learning)

18. [CUDA Development](https://github.com/mikeroyal/Unreal-Engine-Guide#cuda-development)

19. [MATLAB Development](https://github.com/mikeroyal/Unreal-Engine-Guide#matlab-development)

20. [C/C++ Development](https://github.com/mikeroyal/Unreal-Engine-Guide#cc-development)

21. [Python Development](https://github.com/mikeroyal/Unreal-Engine-Guide#python-development)

22. [Lua Development](https://github.com/mikeroyal/Unreal-Engine-Guide#lua-development)

23. [Networking](https://github.com/mikeroyal/Unreal-Engine-Guide#networking)

24. [Databases](https://github.com/mikeroyal/Unreal-Engine-Guide#databases)

# Getting Started with Unreal Engine
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

[Unreal Engine](https://www.unrealengine.com/unreal-engine-5) is a game engine developed by Epic Games with the world's most open and advanced real-time 3D creation tool. Continuously evolving to serve not only its original purpose as a state-of-the-art game engine, today it gives creators across industries the freedom and control to deliver cutting-edge content, interactive experiences, and immersive virtual worlds. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/162538256-a3390573-88b8-4925-a92e-70a56da951b3.png">
  <br />
  Unreal Engine 5 with Big City Sample Project
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/146693087-56cfbc91-3398-425c-90a1-6a2479ca3fce.png">
  <br />
</p>

 Unreal Engine Twinmotion. Source: [Unreal Engine](https://www.unrealengine.com/en-US/blog/twinmotion-2021-1-is-here)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/147710656-ea693faf-4ac2-450c-a416-b6cc63a9c524.png">
  <br />
  Unreal Engine Marketplace
</p>

## Unreal Engine Tools

[Blueprint Visual Scripting](https://docs.unrealengine.com/en-US/Engine/Blueprints/index.html) is a complete gameplay scripting system in Unreal Engine based on the concept of using a node-based interface to create gameplay elements from within Unreal Editor. As with many common scripting languages, it is used to define object-oriented (OO) classes or objects in the engine.

[Datasmith](https://www.unrealengine.com/en-US/datasmith) is a collection of tools and plugins that bring entire pre-constructed scenes and complex assets created in a variety of industry-standard design applications into Unreal Engine.

[Chaos Physics](https://docs.unrealengine.com/5.0/en-US/InteractiveExperiences/Physics/ChaosPhysics/Overview/) is a Beta feature that is the light-weight physics simulation solution used in Fortnite, and it includes the following major features.

   - RBAN (Rigid Body Animation Nodes)

   - Destruction

   - Cloth

   - Ragdoll

   - Vehicles

[Niagara VFX System](https://docs.unrealengine.com/5.0/en-US/RenderingAndGraphics/Niagara/) is one of two tools you can use to create and adjust visual effects (VFX) inside Unreal Engine 5 (UE5). Before Niagara, the primary way to create and edit visual effects in UE4 was to use [Cascade](https://docs.unrealengine.com/4.27/en-US/RenderingAndGraphics/ParticleSystems). It has many of the same of particle manipulation methods that Cascade offers, the way you interact and build visual effects with Niagara is vastly different.

[MetaHuman Creator](https://www.unrealengine.com/en-US/metahuman-creator) is a free cloud-based app that empowers anyone to create photorealistic digital humans, complete with hair and clothing, in minutes. MetaHumans come fully rigged and ready to animate in your Unreal Engine projects.

[Twinmotion](https://www.twinmotion.com/en-US) is a real-time 3D immersion software that produces high-quality images, panoramas and standard or 360° VR videos in seconds. Developed for architecture, construction, urban planning and landscaping professionals.

[Bridgew by Quixel](https://www.unrealengine.com/en-US/bridge) is a gateway to create a world of 3D content right inside the Unreal Engine. it includes Megascans—the world's largest library of AAA, cinema-quality assets based on real-world scan data.

[Lumen](https://docs.unrealengine.com/5.0/en-US/RenderingFeatures/Lumen/TechOverview/) is an Unreal Engine 5 feature that uses multiple ray tracing methods to solve Global Illumination and Reflections. Screen traces are done first, followed by a more reliable method. It uses Software Ray Tracing through Signed Distance Fields by default, but can achieve higher quality on supporting video cards when Hardware Ray Tracing is enabled.

[Nanite](https://docs.unrealengine.com/5.0/en-US/RenderingFeatures/Nanite/) is Unreal Engine 5's new virtualized geometry system which uses a new internal mesh format and rendering technology to render pixel scale detail and high object counts. It intelligently does work on only the detail that can be perceived and no more.

[Unreal Engine Marketplace](https://unrealengine.com/marketplace/en-US/store) is Unreal Engine's Store that has a library Of Textures, Models, Animations, Tutorials, and More for creating amazing 3D projects and games.

[UnrealBuildTool (UBT)](https://docs.unrealengine.com/5.0/en-US/ProductionPipelines/BuildTools/UnrealBuildTool) is a tool that manages the process of building UE4 source code across a variety of build configurations.

[UnrealHeaderTool (UHT)](https://docs.unrealengine.com/5.0/en-US/ProductionPipelines/BuildTools/UnrealHeaderTool) is a custom parsing and code-generation tool supporting the UObject system.

[AutomationTool](https://docs.unrealengine.com/4.27/en-US/ProductionPipelines/BuildTools/AutomationTool) is a generic system used to automate processes, including testing and building games.

[Proxy Geometry Tool](https://docs.unrealengine.com/5.0/en-US/TestingAndOptimization/ProxyGeoTool/) is a tool-set that was developed as a way to increase your Unreal Engine 4 (UE4) project's performance while keeping the visual quality of your project uneffected.

[Replay System](https://docs.unrealengine.com/5.0/en-US/TestingAndOptimization/ReplaySystem/) is a tool which can record gameplay for later viewing. This feature is available in all games, from live, multiplayer games played on dedicated servers, to single-player games, and even including Play-In-Editor sessions. At a high level, the Replay system works by using a DemoNetDriver to read data drawn from the built-in replication system, similar to how a NetDriver operates in a live, networked gameplay environment.

## Unreal Engine Learning Resources

[How to migrate your Unreal Engine 4 projects to Unreal Engine 5 Early Access quickly and smoothly](https://docs.unrealengine.com/5.0/en-US/MigrationGuide/)

[Unreal Engine 5 Documentation](https://docs.unrealengine.com/5.0/)

[Unreal Engine Forums](https://forums.unrealengine.com/)

### Developer Resources

 - [Setting Up Visual Studio for Unreal Engine](https://docs.unrealengine.com/en-us/Programming/Development/VisualStudioSetup)

 - [Unreal Engine Performance and Profiling](https://docs.unrealengine.com/5.0/en-US/TestingAndOptimization/PerformanceAndProfiling/)

 - [Unreal Engine C++ API Reference](https://docs.unrealengine.com/5.0/en-US/API/index.html)

 - [Unreal Engine Blueprint API Reference](https://docs.unrealengine.com/5.0/en-US/BlueprintAPI/index.html)

 - [Unreal Engine Python API Reference](https://docs.unrealengine.com/5.0/en-US/PythonAPI/index.html)
 
 - [Unreal Engine | NVIDIA Developer](https://developer.nvidia.com/unrealengine)

 - [Autodesk for Games](https://www.autodesk.com/campaigns/autodesk-for-games)

 - [Getting Started with DirectX 12 Ultimate](https://devblogs.microsoft.com/directx/directx-12-ultimate-getting-started-guide/)

 - [Getting Started with Vulkan](https://www.khronos.org/vulkan/)

 - [Getting Started with Apple Metal](https://developer.apple.com/metal/)

### Unreal Engine 5 Training & Online Courses 

 - [Unreal Online Learning](https://www.unrealengine.com/en-US/onlinelearning-courses) is a free learning platform that offers hands-on video courses and guided learning paths.
 
 - [Unreal Engine Authorized Training Program](https://www.unrealengine.com/en-US/training-partners) 

 - [Unreal Engine for education](https://www.unrealengine.com/en-US/education/)

 - [Unreal Engine Training & Simulation](https://www.unrealengine.com/en-US/industry/training-simulation)

 - [Unreal Engine 5 (UE5): Complete Beginners Course | Udemy](https://www.udemy.com/course/unreal-engine-course/)

 - [Unreal Engine 5 (UE5): Beginner's Course | Skillshare ](https://www.skillshare.com/classes/Unreal-Engine-5-UE5-The-Complete-Beginners-Course/1124349680)

 - [Unreal Engine 5 Crash Course with Blueprint by Beau Carnes](https://www.freecodecamp.org/news/unreal-engine-5-crash-course-with-blueprint/)

 - [Modeling a Castle in Unreal Engine 5 Tutorial](https://unf-vault.teachable.com/p/modeling-in-unreal-engine-5)

 - [Introduction to Blueprints in Unreal Engine 5 Tutorial](https://unf-vault.teachable.com/p/introduction-to-blueprints-for-beginners-in-unreal-engine-5)

 - [Learning Chaos Destruction in Unreal Engine 5 Tutorial](https://unf-vault.teachable.com/p/introduction-to-chaos-destruction-in-unreal-engine-5-for-beginners)

 - [Learning to create Landscapes in Unreal Engine 5 Tutorial](https://unf-vault.teachable.com/p/open-worlds-in-unreal-engine-5-complete-landscape-guide-for-beginners)

 - [Unreal Engine 5 Master Class Course](https://gamedev.gg/courses/unreal-master-class/)

 - [Game Design Online Courses from Udemy](https://www.udemy.com/courses/Design/Game-Design/)

 - [Game Design Online Courses from Skillshare](https://www.skillshare.com/browse/game-design)

 - [Learn Game Design with Online Courses and Classes from edX](https://www.edx.org/learn/game-design)

 - [Game Design Courses from Coursera](https://www.coursera.org/courses?query=game%20design)

 - [Game Design and Development Specialization Course from Coursera](https://www.coursera.org/specializations/game-development)
 
    
      
## Xbox Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

   **Quick links to Development Resources**

 - [Developing Games | Xbox and Windows](https://www.xbox.com/en-US/developers)
 
 - [Xbox Creators Program](https://www.xbox.com/en-US/developers/creators-program)
 
 - [ID@Xbox Program](https://www.xbox.com/en-US/developers/id)
 
 - [Xbox game development - Game Stack | Microsoft Docs](https://docs.microsoft.com/en-us/gaming/xbox/)
 
 - [Get Xbox Dev Mode - Microsoft Store](https://www.microsoft.com/en-us/p/xbox-dev-mode/9nljhzjrn0f4)
 
 - [Multi-platform development - Unreal Engine](https://www.unrealengine.com/en-US/features/multi-platform-development)
 
 - [Tips for developing console games (Xbox, PlayStation, Nintendo)](https://unity.com/how-to/develop-console-video-games-unity)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158109359-bef5dfd3-6c38-4cb0-8a48-ba2145c670fb.png">
  <br />
  Xbox Series X
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158109363-670074b5-4261-41ca-b02d-c1f99971db76.png">
  <br />
  Xbox Series S
</p>
      
## PlayStation Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

  **Quick links to Development Resources**

  - [PlayStation® Partners Program](https://partners.playstation.net/)
  
  - [PlayStation® Studios | PlayStation (US)](https://www.playstation.com/en-us/corporate/playstation-studios/)
  
  - [PlayStation Support](https://www.playstation.com/en-us/support/?smcid=pdc%3Aen-us%3Acorporate-playstation-and-the-environment-community%3Aprimary%20nav%3Amsg-support%3Asupport)
  
  - [PlayStation® Plus](https://www.playstation.com/en-us/ps-plus/?smcid=pdc%3Aen-us%3Acorporate-playstation-and-the-environment-community%3Aprimary%20nav%3Amsg-services%3Aps-plus)
  
  - [PS Now](https://www.playstation.com/en-us/ps-now/?smcid=pdc%3Aen-us%3Acorporate-playstation-and-the-environment-community%3Aprimary%20nav%3Amsg-services%3Aps-now)
  
  - [Multi-platform development - Unreal Engine](https://www.unrealengine.com/en-US/features/multi-platform-development)
  
  - [Creating games for Playstation | Unity](https://unity.com/solutions/playstation)
  
  - [Tips for developing console games (Xbox, PlayStation, Nintendo)](https://unity.com/how-to/develop-console-video-games-unity)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158109372-7e1dac0a-8df3-4867-a36e-7080e21014a7.png">
  <br />
  PlayStation 5
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158109375-f189109a-ccf6-47fc-a543-7d1831c3f970.png">
  <br />
  PlayStation 4
</p>

[PlayStation® VR Headset](https://www.playstation.com/en-us/ps-vr/) is a virtual reality headset developed by Sony Interactive Entertainment. It gives the user an amazing gaming experience with stunning High Dynamic Range visuals and up to 120fps, as two 1920 x 1080 OLED displays deliver a vast 100º field of view. PSVR is fully functional with the PlayStation 4™ and is forward compatible with the PlayStation 5™ home video game console. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/117720763-e9750000-b193-11eb-888a-e4bccd6c30eb.png">
<br />
</p>

PlayStation VR Headset. Source: [PlayStation](https://www.playstation.com/en-us/ps-vr/)

[PlayStation®VR2](https://www.playstation.com/en-us/ps-vr2/) is the next generation of virtual reality gaming by PlayStation. It gives the user an amazing gaming experience with new stunning 4K High Dynamic Range visuals and up to 120fps, as two 2000 x 2040 OLED displays deliver over four times the resolution generated by the original PlayStation®VR headset. A vast 110º field of view and a light, well-balanced Fresnel lens. The lens adjustment dial allows you to customize spacing between lenses to match your eye position for an optimal onscreen image. Along with ground-breaking new controllers and genre-defining games, all made possible by the power of PS5™.

<p align="center">
  <img alt="[psvr2" src="https://user-images.githubusercontent.com/45159366/156683318-6811ecf8-a8f2-4652-8872-f669cf38b459.png">
</p>

PlayStation VR 2 Headset. Source: [PlayStation](https://www.playstation.com/en-us/ps-vr2/)
      
## Nintendo Switch Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

  **Quick links to Development Resources**

  - [Nintendo Developer Portal](https://developer.nintendo.com/)
  
  - [Nintendo Developer Tools/ Middleware](https://developer.nintendo.com/tools)
  
  - [Multi-platform development - Unreal Engine](https://www.unrealengine.com/en-US/features/multi-platform-development)
  
  - [Tips for developing console games (Xbox, PlayStation, Nintendo)](https://unity.com/how-to/develop-console-video-games-unity)
  
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158109381-493efc29-3da2-4db8-b772-43cb3ca1f97a.png">
  <br />
  Nintendo Switch
</p>

## Steam Deck Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)
  
  **Quick links to Development Resources**

  - [Getting your game ready for Steam Deck](https://partner.steamgames.com/doc/steamdeck/recommendations)

  - [Developing for Steam Deck without a Dev-Kit](https://partner.steamgames.com/doc/steamdeck/testing)

  - [Steam Deck Developer Kits](https://partner.steamgames.com/doc/steamdeck/devkits)

  - [Steam Deck and Proton](https://partner.steamgames.com/doc/steamdeck/proton)

  - [Steam Deck Developer Forums](https://steamcommunity.com/groups/steamworks/discussions/27/)
  
  - [Multi-platform development - Unreal Engine](https://www.unrealengine.com/en-US/features/multi-platform-development)

  - [Tips for developing console games (Xbox, PlayStation, Nintendo)](https://unity.com/how-to/develop-console-video-games-unity)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158109383-57188374-6632-4ef2-ae58-1d66351b0fa8.png">
  <br />
  Steam Deck
</p>

[Steamworks](https://partner.steamgames.com/doc/home) is a free suite of tools available to any developer to use in their game or software on Steam and the Steam Deck.

[Steam Hardware GitLab Repo](https://gitlab.steamos.cloud/SteamDeck/hardware) is a repository that contains CAD files for the external shell (surface topology) of Steam Deck, under a Creative Commons license. This includes an STP model, STL model, and drawings (DWG) for reference.

[Dynamic Cloud Sync](https://steamcommunity.com/groups/steamworks/announcements/detail/3142949576401813670) is a tool that Steam will use  to automatically upload all modified save game data to the cloud prior to the device entering sleep mode. Users can then resume their game on any PC, laptop or other device. Steam will also automatically download any save game changes when users return to their Steam Deck and wake up the device.

[Steam Cloud](https://partner.steamgames.com/doc/features/cloud) is a tool that provides an easy and transparent remote file storage system for your game. Files specified in the Auto-Cloud configuration or written to disk (created, modified, deleted, etc.) using the Cloud API will automatically be replicated to the Steam servers after the game exits. If the user changes computers, the files are automatically downloaded to the new computer prior to the game launching. The game can then access the files by reading them through the Cloud API or reading them directly from disk as usual. Avoid machine specific configurations such as video settings.

[Gamescope](https://github.com/Plagman/gamescope) is a SteamOS session micro-compositing window manager formerly known as [steamcompmgr](https://github.com/ValveSoftware/steamos-compositor).

[AMD FidelityFX Super Resolution (FSR)](https://www.amd.com/en/technologies/radeon-software-fidelityfx) is an open source, high-quality solution for producing high resolution frames from lower resolution inputs. It enables “practical performance” for costly render operations, such as hardware ray tracing for the AMD RDNA™ and AMD RDNA™ 2 architectures.

[MangoHud](https://github.com/flightlessmango/MangoHud) is a Vulkan and OpenGL overlay for monitoring FPS, temperatures, CPU/GPU load and more.

[GOverlay](https://github.com/benjamimgois/goverlay) is an open source project aimed to create a Graphical UI to manage Vulkan/OpenGL overlays. It is still in early development.

[ReplaySorcery](https://github.com/matanui159/ReplaySorcery) is an open-source, instant-replay solution for Linux.

[Deck Verified](https://www.steamdeck.com/en/verified) is a program that reviews games in Steam's catalog verifying their compatibility with the Steam Deck. So when you visit your Library on Steam Deck, you’ll find a compatibility badge on each title, reflecting the kind of experience you can expect when playing each game on Steam Deck.

# VS Code Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/140833078-77973dcf-d3a6-421f-b6a7-b6e63fb1e97c.png">
  <br />
</p>

## Getting Started with VS Code

[Visual Studio Code](https://code.visualstudio.com) is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140832435-49e53589-e9e1-47fe-a1bd-d9800cfc1274.png">
<br />
VS Code
</p>

[Visual Studio Marketplace](https://marketplace.visualstudio.com/VSCode) is a marketplace for all extensions for Visual Studio, Azure DevOps Services, Azure DevOps Server and Visual Studio Code.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140832440-0247a088-4eeb-4c57-ae7d-90894d56d629.png">
<br />
VS Code Marketplace
</p>


[VS Code Documentation](https://code.visualstudio.com/docs)

[Working with GitHub in VS Code](https://code.visualstudio.com/docs/editor/github)

[Code Server](https://coder.com/) is a tool that allows you to run [VS Code](https://code.visualstudio.com/) on any machine anywhere and access it in the browser.

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code. Also, from any repo or pull request on GitHub you can simply press the period (.) key on your keyboard to bring up the browser-based VS Code environment with the source code file ready for editing. That dot (.) press to bring up the web-based VS Code editor takes you to https://github.dev/.

[Language Server Protocol (LSP)](https://microsoft.github.io/language-server-protocol/) is a tool that defines the protocol used between an editor or IDE and a language server that provides language features like auto complete, go to definition, find all references.

### VS Code Extensions for Developer Productivity

[Visual Studio Live Share](https://visualstudio.microsoft.com/services/live-share/) is a service/ extension that enables you to collaboratively edit and debug with others in real time, regardless of the programming languages you're using or app types you're building. You can instantly and securely share your current project, start a joint debugging session, share terminal instances, forward localhost web apps, have voice calls, and more.

[GistPad](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gistfs) is a Visual Studio Code extension that allows you to edit GitHub Gists and repositories from the comfort of your favorite editor. You can open, create, delete, fork and star gists and repositories, and then seamlessly begin editing files as if they were local, without ever cloning, pushing or pulling anything.

[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) is an extension for Visual Studio Code that launches a development local Server with live reload feature for static & dynamic pages.

[GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) is an extension for Visual Studio Code that allows you to review and manage GitHub pull requests and issues in Visual Studio Code.

[Terminal](https://marketplace.visualstudio.com/items?itemName=formulahendry.terminal) is an extension for Visual Studio Code that lets you run terminal command directly in the Editor.

[Profile Switcher](https://marketplace.visualstudio.com/items?itemName=aaronpowell.vscode-profile-switcher) is an extension for Visual Studio Code that allows you to switch between different profiles you have created.

[Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) is an extension for Visual Studio Code that gets the Material Design icons into your VS Code.

[One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme) is an extension for Visual Studio Code that adds Atom's iconic One Dark theme, which is one of the most installed themes for VS Code.

[VSCode Icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) is an extension for Visual Studio Code that brings icons to your Visual Studio Code setup.

[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) is an extension for Visual Studio Code that helps you visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more.

[Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) is an extension for Visual Studio Code that will display inline in the editor the size of the imported/required package. The extension utilizes webpack with babili-webpack-plugin in order to detect the imported size.

[Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) is an extension for Visual Studio Code that gives you everything you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more).

[Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer) is an extension for Visual Studio Code that allows matching brackets to be identified with colours. The user can define which characters to match, and which colours to use.

[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) is an extension for Visual Studio Code that automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text.

[Auto-Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) is an extension for Visual Studio Code that automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text does.

[Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync) is an extension for Visual Studio Code that synchronizes Settings, Snippets, Themes, File Icons, Launch, Keybindings, Workspaces and Extensions Across Multiple Machines Using GitHub Gist.

[Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) is an extension for Visual Studio Code that lets you mark lines of code and jump to them.

[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) is an extension for Visual Studio Code that improves your code commenting by annotating with alert, informational, TODOs, and more.

[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) is an extension for Visual Studio Code that works as a spelling checker for source code.

[CSS Peak](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek) is an extension for Visual Studio Code that allows peeking to css ID and class strings as definitions from html files to respective CSS. It also allows peek and goto definition.

[Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) is an extension for Visual Studio Code that enhances the Tailwind development experience by providing Visual Studio Code users with advanced features such as autocomplete, syntax highlighting, and linting.

[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) is an extension for Visual Studio Code that is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

[NPM Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) is an extension for Visual Studio Code that autocompletes npm modules in import statements.

[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) is an extension for Visual Studio Code that autocompletes filenames.

[Relative Path](https://marketplace.visualstudio.com/items?itemName=jakob101.RelativePath) is an extension for Visual Studio Code that gets the relative url paths from files in the current workspace.

[Path Autocomplete](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete) is an extension for Visual Studio Code that provides path completion for visual studio code.

[Discord Presence](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode) is an extension for Visual Studio Code that updates your discord status with a rich presence.

[Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) is an extension for Visual Studio Code that runs code snippets or code files for multiple languages: C/C++, Java, JavaScript, PHP, Python, Perl, Ruby, Go, Lua, Groovy, PowerShell, BASH/SH, C#, F#, .NET Core, TypeScript, CoffeeScript, Scala, Swift, Julia, OCaml, R, Elixir, Clojure, Haxe, Objective-C, Rust, Racket, Scheme, Kotlin, Dart, Haskell, Nim, D, CUDA, and custom command.

[Kite](https://marketplace.visualstudio.com/items?itemName=kiteco.kite) is an extension for Visual Studio Code that provides an AI-powered programming assistant that helps you write code faster inside Visual Studio Code. Kite works for all major programming languages: Python, Java, Go, PHP, C/C#/C++, Javascript, HTML/CSS, Typescript, React, Ruby, Scala, Kotlin, Bash, Vue and React.

[Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) is an extension for Visual Studio Code that provides an AI code completion tool trusted by millions of developers to code faster with fewer errors. Whether you are a new dev or a seasoned pro, working solo or part of a team, Tabnine will help push your productivity to new heights while cutting your QA time in your favorite IDE.

# Xcode Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/141201793-f31f4899-7317-49a7-808b-6e551df23bf9.png">
  <br />
  Xcode Guide
</p>

## Getting Started with Xcode

[Apple Developer Documentation for Xcode](https://developer.apple.com/documentation/xcode)

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging. Xcode 12 is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880054-dd9fb700-8292-11eb-9478-a5d62dc76f9d.png">
<br />
Developing with SwiftUI in Xcode 12
</p>

[Xcode Cloud](https://developer.apple.com/xcode-cloud/) is a continuous integration and delivery service built into Xcode and designed expressly for Apple developers. It accelerates the development and delivery of high-quality apps by bringing together cloud-based tools that help you build apps, run automated tests in parallel, deliver apps to testers, and view and manage user feedback.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821101-9cc98c80-cc4b-11eb-9dde-e3efa2ea8154.png">
<br />
</p>

**Xcode Cloud. Source: [Apple](https://developer.apple.com/xcode-cloud/)**

[SwiftUI](https://developer.apple.com/documentation/swiftui) is a user interface toolkit that provides views, controls, and layout structures for declaring your app's user interface. The SwiftUI framework provides event handlers for delivering taps, gestures, and other types of input to your application.

[UIKit](https://developer.apple.com/documentation/uikit) is a framework provides the required infrastructure for your iOS or tvOS apps. It provides the window and view architecture for implementing your interface, the event handling infrastructure for delivering Multi-Touch and other types of input to your app, and the main run loop needed to manage interactions among the user, the system, and your app.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[Mac Catalyst](https://developer.apple.com/mac-catalyst/) is a set of Apple APIs that developers can use to rapidly port their iOS apps to [Apple Silicon M1 Chip](https://www.apple.com/mac/m1/) and take full advantage of the new capabilities on the new Apple hardware.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. It’s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[TestFlight](https://developer.apple.com/testflight/) is a tool that makes it easy to invite users to test your apps and App Clips and collect valuable feedback before releasing your apps on the App Store. It allows you to invite up to 10,000 testers using just their email address or by sharing a public link.

## Xcode Developer Platforms for Apps

[macOS](https://www.apple.com/macos/monterey/) is an advanced desktop operating system (OS) for Apple's series of desktops and laptops.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821090-8d4a4380-cc4b-11eb-896a-74e1be0fb3c6.png">
<br />
</p>

**macOS Monterey. Source: [Apple](https://www.apple.com/macos/monterey/)**

[iOS](https://www.apple.com/ios/ios-15/) is an advanced mobile operating system (OS) for Apple's series of iPhone products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821096-976c4200-cc4b-11eb-9006-641b1c99a9e7.png">
<br />
</p>

**iOS 15. Source: [Apple](https://www.apple.com/ios/ios-15/)**

[iPadOS](https://www.apple.com/ipados/ipados-15/) is an advanced mobile operating system (OS) for Apple's series of iPad products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821093-93402480-cc4b-11eb-9a02-42e75c811c39.png">
<br />
</p>

**iPadOS 15. Source: [Apple](https://www.apple.com/ipados/ipados-15/)**

[WatchOS](https://www.apple.com/watchos/watchos-8/) is an advanced mobile operating system (OS) for Apple's series of Watch products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821100-9b985f80-cc4b-11eb-9c10-1e3aac33feda.png">
<br />
</p>

**WatchOS 8. Source: [Apple](https://www.apple.com/watchos/watchos-8/)**

[tvOS](https://developer.apple.com/tvos/) is an advanced mobile operating system (OS) for Apple's series of TV products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/141201806-71144a22-879d-474a-a7ef-45ace396584c.png">
<br />
</p>

**tvOS 15. Source: [Apple](https://developer.apple.com/tvos/)**

# Game Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/97361059-45151700-185c-11eb-9d12-dae51c79eb8a.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119279021-ea6b5000-bbdd-11eb-9f59-5251fc3ac751.png">
  <br />
</p>

## Game Development Tools

[NVIDIA Reflex](https://developer.nvidia.com/reflex/get-started) is a new feature that was introduced with the RTX 30(3000) series GPUs that allows game developers to implement a low latency mode that aligns game engine work to complete just-in-time for rendering, eliminating the GPU render queue and reducing CPU back pressure in GPU-bound scenarios. In addition to latency reduction functions, the SDK also features measurement markers to calculate both Game and Render Latency that are great for debugging and visualizing in-game performance counter.

[NVIDIA DLSS (Deep Learning Super Sampling)](https://developer.nvidia.com/dlss) is a temporal image upscaling AI rendering technology that increases graphics performance using dedicated Tensor Core AI processors on GeForce RTX™ GPUs. DLSS uses the power of a deep learning neural network to boost frame rates and generate beautiful, sharp images for your games.

[AMD FidelityFX Super Resolution (FSR)](https://www.amd.com/en/technologies/radeon-software-fidelityfx) is an open source, high-quality solution for producing high resolution frames from lower resolution inputs. It uses a collection of cutting-edge Deep Learning algorithms with a particular emphasis on creating high-quality edges, giving large performance improvements compared to rendering at native resolution directly. FSR enables “practical performance” for costly render operations, such as hardware ray tracing for the AMD RDNA™ and AMD RDNA™ 2 architectures.

[Intel Xe Super Sampling (XeSS)](https://www.youtube.com/watch?v=Y9hfpf-SqEg) is a temporal image upscaling AI rendering technology that increases graphics performance similar to NVIDIA's [DLSS (Deep Learning Super Sampling)](https://developer.nvidia.com/dlss). Intel's Arc GPU architecture (early 2022) will have GPUs that feature dedicated Xe-cores to run XeSS. The GPUs will have Xe Matrix eXtenstions matrix (XMX) engines for hardware-accelerated AI processing. XeSS will be able to run on devices without XMX, including integrated graphics, though, the performance of XeSS will be lower on non-Intel graphics cards because it will be powered by [DP4a instruction](https://www.intel.com/content/dam/www/public/us/en/documents/reference-guides/11th-gen-quick-reference-guide.pdf).

[Unigine](https://unigine.com) is a cross-platform game engine designed for development teams (C++/C# programmers, 3D artists) working on interactive 3D apps.

[Frostbite](https://www.ea.com/frostbite/engine) is a game engine developed by [DICE](https://www.dice.se/), designed for cross-platform use on Microsoft Windows and game consoles such as PlayStation 3 Xbox 360,  PlayStation 4, Xbox One, Nintendo Switch, PlayStation 5, and Xbox Series X/S.

[Panda3D](https://www.panda3d.org/) is a game engine, a framework for 3D rendering and game development for Python and C++ programs, developed by Disney and CMU. Panda3D is open-source and free for any purpose, including commercial ventures.

[Source 2](https://developer.valvesoftware.com/wiki/Source_2) is a 3D video game engine in development by Valve as a successor to Source. It is used in Dota 2, Artifact, Dota Underlords, parts of The Lab, SteamVR Home, and Half-Life: Alyx.

[Havok](https://www.havok.com/) is a middleware software suite that provides a realistic physics engine component and related functions to video games. It is supported  and optimized across all major platforms, including Nintendo Switch, PlayStation®, Stadia, and Xbox. Along with integrations for Unity and Unreal Engine and are used in countless proprietary game engines.

[AutoDesk 3ds Max](https://www.autodesk.com/products/3ds-max/overview) is a professional software program for 3D modeling, animation, rendering, and visualization. 3ds Max allows you to create stunning game environments, design visualizations, and virtual reality experiences.

[Houdini](https://www.sidefx.com/) is a 3D procedural software for modeling, rigging, animation, VFX, look development, lighting and rendering in film, TV, advertising and video game pipelines.

[A-Frame](https://aframe.io) is a web framework for building virtual reality experiences in WebVR with HTML and Entity-Component. A-Frame works on Vive, Rift, desktop, mobile platforms.

[AppGameKit](https://www.appgamekit.com) is a powerful game development engine, ideal for Hobbyist and Indie developers. Where you can start coding in the easy to learn AppGameKit BASIC or use the libraries in C++ & XCode.

[Amazon Lumberyard](https://aws.amazon.com/lumberyard/) is an open source, AAA game engine(based on CryEngine) that gives you the tools you need to create high quality games. Deeply integrated with AWS and Twitch, Amazon Lumberyard includes full source code, allowing you to customize your project at any level.

[Blender](https://www.blender.org) is the free and open source 3D creation suite. It supports the entirety of the 3D pipeline—modeling, rigging, animation, simulation, rendering, compositing and motion tracking, video editing and 2D animation pipeline.

[CryEngine](https://www.cryengine.com) is a powerful real-time game development platform created by Crytek.

[GameMaker Studio 2](https://www.yoyogames.com/gamemaker) is the latest and greatest incarnation of GameMaker. It has everything you need to take your idea from concept to finished game. With no barriers to entry and powerful functionality, GameMaker Studio 2 is the ultimate 2D development environment.

[Godot](https://godotengine.org) is a feature-packed, cross-platform game engine to create 2D and 3D games from a unified interface. It provides a comprehensive set of common tools, so that users can focus on making games without having to reinvent the wheel. Games can be exported in one click to a number of platforms, including the major desktop platforms (Linux, Mac OSX, Windows) as well as mobile (Android, iOS) and web-based (HTML5) platforms.

[Open Graphics Library(OpenGL)](https://www.opengl.org/) is an API used acrossed mulitple  programming languages and platforms for hardware-accelerated rendering of 2D/3D vector graphics currently developed by the [Khronos Group](https://www.khronos.org/).

[Open Computing Language (OpenCL)](https://www.khronos.org/opencl/) is an open standard for [parallel programming](https://www.coursera.org/lecture/parprog1/introduction-to-parallel-computing-zNrIS) of heterogeneous platforms consisting of CPUs, GPUs, and other hardware accelerators found in supercomputers, cloud servers, personal computers, mobile devices and embedded platforms.

[OpenGL Shading Language(GLSL)](https://www.khronos.org/opengl/wiki/Core_Language_(GLSL)) is a High Level Shading Language based on the C-style language, so it covers most of the features a user would expect with such a language.  Such as control structures (for-loops, if-else statements, etc) exist in GLSL, including the switch statement.

[High Level Shading Language(HLSL)](https://docs.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl) is the High Level Shading Language for DirectX. Using HLSL, the user can create C-like programmable shaders for the Direct3D pipeline. HLSL was first created with DirectX 9 to set up the programmable 3D pipeline.

[DirectX 12 Ultimate](https://github.com/Microsoft/DirectX-Graphics-Samples) is an API(for high performance 2D & 3D graphics) from Microsoft. DirectX 12 Ultimate brings support for ray tracing, mesh shaders, variable rate shading, and sampler feedback. Available in Windows 2004 version(May 2020 Update).

[Vulkan](https://www.khronos.org/vulkan/) is a modern cross-platform graphics and compute API that provides high-efficiency, cross-platform access to modern GPUs used in a wide variety of devices from PCs and consoles to mobile phones and embedded platforms. Vulkan is currently in development by the Khronos consortium.

[Metal](https://developer.apple.com/metal/) is a low-level GPU programming framework used for rendering 2D and 3D graphics on Apple platforms such as iOS, iPadOS, macOS, watchOS and tvOS.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[MoltenGL](https://moltengl.com) is an implementation of the OpenGL ES 2.0 API that runs on Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[Mesa 3D Graphics Library](https://docs.mesa3d.org/index.html) is a project began as an open-source implementation of the OpenGL specification. A system for rendering interactive 3D graphics. Mesa ties into several other open-source projects: the [Direct Rendering Infrastructure](https://dri.freedesktop.org/), [X.org](https://x.org/), and [Wayland](https://wayland.freedesktop.org/) to provide OpenGL support on Linux, FreeBSD, and other operating systems.

[OpenGL ES](https://www.khronos.org/opengles/) is the mobile subset of OpenGL. It's supported on all major mobile platforms, and is also the base for WebGL.

[OpenCL](https://www.khronos.org/opencl/) is a framework for writing programs that execute across heterogeneous platforms consisting of CPUs, GPUs, DSPs, FPGAs and other processors or hardware accelerators.

[EGL](https://www.khronos.org/egl/) is an interface between Khronos rendering APIs such as OpenGL or OpenVG and the underlying native platform window system.

[VDPAU](https://www.freedesktop.org/wiki/Software/VDPAU/) is the Video Decode and Presentation API for UNIX. It provides an interface to video decode acceleration and presentation hardware present in modern GPUs.

[VA API](https://freedesktop.org/wiki/Software/vaapi/) is an open-source library and API specification, which provides access to graphics hardware acceleration capabilities for video processing.

[XvMC](https://en.wikipedia.org/wiki/X-Video_Motion_Compensation) is an extension of the X video extension (Xv) for the X Window System. The XvMC API allows video programs to offload portions of the video decoding process to the GPU hardware.

[AMD Radeon ProRender](https://www.amd.com/en/technologies/radeon-prorender) is a powerful physically-based rendering engine that enables creative professionals to produce stunningly photorealistic images on virtually any GPU, any CPU, and any OS in over a dozen leading digital content creation and CAD applications.

[NVIDIA Omniverse](https://developer.nvidia.com/nvidia-omniverse-platform) is a powerful, multi-GPU, real-time simulation and collaboration platform for 3D production pipelines based on Pixar's Universal Scene Description and NVIDIA RTX.

[LibGDX](https://github.com/libgdx/libgdx) is a cross-platform Java game development framework based on OpenGL (ES) that works on Windows, Linux, Mac OS X, Android, your WebGL enabled browser and iOS.

[cocos2d-x](https://github.com/cocos2d/cocos2d-x) is a multi-platform framework for building 2d games, interactive books, demos and other graphical applications. It is based on cocos2d-iphone, but instead of using Objective-C, it uses C++. It works on iOS, Android, macOS, Windows and Linux.

[MonoGame](https://github.com/MonoGame/MonoGame) is a framework for creating powerful cross-platform games. The spiritual successor to XNA with thousands of titles shipped across desktop, mobile, and console platforms. MonoGame is a fully managed .NET open source game framework without any black boxes.

[Three.js](https://threejs.org) is a cross-browser JavaScript library and application programming interface used to create and display animated 3D computer graphics in a web browser using WebGL.

[Superpowers](http://superpowers-html5.com/) is a downloadable HTML5 app for real-time collaborative projects . You can use it solo like a regular offline game maker, or setup a password and let friends join in on your project through their Web browser.

[URHO3D](https://urho3d.github.io/) is a free lightweight, cross-platform 2D and 3D game engine implemented in C++ and released under the MIT license. Greatly inspired by OGRE and Horde3D.

[Vivox](https://www.vivox.com/) is a voice & text chat platform that's trusted by the world's biggest gaming brands and titles such as Fortnite, PUBG, League of Legends, and Rainbow Six Siege.

[HGIG](https://www.hgig.org/) is a volunteer group of companies from the game and TV display industries that meet to specify and make available for the public guidelines to improve consumer gaming experiences in HDR.

[GameBlocks](https://www.gameblocks.com/) is a Server Side Anti-Cheat & Middleware software.

# Augmented Reality (AR) & Virtual Reality (VR)
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/130368380-37b7c0cd-ed71-4a52-8b16-4ac802e059d4.png">
  <br />
</p>

## Augmented Reality (AR) & Virtual Reality (VR) Learning Resources

[Augmented Reality (AR)](https://en.wikipedia.org/wiki/Augmented_reality) is an interactive experience of a real-world environment where the objects that reside in the real world are enhanced by computer-generated perceptual information.

[Virtual Reality (VR)](https://en.wikipedia.org/wiki/Virtual_reality) is a simulated experience that can be similar to or completely different from the real world. The applications of virtual reality include entertainment (video games), education (medical or military training) and business (virtual meetings).

[Mixed Reality (MR)](https://en.wikipedia.org/wiki/Mixed_reality) is the merging of real and virtual worlds to produce new environments and visualizations, where physical and digital objects co-exist and interact in real time.

[Extended Reality (XR)](https://en.wikipedia.org/wiki/Extended_reality) is a concept referring to all real-and-virtual combined environments and human-machine interactions generated by computer technology and wearables. Including augmented reality (AR), mixed reality (MR) and virtual reality (VR).

[Virtual Reality - Experiences and Devices](https://www.microsoft.com/en-us/mixed-reality/windows-mixed-reality)

[Oculus | VR Headsets, Games & Equipment](https://www.oculus.com/)

[Virtual Reality on Steam](https://store.steampowered.com/vr/)

[Valve Index® VR Headset](https://store.steampowered.com/valveindex)

[PlayStation VR](https://www.playstation.com/explore/playstation-vr/)

[HTC Vive VR Headset](https://www.vive.com/us/)

[Augmented Reality applications - Apple](https://www.apple.com/augmented-reality/)

[Unity Learn Training Program](https://learn.unity.com)

[Unity Manual: XR](https://docs.unity3d.com/Manual/XR.html)

[Intro to XR: VR, AR, and MR Foundations - Unity Learn](https://learn.unity.com/course/introduction-to-xr-vr-ar-and-mr-foundations)

[Unity XR: Build VR and AR Apps](https://unity3d.com/learn/unity-xr-apps)

[Top Virtual Reality Courses Online | Udemy](https://www.udemy.com/topic/virtual-reality/)

[Top Augmented Reality Courses Online | Udemy](https://www.udemy.com/topic/augmented-reality/)

[Google AR & VR Online Courses | Coursera](https://www.coursera.org/googlearvr)

[Top Augmented Reality Courses | Coursera](https://www.coursera.org/courses?query=augmented%20reality)

[Learn Augmented Reality with Online Courses and Lessons | edX](https://www.edx.org/learn/augmented-reality)

## Augmented Reality (AR) & Virtual Reality (VR) Tools and Frameworks

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[GPUImage framework](https://github.com/BradLarson/GPUImage) is a BSD-licensed iOS library that lets you apply GPU-accelerated filters and other effects to images, live camera video, and movies. In comparison to Core Image (part of iOS 5.0), GPUImage allows you to write your own custom filters, supports deployment to iOS 4.0, and has a simpler interface. However, it currently lacks some of the more advanced features of Core Image, such as facial detection.

[GPUImage3](https://github.com/BradLarson/GPUImage3) is the third generation of the [GPUImage framework](https://github.com/BradLarson/GPUImage), an open source project for performing GPU-accelerated image and video processing on Mac and iOS. The original GPUImage framework was written in Objective-C and targeted Mac and iOS, the second iteration rewritten in Swift using OpenGL to target Mac, iOS, and Linux, and now this third generation is redesigned to use [Apple's Metal](https://developer.apple.com/metal/) in place of OpenGL.

[ARCore](https://developers.google.com/ar/) is a software development kit developed by Google that allows for augmented reality applications in the real world. These tools include environmental understanding, which allows devices to detect horizontal and vertical surfaces and planes. It also includes motion tracking, which lets phones understand and track their positions relative to the world. Also ARCore’s Light Estimation API lets your digital objects appear realistically as if they’re actually part of the physical world.

[Adobe Aero](https://www.adobe.com/products/aero.html) is a powerful new [augmented reality (AR)](https://en.wikipedia.org/wiki/Augmented_reality) authoring tool that makes it easier for designers to create immersive content.

[Vuforia](https://developer.vuforia.com/) is a comprehensive, scalable enterprise AR platform. Our wide-ranging solution suite ensures that we can provide the right AR technology to every customer based on their business needs.

[Vuforia Studio](https://www.ptc.com/en/products/vuforia/vuforia-studio) is a tool that allows anyone to create beautiful 3D augmented reality (AR) experiences in a matter of minutes with no coding required.

[OpenVX™](https://www.khronos.org/openvx/) is an open-source, royalty-free standard for cross platform acceleration of computer vision applications. OpenVX enables performance and power-optimized computer vision processing, especially important in embedded and real-time use cases such as face, body and gesture tracking, smart video surveillance, advanced driver assistance systems (ADAS), object and scene reconstruction, augmented reality, visual inspection, robotics and more.

[NVIDIA Flex](https://github.com/NVIDIAGameWorks/FleX) is a particle-based simulation library designed for real-time applications.

[ARToolKit](https://artoolkit.org) is a fast and modern open source tracking and recognition SDK which enables computers to see and understand more in the environment around them. It's built from the ground up using modern computer vision techniques.

[ARmedia](https://www.inglobetechnologies.com/ar-media/) is a plugin tool that makes it easy to develop and create AR experiences without coding.

[Kundan](https://www.kudan.io/) is a tool that provides proprietary Artificial Perception technologies based on SLAM to enable use cases with significant market potential and impact on our lives such as autonomous driving, robotics, AR/VR and smart cities.

[OVR Toolkit](https://store.steampowered.com/app/1068820/OVR_Toolkit/) is a utility application designed to make viewing the desktop in VR simple and fast, it allows for viewing the desktop within VR, placing desktop windows around the world, mouse input, typing with a virtual keyboard, and quickly switching between windows.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/117720758-e843d300-b193-11eb-9796-bde15aebed71.png">
<br />
</p>

Microsoft HoloLens Headset. Source: [Microsoft](https://www.microsoft.com/en-us/hololens/buy)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/117720763-e9750000-b193-11eb-888a-e4bccd6c30eb.png">
<br />
</p>

PlayStation VR Headset. Source: [PlayStation](https://www.playstation.com/en-us/ps-vr/)

[SteamVR](https://store.steampowered.com/steamvr) is the ultimate tool for experiencing VR content on the hardware of your choice. SteamVR supports the Valve Index, HTC Vive, Oculus Rift, Windows Mixed Reality headsets, and others.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110881514-543db400-8295-11eb-9543-fd5d385ddb05.png">
<br />

SteamVR Home
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/117720776-ed088700-b193-11eb-8538-9831999b5104.png">
<br />
</p>
Valve Index VR Headset. Source: [Steam](https://store.steampowered.com/valveindex)


[OpenVR](https://github.com/ValveSoftware/openvr) is an API and runtime that allows access to VR hardware(Steam Index, HTC Vive, and Oculus Rift) from multiple vendors without requiring that applications have specific knowledge of the hardware they are targeting.

[OpenVR Benchmark on Steam](https://store.steampowered.com/app/955610/OpenVR_Benchmark/) is the first benchmark tool for reproducibly testing your real VR performance, rendering inside of your VR headset.

[OpenHMD](http://www.openhmd.net/) is open source API and drivers that supports a wide range of HMD(head-mounted display) devices such as Oculus Rift, HTC Vive, Sony PSVR, and others.

[openXR](https://www.khronos.org/OpenXR/) is a free, open standard that provides high-performance access to Augmented Reality (AR) and Virtual Reality (VR) collectively known as XR—platforms and devices.

[Monado](https://monado.dev/) is the first OpenXR™ runtime for GNU/Linux. Monado aims to jump-start development of an open source XR ecosystem and provide the fundamental building blocks for device vendors to target the GNU/Linux platform.

[Libsurvive](https://github.com/cntools/libsurvive) is a set of tools and libraries that enable 6 dof tracking on lighthouse and vive based systems that is completely open source and can run on any device. It currently supports both SteamVR 1.0 and SteamVR 2.0 generation of devices and should support any tracked object commercially available.

[Simula](https://github.com/SimulaVR/Simula) is a VR window manager for Linux that runs on top of Godot. It takes less than 1 minute to install. Simula is officially compatible with SteamVR headsets equipped with Linux drivers (e.g. HTC Vive, HTC Vive Pro, & Valve Index). We have also added experimental support to OpenXR headsets that have Monado drivers (e.g. North Star, OSVR HDK, and PSVR). Some people have gotten the Oculus Rift S to run Simula via OpenHMD ([see here](https://github.com/OpenHMD/OpenHMD/issues/225#issuecomment-638454156)).

# Vulkan Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/129622224-8c4cca51-9200-4d70-9d16-2610d704713a.png">
  <br />
</p>

## Vulkan Learning Resources

[Vulkan®](https://www.khronos.org/vulkan/) is a modern cross-platform graphics and compute API that provides high-efficiency, cross-platform access to modern GPUs used in a wide variety of devices from PCs and consoles to mobile phones and embedded platforms. Vulkan is currently in development by the Khronos consortium.

[Khronos Group GitHub](https://github.com/KhronosGroup)

[Vulkan Documentation](https://github.com/KhronosGroup/Vulkan-Docs)

[HLSL to SPIR-V Feature Mapping Manual](https://github.com/microsoft/DirectXShaderCompiler/blob/master/docs/SPIR-V.rst)

[Vulkan GLSL Ray Tracing Emulator Tutorial](https://www.gsn-lib.org/docs/nodes/raytracing.php)

[Getting Started with Vulkan](https://vulkan-tutorial.com/)

[Vulkan Samples](https://github.com/KhronosGroup/Vulkan-Samples)

[Khronos Community Forums](https://community.khronos.org/)

## Vulkan Tools, Libraries, and Frameworks

[Vulkan SDK](https://vulkan.lunarg.com) is a set of tools that enables Vulkan developers to develop Vulkan applications.

[SPIR-V](https://www.khronos.org/spir/) is a set of tools that enables high-level language front-ends to emit programs in a standardized intermediate form to be ingested by Vulkan, OpenGL or OpenCL drivers. It eliminates the need for high-level language front-end compilers in device drivers, significantly reducing driver complexity, enables a broad range of language and framework front-ends to run on diverse hardware architectures and encourages a vibrant ecosystem of open source analysis, porting, debug and optimization tools.

[SPIRV-Reflect](https://github.com/KhronosGroup/SPIRV-Reflect) is a lightweight library that provides a C/C++ reflection API for SPIR-V shader bytecode in Vulkan applications.

[Vulkan® Tools](https://github.com/KhronosGroup/Vulkan-Tools) is a project that provides Khronos official Vulkan Tools and Utilities for Windows, Linux, Android, and macOS.

[Vulkan-Hpp](https://github.com/KhronosGroup/Vulkan-Hpp) is a API that provides a header only C++ bindings for the Vulkan C API to improve the developers Vulkan experience without introducing CPU runtime cost. It adds features like type safety for enums and bitfields, STL container support, exceptions and simple enumerations.

[Vulkan® Memory Allocator (VMA)](https://gpuopen.com/vulkan-memory-allocator/) is a  library that provides a simple and easy to integrate API to help you allocate memory for Vulkan® buffer and image storage.

[AMD Open Source Driver for Vulkan®](https://gpuopen.com/amd-open-source-driver-for-vulkan/) is an open-source Vulkan driver for AMD Radeon™ graphics adapters on Linux®.

[NVIDIA® Nsight™ Visual Studio Edition](https://developer.nvidia.com/nsight-visual-studio-edition) is an application development environment for heterogeneous platforms which brings GPU computing into Microsoft Visual Studio. NVIDIA Nsight™ VSE allows you to build and debug integrated GPU kernels and native CPU code as well as inspect the state of the GPU and memory.

[Radeon™ GPU Profiler](https://gpuopen.com/rgp/) is a performance tool that can be used by developers to optimize DirectX®12, Vulkan® and OpenCL™ applications for AMD RDNA™ and GCN hardware.

[Radeon™ GPU Analyzer](https://gpuopen.com/rga/) is a compiler and code analysis tool for Vulkan®, DirectX®, OpenGL® and OpenCL™.

[Radeon™ Memory Visualizer (RMV)](https://gpuopen.com/rmv/) is a tool provided by AMD for use by game engine developers. It allows engineers to examine, diagnose, and understand the GPU memory management within their projects.

[DXVK](https://github.com/doitsujin/dxvk) is a Vulkan-based translation layer for Direct3D 9/10/11 which allows running 3D applications on Linux using Wine.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[RenderDoc](https://renderdoc.org) is a stand-alone graphics debugger that allows quick and easy single-frame capture and detailed introspection of any application using Vulkan, D3D11, OpenGL & OpenGL ES or D3D12 across Windows, Linux, Android, Stadia, or Nintendo Switch™.

[PerfDoc](https://github.com/ARM-software/perfdoc) is a cross-platform Vulkan layer which checks Vulkan applications for [best practices on Arm Mali](https://developer.arm.com/graphics/developer-guides/mali-gpu-best-practices) devices.

[GLFW](https://www.glfw.org/) is an Open Source, multi-platform library for OpenGL, OpenGL ES and Vulkan application development. It provides a simple, platform-independent API for creating windows, contexts and surfaces, reading input, handling events, etc. GLFW natively supports Windows, macOS and Linux and other Unix-like systems. On Linux both X11 and Wayland are supported.

[VulkanSharp](https://github.com/mono/VulkanSharp) is a project provides a .NET binding for the Vulkan API.

[Vortice.Vulkan](https://github.com/amerkoleci/Vortice.Vulkan) is a .NET Standard 2.0 and .NET5 low-level bindings for Vulkan API.

[VKD3D-Proton](https://github.com/HansKristian-Work/vkd3d-proton) is a fork of VKD3D, which aims to implement the full Direct3D 12 API on top of Vulkan.

[ImGui](https://github.com/ocornut/imgui) is a bloat-free graphical user interface library for C++. It outputs optimized vertex buffers that you can render anytime in your 3D-pipeline enabled application. It is fast, portable, renderer agnostic and self-contained (no external dependencies).

[Ash](https://github.com/MaikKlein/ash) is a very lightweight wrapper around Vulkan.

[gfx-rs](https://github.com/gfx-rs/gfx) is a low-level, cross-platform graphics and compute abstraction library in Rust.

[Vulkan.jl](https://github.com/JuliaGPU/Vulkan.jl) is a lightweight wrapper around the Vulkan graphics and compute library. It exposes abstractions over the underlying C interface, primarily geared towards developers looking for a more natural way to work with Vulkan with minimal overhead.

# Metal Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/129622324-243aca6c-1feb-4b16-abef-70ad8b97f488.png">
  <br />
</p>

## Metal Learning Resources

[Metal](https://developer.apple.com/metal/) is a low-level API that provides a platform-optimized, low-overhead API for developing the latest 3D pro applications and amazing games using a rich shading language with tighter integration between graphics and compute programs. To help you do more while managing ever more complex shader code, Metal adds an unparalleled suite of advanced GPU debugging tools to help you realize the full potential of your graphics code.

[Apple Developer Documentation](https://developer.apple.com/documentation)

[MetalKit](https://developer.apple.com/documentation/metalkit/)

[Metal Shading Language Specification](https://developer.apple.com/metal/Metal-Shading-Language-Specification.pdf)

[Using Metal Feature Set Tables](https://developer.apple.com/documentation/metal/gpu_features/using_metal_feature_set_tables/)

[Metal Performance Shaders](https://developer.apple.com/documentation/metalperformanceshaders/)

[Optimizing Performance with the GPU Counters Instrument](https://developer.apple.com/documentation/metal/optimizing_performance_with_the_gpu_counters_instrument?language=objc)

[Enabling Frame Capture](https://developer.apple.com/documentation/metal/frame_capture_debugging_tools/enabling_frame_capture?language=objc)

[Reducing the Memory Footprint of Metal Apps](https://developer.apple.com/documentation/metal/reducing_the_memory_footprint_of_metal_apps)

[Metal Developer Tools for Windows](https://developer.apple.com/download/release/)

[Metal Sample code](https://developer.apple.com/metal/sample-code/)

[Metal plugin for TensorFlow](https://developer.apple.com/metal/tensorflow-plugin/)

[Metal Developer discussions](https://developer.apple.com/forums/tags/metal/)

## Metal Tools, Libraries, and Frameworks

[Apple Foundation Framework](https://developer.apple.com/documentation/foundation) is a framework provides a base layer of functionality for apps and frameworks, including data storage and persistence, text processing, date and time calculations, sorting and filtering, and networking. The classes, protocols, and data types defined by Foundation are used throughout the macOS, iOS, watchOS, and tvOS SDKs.

[Apple Core Animation Framework](https://developer.apple.com/documentation/quartzcore) is a graphics rendering and animation infrastructure that provides high frame rates and smooth animations without burdening the CPU and slowing down your app.

[Apple Core Graphics Framework](https://developer.apple.com/documentation/coregraphics)is a framework based on the Quartz advanced drawing engine. It provides low-level, lightweight 2D rendering with unmatched output fidelity.

[Paravirtualized Graphics Framework](https://developer.apple.com/documentation/paravirtualizedgraphics) is a framework that implements hardware-accelerated graphics for macOS running in a virtual machine, hereafter known as the guest. The macOS operating system provides a graphics driver that runs inside the guest, communicating with the framework in the host operating system to take advantage of Metal-accelerated graphics.

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging. Xcode 12 is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU.

[SwiftUI](https://developer.apple.com/documentation/swiftui) is a user interface toolkit that provides views, controls, and layout structures for declaring your app's user interface. The SwiftUI framework provides event handlers for delivering taps, gestures, and other types of input to your application.

[UIKit](https://developer.apple.com/documentation/uikit) is a framework provides the required infrastructure for your iOS or tvOS apps. It provides the window and view architecture for implementing your interface, the event handling infrastructure for delivering Multi-Touch and other types of input to your app, and the main run loop needed to manage interactions among the user, the system, and your app.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. It’s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[Cocoapods](https://cocoapods.org/) is a dependency manager for Swift and Objective-C used in Xcode projects by specifying the dependencies for your project in a simple text file. CocoaPods then recursively resolves dependencies between libraries, fetches source code for all dependencies, and creates and maintains an Xcode workspace to build your project.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

# DirectX Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/146693482-58c6d5d6-06ff-4ba9-b77e-38307358370d.png">
  <br />
</p>

## DirectX Learning Resources

[Microsoft DirectX®](https://support.microsoft.com/en-us/topic/how-to-install-the-latest-version-of-directx-d1f5ffa5-dae2-246c-91b1-ee1e973ed8c2) is a low-level API that handles tasks related to multimedia for game programming and video on Microsoft platforms(Windows & Xbox).

[Getting Started with DirectX 12 Ultimate](https://devblogs.microsoft.com/directx/directx-12-ultimate-getting-started-guide/)

[Getting Started with the DirectX 12 Agility SDK](https://devblogs.microsoft.com/directx/gettingstarted-dx12agility/)

[DirectX 12 and Graphics Education | YouTube](https://www.youtube.com/channel/UCiaX2B8XiXR70jaN7NK-FpA)

[DirectX— Feature Level 12_2](https://devblogs.microsoft.com/directx/new-in-directx-feature-level-12_2/)

[DirectX 12 Technology | NVIDIA](https://www.nvidia.com/en-us/geforce/technologies/dx12/)

[AMD DirectX® 12 (DX12) Technology | AMD](https://www.amd.com/en/technologies/directx12)

[Top Microsoft DirectX Courses Online | Udemy](https://www.udemy.com/topic/microsoft-directx/)

[DirectX - Learn Microsoft DirectX from Scratch Course | Udemy](https://www.udemy.com/course/directx-learn-microsoft-directx-from-scratch/)

[DirectX 11 Programming Course | Udemy](https://www.udemy.com/course/directx11/)

## DirectX Tools, Libraries, and Frameworks

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[DirectX-Graphics-Samples](https://github.com/Microsoft/DirectX-Graphics-Samples) is a project that contains the DirectX 12 Graphics samples that demonstrate how to build graphics intensive applications for Windows 10.

[PIX on Windows](https://devblogs.microsoft.com/pix/documentation/) is a performance tuning and debugging tool for DirectX 12 games on Windows.

[DirectStorage API](https://devblogs.microsoft.com/directx/directstorage-is-coming-to-pc/) is an API in the DirectX family originally designed for the [Velocity Architecture](https://news.xbox.com/en-us/2020/07/14/a-closer-look-at-xbox-velocity-architecture/) to Windows. The DirectX API is architected in a way that takes all this into account and maximizes performance throughout the entire pipeline from NVMe drive all the way to the GPU. It does this in several ways: by reducing per-request NVMe overhead, enabling batched many-at-a-time parallel IO requests which can be efficiently fed to the GPU, and giving games finer grain control over when they get notified of IO request completion instead of having to react to every tiny IO completion. The DirectStorage API will be available on [Windows 11](https://www.microsoft.com/en-us/windows/windows-11) PCs with NVMe SSDs, but will also be support in [Windows 10](https://www.microsoft.com/software-download/windows10) version 1909 and newer.

[NVIDIA® Nsight™ Visual Studio Edition](https://developer.nvidia.com/nsight-visual-studio-edition) is an application development environment for heterogeneous platforms which brings GPU computing into Microsoft Visual Studio. NVIDIA Nsight™ VSE allows you to build and debug integrated GPU kernels and native CPU code as well as inspect the state of the GPU and memory.

[NVRHI (NVIDIA Rendering Hardware Interface)](https://github.com/NVIDIAGameWorks/nvrhi) is a library that implements a common abstraction layer over multiple graphics APIs (GAPIs): Direct3D 11, Direct3D 12, and Vulkan 1.2. It works on Windows (x64 only) and Linux (x64 and ARM64).

[RTXMU - RTX Memory Utility SDK](https://github.com/NVIDIAGameWorks/RTXMU) is an SDK tool that batchs up all of the acceleration structure build inputs and pass them to RTXMU which in turn will perform all the suballocation memory requests and build details including compaction. Then post build info is abstracted away by the SDK in order to do compaction under the hood. RTXMU returns acceleration structure handle ids that are used to reference the underlying memory buffers. These handle ids are passed into RTXMU to create compaction copy workloads, deallocate unused build resources or remove all memory associated with an acceleration structure.

[Radeon™ GPU Profiler](https://gpuopen.com/rgp/) is a performance tool that can be used by developers to optimize DirectX®12, Vulkan® and OpenCL™ applications for AMD RDNA™ and GCN hardware.

[Radeon™ GPU Analyzer](https://gpuopen.com/rga/) is a compiler and code analysis tool for Vulkan®, DirectX®, OpenGL® and OpenCL™.

[Radeon™ Memory Visualizer (RMV)](https://gpuopen.com/rmv/) is a tool provided by AMD for use by game engine developers. It allows engineers to examine, diagnose, and understand the GPU memory management within their projects.

[FNA](https://fna-xna.github.io/) is an XNA4 reimplementation that focuses solely on developing a fully accurate XNA4 runtime for the desktop.

[FAudio](https://fna-xna.github.io/) is an XAudio reimplementation that focuses solely on developing fully accurate DirectX Audio runtime libraries for the FNA project, including [XAudio2](https://docs.microsoft.com/en-us/windows/win32/xaudio2/xaudio2-introduction), [X3DAudio](https://docs.microsoft.com/en-us/windows/win32/xaudio2/x3daudio-overview), [XAPO](https://docs.microsoft.com/en-us/windows/win32/xaudio2/xapo-overview), and [XACT3](https://en.wikipedia.org/wiki/Cross-platform_Audio_Creation_Tool).

[Simple DirectMedia Layer](https://www.libsdl.org/) is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog.

[DXVK](https://github.com/doitsujin/dxvk) is a Vulkan-based translation layer for Direct3D 9/10/11 which allows running 3D applications on Linux using Wine.

[VKD3D-Proton](https://github.com/HansKristian-Work/vkd3d-proton) is a fork of VKD3D, which aims to implement the full Direct3D 12 API on top of Vulkan.

[RenderDoc](https://renderdoc.org) is a stand-alone graphics debugger that allows quick and easy single-frame capture and detailed introspection of any application using Vulkan, D3D11, OpenGL & OpenGL ES or D3D12 across Windows, Linux, Android, Stadia, or Nintendo Switch™.

# Computer Vision Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/129494417-b0ee8192-ac41-4a6d-8e1d-4761ffc8bab1.png">
  <br />
</p>

## Computer Vision Learning Resources

[Computer Vision](https://azure.microsoft.com/en-us/overview/what-is-computer-vision/) is a field of Artificial Intelligence (AI) that focuses on enabling computers to identify and understand objects and people in images and videos.

[OpenCV Courses](https://opencv.org/courses/)

[Exploring Computer Vision in Microsoft Azure](https://docs.microsoft.com/en-us/learn/paths/explore-computer-vision-microsoft-azure/)

[Top Computer Vision Courses Online | Coursera](https://www.coursera.org/courses?languages=en&query=computer%20vision)

[Top Computer Vision Courses Online | Udemy](https://www.udemy.com/topic/computer-vision/)

[Learn Computer Vision with Online Courses and Lessons | edX](https://www.edx.org/learn/computer-vision)

[Computer Vision and Image Processing Fundamentals | edX](https://www.edx.org/course/computer-vision-and-image-processing-fundamentals)

[Introduction to Computer Vision Courses | Udacity](https://www.udacity.com/course/introduction-to-computer-vision--ud810)

[Computer Vision Nanodegree program | Udacity](https://www.udacity.com/course/computer-vision-nanodegree--nd891)

[Machine Vision Course |MIT Open Courseware ](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-801-machine-vision-fall-2004/)

[Computer Vision Training Courses | NobleProg](https://www.nobleprog.com/computer-vision-training)

[Visual Computing Graduate Program | Stanford Online](https://online.stanford.edu/programs/visual-computing-graduate-program)

## Computer Vision Tools, Libraries, and Frameworks

[OpenCV](https://opencv.org) is a highly optimized library with focus on real-time computer vision applications. The C++, Python, and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Microsoft Cognitive Toolkit (CNTK)](https://docs.microsoft.com/en-us/cognitive-toolkit/) is an open-source toolkit for commercial-grade distributed deep learning. It describes neural networks as a series of computational steps via a directed graph. CNTK allows the user to easily realize and combine popular model types such as feed-forward DNNs, convolutional neural networks (CNNs) and recurrent neural networks (RNNs/LSTMs). CNTK implements stochastic gradient descent (SGD, error backpropagation) learning with automatic differentiation and parallelization across multiple GPUs and servers.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a Python module for machine learning built on top of SciPy, NumPy, and matplotlib, making it easier to apply robust and simple implementations of many popular machine learning algorithms.

[NVIDIA cuDNN](https://developer.nvidia.com/cudnn) is a GPU-accelerated library of primitives for [deep neural networks](https://developer.nvidia.com/deep-learning). cuDNN provides highly tuned implementations for standard routines such as forward and backward convolution, pooling, normalization, and activation layers. cuDNN accelerates widely used deep learning frameworks, including [Caffe2](https://caffe2.ai/), [Chainer](https://chainer.org/), [Keras](https://keras.io/), [MATLAB](https://www.mathworks.com/solutions/deep-learning.html), [MxNet](https://mxnet.incubator.apache.org/), [PyTorch](https://pytorch.org/), and [TensorFlow](https://www.tensorflow.org/).

[Automated Driving Toolbox™](https://www.mathworks.com/products/automated-driving.html) is a MATLAB tool that provides algorithms and tools for designing, simulating, and testing ADAS and autonomous driving systems. You can design and test vision and lidar perception systems, as well as sensor fusion, path planning, and vehicle controllers. Visualization tools include a bird’s-eye-view plot and scope for sensor coverage, detections and tracks, and displays for video, lidar, and maps. The toolbox lets you import and work with HERE HD Live Map data and OpenDRIVE® road networks. It also provides reference application examples for common ADAS and automated driving features, including FCW, AEB, ACC, LKA, and parking valet. The toolbox supports C/C++ code generation for rapid prototyping and HIL testing, with support for sensor fusion, tracking, path planning, and vehicle controller algorithms.

[LRSLibrary](https://github.com/andrewssobral/lrslibrary) is a Low-Rank and Sparse Tools for Background Modeling and Subtraction in Videos. The library was designed for moving object detection in videos, but it can be also used for other computer vision and machine learning problems.

[Image Processing Toolbox™](https://www.mathworks.com/products/image.html) is a tool that provides a comprehensive set of reference-standard algorithms and workflow apps for image processing, analysis, visualization, and algorithm development. You can perform image segmentation, image enhancement, noise reduction, geometric transformations, image registration, and 3D image processing.

[Computer Vision Toolbox™](https://www.mathworks.com/products/computer-vision.html) is a tool that provides algorithms, functions, and apps for designing and testing computer vision, 3D vision, and video processing systems. You can perform object detection and tracking, as well as feature detection, extraction, and matching. You can automate calibration workflows for single, stereo, and fisheye cameras. For 3D vision, the toolbox supports visual and point cloud SLAM, stereo vision, structure from motion, and point cloud processing.

[Statistics and Machine Learning Toolbox™](https://www.mathworks.com/products/statistics.html) is a tool that provides functions and apps to describe, analyze, and model data. You can use descriptive statistics, visualizations, and clustering for exploratory data analysis; fit probability distributions to data; generate random numbers for Monte Carlo simulations, and perform hypothesis tests. Regression and classification algorithms let you draw inferences from data and build predictive models either interactively, using the Classification and Regression Learner apps, or programmatically, using AutoML.

[Lidar Toolbox™](https://www.mathworks.com/products/lidar.html) is a tool that provides algorithms, functions, and apps for designing, analyzing, and testing lidar processing systems. You can perform object detection and tracking, semantic segmentation, shape fitting, lidar registration, and obstacle detection. Lidar Toolbox supports lidar-camera cross calibration for workflows that combine computer vision and lidar processing.

[Mapping Toolbox™](https://www.mathworks.com/products/mapping.html) is a tool that provides algorithms and functions for transforming geographic data and creating map displays. You can visualize your data in a geographic context, build map displays from more than 60 map projections, and transform data from a variety of sources into a consistent geographic coordinate system.

[UAV Toolbox](https://www.mathworks.com/products/uav.html) is an application that provides tools and reference applications for designing, simulating, testing, and deploying unmanned aerial vehicle (UAV) and drone applications. You can design autonomous flight algorithms, UAV missions, and flight controllers. The Flight Log Analyzer app lets you interactively analyze 3D flight paths, telemetry information, and sensor readings from common flight log formats.

[Parallel Computing Toolbox™](https://www.mathworks.com/products/matlab-parallel-server.html) is a tool that lets you solve computationally and data-intensive problems using multicore processors, GPUs, and computer clusters. High-level constructs such as parallel for-loops, special array types, and parallelized numerical algorithms enable you to parallelize MATLAB® applications without CUDA or MPI programming. The toolbox lets you use parallel-enabled functions in MATLAB and other toolboxes. You can use the toolbox with Simulink® to run multiple simulations of a model in parallel. Programs and models can run in both interactive and batch modes.

[Partial Differential Equation Toolbox™](https://www.mathworks.com/products/pde.html) is a tool that provides functions for solving structural mechanics, heat transfer, and general partial differential equations (PDEs) using finite element analysis.

[ROS Toolbox](https://www.mathworks.com/products/ros.html) is a tool that provides an interface connecting MATLAB® and Simulink® with the Robot Operating System (ROS and ROS 2), enabling you to create a network of ROS nodes. The toolbox includes MATLAB functions and Simulink blocks to import, analyze, and play back ROS data recorded in rosbag files. You can also connect to a live ROS network to access ROS messages.

[Robotics Toolbox™](https://www.mathworks.com/products/robotics.html) provides a toolbox that brings robotics specific functionality(designing, simulating, and testing manipulators, mobile robots, and humanoid robots) to MATLAB, exploiting the native capabilities of MATLAB (linear algebra, portability, graphics). The toolbox also supports mobile robots with functions for robot motion models (bicycle), path planning algorithms (bug, distance transform, D*, PRM), kinodynamic planning (lattice, RRT), localization (EKF, particle filter), map building (EKF) and simultaneous localization and mapping (EKF), and a Simulink model a of non-holonomic vehicle. The Toolbox also including a detailed Simulink model for a quadrotor flying robot.

[Deep Learning Toolbox™](https://www.mathworks.com/products/deep-learning.html) is a tool that provides a framework for designing and implementing deep neural networks with algorithms, pretrained models, and apps. You can use convolutional neural networks (ConvNets, CNNs) and long short-term memory (LSTM) networks to perform classification and regression on image, time-series, and text data. You can build network architectures such as generative adversarial networks (GANs) and Siamese networks using automatic differentiation, custom training loops, and shared weights. With the Deep Network Designer app, you can design, analyze, and train networks graphically. It can exchange models with TensorFlow™ and PyTorch through the ONNX format and import models from TensorFlow-Keras and Caffe. The toolbox supports transfer learning with DarkNet-53, ResNet-50, NASNet, SqueezeNet and many other pretrained models.

[Reinforcement Learning Toolbox™](https://www.mathworks.com/products/reinforcement-learning.html) is a tool that provides an app, functions, and a Simulink® block for training policies using reinforcement learning algorithms, including DQN, PPO, SAC, and DDPG. You can use these policies to implement controllers and decision-making algorithms for complex applications such as resource allocation, robotics, and autonomous systems.

[Deep Learning HDL Toolbox™](https://www.mathworks.com/products/deep-learning-hdl.html) is a tool that provides functions and tools to prototype and implement deep learning networks on FPGAs and SoCs. It provides pre-built bitstreams for running a variety of deep learning networks on supported Xilinx® and Intel® FPGA and SoC devices. Profiling and estimation tools let you customize a deep learning network by exploring design, performance, and resource utilization tradeoffs.

[Model Predictive Control Toolbox™](https://www.mathworks.com/products/model-predictive-control.html) is a tool that provides functions, an app, and Simulink® blocks for designing and simulating controllers using linear and nonlinear model predictive control (MPC). The toolbox lets you specify plant and disturbance models, horizons, constraints, and weights. By running closed-loop simulations, you can evaluate controller performance.

[Vision HDL Toolbox™](https://www.mathworks.com/products/vision-hdl.html) is a tool that provides pixel-streaming algorithms for the design and implementation of vision systems on FPGAs and ASICs. It provides a design framework that supports a diverse set of interface types, frame sizes, and frame rates. The image processing, video, and computer vision algorithms in the toolbox use an architecture appropriate for HDL implementations.

[Microsoft AirSim](https://microsoft.github.io/AirSim/lidar.html) is a simulator for drones, cars and more, built on Unreal Engine (with an experimental Unity release). AirSim is open-source, cross platform, and supports [software-in-the-loop simulation](https://www.mathworks.com/help///ecoder/software-in-the-loop-sil-simulation.html) with popular flight controllers such as PX4 & ArduPilot and [hardware-in-loop](https://www.ni.com/en-us/innovations/white-papers/17/what-is-hardware-in-the-loop-.html) with PX4 for physically and visually realistic simulations. It is developed as an Unreal plugin that can simply be dropped into any Unreal environment. AirSim is being developed  as a platform for AI research to experiment with deep learning, computer vision and reinforcement learning algorithms for autonomous vehicles.

# Photogrammetry Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/129494677-0341843b-c78c-4027-8a2c-43e98a995f6f.png">
  <br />
</p>

## Photogrammetry Learning Resources

[Photogrammetry](https://www.autodesk.com/solutions/photogrammetry-software) is the art and science of extracting 3D information from photographs. The process involves taking overlapping photographs of an object, structure, or space, and converting them into 2D or 3D digital models. Photogrammetry is often used by surveyors, architects, engineers, and contractors to create topographic maps, meshes, point clouds, or drawings based on the real-world.

[Aerial photogrammetry](https://www.autodesk.com/solutions/photogrammetry-software) is process of utilizing aircrafts to produce aerial photography that can be turned into a 3D model or mapped digitally. Now, it is possible to do the same work with a drone.

[Terrestrial(Close-range) photogrammetry](https://www.autodesk.com/solutions/photogrammetry-software) is when images are captured using a handheld camera or with a camera mounted to a tripod. The output of this method is not to create topographic maps, but rather to make 3D models of a smaller object.

[Top Photogrammetry Courses Online | Udemy](https://www.udemy.com/topic/photogrammetry/)

[Photogrammetry With Drones: In Mapping Technology | Udemy](https://www.udemy.com/course/essentials-of-photogrammetry/)

[Introduction to Photogrammetry Course | Coursera](https://www.coursera.org/lecture/aerial-photography-with-uav/introduction-to-photogrammetry-KyP30)

[Photogrammetry Online Classes and Training | Linkedin Learning](https://www.linkedin.com/learning/search?keywords=Photogrammetry&upsellOrderOrigin=default_guest_learning&trk=learning-course_learning-search-bar_search-submit)

[Pix4D training and certification for mapping professionals](https://training.pix4d.com/)

[Drone mapping and photogrammetry workshops with Pix4D](https://training.pix4d.com/pages/workshops)

[Digital Photogrammetric Systems Course | Purdue Online Learning](https://engineering.purdue.edu/online/courses/digital-photogrammetric-systems)

[Photogrammetry Training | Deep3D Photogrammetry](https://deep3d.co.uk/photogrammetry-training/)

[ASPRS Certification Program](https://www.asprs.org/certification)

## Photogrammetry Tools, Libraries, and Frameworks

[Autodesk® ReCap™](https://www.autodesk.com/products/recap/free-trial) is a software tool that converts reality captured from laser scans or photos into a 3D model or 2D drawing that's ready to be used in your design built for UAV and drone processes.

[Autodesk® ReCap™ Photo](http://blogs.autodesk.com/recap/introducing-recap-photo/) is a cloud-connected solution tailored for drone/UAV photo capturing workflows. Using ReCap Photo, you can create textured meshes, point clouds with geolocation, and high-resolution orthographic views with elevation maps.

[Pix4D](https://www.pix4d.com/) is a unique suite of photogrammetry software for drone mapping. Capture images with our app, process on desktop or cloud and create maps and 3D models.

[PIX4Dmapper](https://www.pix4d.com/product/pix4dmapper-photogrammetry-software) is the leading photogrammetry software for professional drone mapping.

[RealityCapture](https://www.capturingreality.com/) is a state-of-the-art photogrammetry software solution that creates virtual reality scenes, textured 3D meshes, orthographic projections, geo-referenced maps and much more from images and/or laser scans completely automatically.

[Adobe Scantastic](https://labs.adobe.com/projects/scantastic/) is a tool that makes the creation of 3D assets accessible to everyone. It can be used with just a mobile device (combined with Adobe's server-based photogrammetry pipeline), users can easily scan objects in their physical environment and turn them into 3D models which can then be imported into tools like [Adobe Dimension](https://www.adobe.com/products/dimension.html)  and [Adobe Aero](https://www.adobe.com/products/aero.html).

[Adobe Aero](https://www.adobe.com/products/aero.html) is a tool that helps you build, view, and share immersive AR experiences. Simply build a scene by bringing in 2D images from Adobe Photoshop and Illustrator, or 3D models from Adobe Dimension, Substance, third-party apps like Cinema 4D, or asset libraries like Adobe Stock and TurboSquid. Aero optimizes a wide array of assets, including OBJ, GLB, and glTF files, for AR, so you can visualize them in real time.

[Agisoft Metashape](https://www.agisoft.com/) is a stand-alone software product that performs photogrammetric processing of digital images and generates 3D spatial data to be used in GIS applications, cultural heritage documentation, and visual effects production as well as for indirect measurements of objects of various scales.

[MicroStation](https://www.bentley.com/en/products/brands/microstation) is a CAD software platform for 2D and 3D dimensional design and drafting, developed and sold by Bentley Systems. It generates 2D/3D vector graphics objects and elements and includes building information modeling (BIM) features.

[Leica Photogrammetry Suite (LPS)](https://support.hexagonsafetyinfrastructure.com/infocenter/index?page=product&facRef=LPS&facDisp=Leica%20Photogrammetry%20Suite%20(LPS)&landing=1) is a powerful photogrammetry system that delivers full analytical triangulation, the generation of digital terrain models, orthophoto production, mosaicking, and 3D feature extraction in a user-friendly environment that guarantees results even for photogrammetry novices.

[Terramodel](https://heavyindustry.trimble.com/products/terramodel) is a powerful software package for the surveyor, civil engineer or contractor who requires a CAD and design package with integrated support for raw survey data.

[MicMac](https://github.com/micmacIGN/micmac) is a free and  open-source photogrammetry software tools for 3D reconstruction.

[3DF Zephyr] (https://www.3dflow.net/3df-zephyr-photogrammetry-software/) is a photogrammetry software solution by 3Dflow. It allows you automatically reconstruct 3D models from photos and deal with any 3D reconstruction and scanning challenge. No matter what camera sensor, drone or laser scanner device you are going to use.

[COLMAP](https://colmap.github.io/) is a general-purpose Structure-from-Motion (SfM) and Multi-View Stereo (MVS) pipeline with a graphical and command-line interface. It offers a wide range of features for reconstruction of ordered and unordered image collections.

[Multi-View Environment (MVE)](https://www.gcc.tu-darmstadt.de/home/proj/mve/) is an effort to ease the work with multi-view datasets and to support the development of algorithms based on multiple views. It features Structure from Motion, Multi-View Stereo and Surface Reconstruction. MVE is developed at the TU Darmstadt.

[AliceVision](https://github.com/alicevision/AliceVision) is a Photogrammetric Computer Vision Framework which provides 3D Reconstruction and Camera Tracking algorithms. AliceVision comes up with strong software basis and state-of-the-art computer vision algorithms that can be tested, analyzed and reused.

[Meshroom](https://github.com/alicevision/meshroom) is a free, open-source 3D Reconstruction Software based on the AliceVision framework.

[PhotoModeler](https://www.photomodeler.com/) is a software extracts Measurements and Models from photographs taken with an ordinary camera. A cost-effective way for accurate 2D or 3D measurement, photo-digitizing, surveying, 3D scanning, and reality capture.

[ODM](https://www.opendronemap.org/odm/) is an open source command line toolkit to generate maps, point clouds, 3D models and DEMs from drone, balloon or kite images.

[WebODM](https://www.opendronemap.org/webodm/) is a user-friendly, commercial grade software for drone image processing. Generate georeferenced maps, point clouds, elevation models and textured 3D models from aerial images. It supports multiple engines for processing, currently [ODM](https://github.com/OpenDroneMap/ODM) and [MicMac](https://github.com/dronemapper-io/NodeMICMAC/).

[NodeODM](https://www.opendronemap.org/nodeodm/) is a [standard API specification](https://github.com/OpenDroneMap/NodeODM/blob/master/docs/index.adoc) for processing aerial images with engines such as [ODM](https://github.com/OpenDroneMap/ODM). The API is used by clients such as [WebODM](https://github.com/OpenDroneMap/WebODM), [CloudODM](https://github.com/OpenDroneMap/CloudODM) and [PyODM](https://github.com/OpenDroneMap/PyODM).

[ClusterODM]https://www.opendronemap.org/clusterodm/) is a reverse proxy, load balancer and task tracker with optional cloud autoscaling capabilities for NodeODM API compatible nodes. In a nutshell, it's a program to link together multiple NodeODM API compatible nodes under a single network address.

[FIELDimageR](https://www.opendronemap.org/fieldimager/) is an R package to analyze orthomosaic images from agricultural field trials.

[Regard3D](https://www.regard3d.org/) is a free and open source structure-from-motion program. It converts photos of an object, taken from different angles, into a 3D model of this object.

# Geometric optics
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

    - Reflection and refraction: Geometric optics
    - Mirrors: Geometric optics
    - Lenses

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784685-dfeb8063-7bf2-4420-9610-41c05a0b5d4d.png">
  <br />
</p>

   **Geometric Optics - Raytracing. Source: [sdsu-physics](https://sdsu-physics.org/physics180/physics180B/Topics/light/raytracing.html)**

  <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784688-5ecef6ad-3520-41fd-a206-e675ca3a1f5b.png">
  <br />
   </p>

**Geometric Optics - Reflection. Source: [sdsu-physics](https://sdsu-physics.org/physics180/physics180B/Topics/light/raytracing.html)**

# Autodesk Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687186-060c4b00-d1ca-11eb-9e90-f51a3ebf4e43.png">
  <br />
</p>

## Autodesk Learning Resources

[Autodesk](https://www.autodesk.com/) is a global leader in design and make technology, with expertise across architecture, engineering, construction, design, manufacturing, and entertainment.

[CNC programming (Computer Numerical Control Programming)](https://www.autodesk.com/solutions/cnc-programming) is utilized by manufacturers to create program instructions for computers to control a machine tool. CNC is highly involved in the manufacturing process and improves automation as well as flexibility.

[AutoDesk Learning & Training](https://www.autodesk.com/training)

[Autodesk Certification](https://www.autodesk.com/certification/overview)

[Autodesk University](https://www.autodesk.com/autodesk-university/)

[Autodesk Design Academy](https://academy.autodesk.com/)

[Autodesk Customer Success Hub](https://customersuccess.autodesk.com)

[Software and Services for Education | Autodesk Education](https://www.autodesk.com/education/home)

[AutoDesk Forums](https://forums.autodesk.com)

[AutoDesk Developer Network](https://www.autodesk.com/developer-network/overview)

[Learning Civil 3D on Autodesk Knowledge Network](https://knowledge.autodesk.com/support/civil-3d/learn)

[Top Autodesk Courses on Udemy](https://www.udemy.com/topic/autodesk/)

[Top Autodesk Courses on Coursera](https://www.coursera.org/autodesk)

[Top Autodesk Fusion 360 Courses on Coursera](https://www.coursera.org/courses?query=autodesk%20fusion%20360&page=1)

## Autodesk Tools and Frameworks

[AutoCAD®](https://www.autodesk.com/products/autocad/overview) is computer-aided design (CAD) software that architects, engineers, and construction professionals rely on to create precise 2D and 3D drawings. It also automates tasks such as comparing drawings, counting, adding blocks, creating schedules.

[AutoCAD LT®](https://www.autodesk.com/products/autocad-lt/overview) is a powerful 2D computer-aided design (CAD) software that architects, engineers, construction professionals, and designers rely on to design, draft, and document with precise 2D geometry.

[AutoCAD® Mobile App](https://www.autodesk.com/products/autocad-mobile/overview) is a mobile(smartphone or tablet) version of AutoCAD that has the core design and drafting tools. Work on your CAD drawings anytime, anywhere—even offline.

[AutoCAD® Web App](https://www.autodesk.com/products/autocad-web-app/overview) is a web version of AutoCAD that can edit, create, share, and view CAD drawings in a web browser on any computer.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687196-0ad0ff00-d1ca-11eb-87d8-6a1e806dcd4c.png">
  <br />
</p>

**AutoCAD® with Architecture toolset. Source: [Autodesk](https://www.autodesk.com/products/autocad/overview)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687204-13293a00-d1ca-11eb-806b-57a3526b0b75.png">
  <br />
</p>

**AutoCAD® with  Mechanical toolset. Source: [Autodesk](https://www.autodesk.com/products/autocad/overview)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687201-10c6e000-d1ca-11eb-99b4-90dec581f163.png">
  <br />
</p>

**AutoCAD® with Electrical toolset. Source: [Autodesk](https://www.autodesk.com/products/autocad/overview)**

[Tinkercad®](https://www.tinkercad.com) is a free, easy-to-use app for 3D design, electronics, and coding. It's used by teachers, kids, hobbyists, and designers to imagine, design, and make anything.

[Revit®](https://www.autodesk.com/products/revit/overview) is a  BIM (Building Information Modeling) software to drive efficiency and accuracy across the project lifecycle, from conceptual design, visualization, and analysis to fabrication and construction.

[AEC(Architecture, Engineering & Construction) Collection®](https://www.autodesk.com/collections/architecture-engineering-construction/overview) is a set of BIM and CAD tools for designers, engineers, and contractors that is supported by a cloud-based common data environment that facilitates project delivery from early-stage design through to construction.

[Fusion 360®](https://www.autodesk.com/products/fusion-360/overview) is an integrated CAD, CAM, CAE, and PCB software application. It unifies design, engineering, electronics, and manufacturing into a single software platform.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687501-98f9b500-d1cb-11eb-807b-20d24da14fc1.png">
  <br />
</p>

**Autodesk® Fusion 360. Source: [Autodesk](https://www.autodesk.com/products/fusion-360/features#)**

[Fusion 360 with FeatureCAM®](https://www.autodesk.com/products/featurecam/overview) is a tool that gives you access to FeatureCAM Ultimate, PartMaker, Fusion 360, Fusion Team, and HSMWorks. With FeatureCAM CNC programming software uses manufacturing knowledge to intelligently make decisions, produce results, and remove repetitive processes.

[Fusion 360 with Netfabb®](https://www.autodesk.com/products/netfabb/overview) is a software that offers a complete toolset for design and implementation for additive manufacturing. It streamlines workflows and automates processes around 3D print preparation. The software also includes access to Fusion 360, Fusion 360 Team, and additional capabilities through Fusion 360 Additive Extensions.

[Fusion 360 Manage](https://www.autodesk.com/products/fusion-360-manage/overview) is a product lifecycle management platform that connects your people, processes, and data across departments and geographies. It gives you the flexibility to start today and expand tomorrow with PLM that adapts to your business.

[Fusion Team](https://fusionteam.autodesk.com/) is a cloud-based coll tool that helps eliminate the inefficiencies that disparate tools create when working with your internal and external teams.

[Fusion 360 with PowerInspect®](https://www.autodesk.com/products/powerinspect/overview) is a 3D measurement software offers a powerful way to inspect, validate, and manage quality for all measurement equipment. Now includes access to Fusion 360, Fusion 360 Team, and Fusion 360 – Machining Extension. PowerInspect includes comprehensive inspection tools that measure parts while they’re still in On Machine Verification (OMV). Machine tool probing helps you make informed scrap or rework decisions quickly.

[Fusion 360 with PowerMill® CAM](https://www.autodesk.com/products/powermill/overview) is a software provides expert CNC programming strategies for complex 3 and 5-axis manufacturing. This includes access to Fusion 360 and advanced manufacturing capabilities through Fusion 360 extensions.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687213-1f14fc00-d1ca-11eb-931e-79c7c5c58ce9.png">
  <br />
</p>

**CNC machining with Fusion 360 with PowerMill® CAM. Source: [Autodesk](https://www.autodesk.com/products/powermill/overview)**

[Fusion 360 with PowerShape®](https://www.autodesk.com/products/powershape/overview) is a  manufacturing CAD software combines surface, solid, and mesh modeling to help prepare molds, dies, and other complex parts for manufacture. This includes access to Fusion 360 and Fusion 360 Team.

[Autodesk PartMaker®](https://www.autodesk.com/solutions/manufacturing-software/swiss-machining) is a software that can produce CNC programs that drive main and sub-spindle machining operations. These can be used for turning, indexed and interpolated C-axis milling, Y-axis, and B-axis milling.

[Robot Structural Analysis Professional](https://www.autodesk.com/products/robot-structural-analysis/overview) is a structural load analysis software that verifies code compliance and uses BIM-integrated workflows to exchange data with Revit. It can help you to create more resilient, constructible designs that are accurate, coordinated, and connected to BIM.

[Revit LT™](https://www.autodesk.com/products/revit-lt/overview) is a software that provides the most cost-effective BIM (Building Information Modeling) solution, you can produce high-quality 3D architectural designs and documentation.

[Maya®](https://www.autodesk.com/products/maya/overview) is a 3D computer animation, modeling, simulation, and rendering software that can create realistic effects from explosions to cloth simulation.

[Maya LT™](https://www.autodesk.com/products/maya-lt/overview) is a game design software for indie game makers that can create and animate realistic-looking characters, props, and environments using the sophisticated 3D modeling and animation tools.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687226-2a682780-d1ca-11eb-9408-4b32ddc7d493.png">
  <br />
</p>

**Autodesk® Maya. Source:[Autodesk](https://www.autodesk.com/products/maya/overview)**

[3DS Max®](https://www.autodesk.com/products/3ds-max/overview) is a 3D modeling and rendering software for design visualization, games, and animation.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687233-3358f900-d1ca-11eb-8e9c-0cb68b16db0e.png">
  <br />
</p>

**Autodesk® 3DS Max. Source:[Autodesk](https://www.autodesk.com/products/3ds-max/overview)**

[Arnold](https://www.autodesk.com/products/arnold/overview) is an advanced Monte Carlo ray tracing(Global illumination) renderer that helps you work more efficiently.

[ReCap™](https://www.autodesk.com/products/recap/overview) is a Pro 3D scanning software to transform the physical world into a digital asset. With reality capture data you can better understand and verify existing and as-built conditions to gain insights and make better decisions.

[Flame®](https://www.autodesk.com/products/flame/overview) is a 3D VFX and finishing software provides powerful tools for 3D compositing, visual effects, and editorial finishing. An integrated, creative environment means faster compositing, advanced graphics, color correction, and more.

[Mudbox®](https://www.autodesk.com/products/mudbox/overview) is a 3D digital painting and sculpting software that let's you sculpt and paint highly detailed 3D geometry and textures.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687228-2e944500-d1ca-11eb-894e-b55e15c35620.png">
  <br />
</p>

**Autodesk® Mudbox. Source:[Autodesk](https://www.autodesk.com/products/mudbox/overview)**

[Character Generator®](https://www.autodesk.com/products/character-generator/overview) is a powerful 3D design and animation tools, Character Generator offers artists a web-based laboratory to create fully rigged 3D characters for animation packages and game engines.

[Smoke®](https://www.autodesk.com/products/smoke/overview) is a  video effects software helps production studios increase productivity by combining editing workflows with node-based compositing tools in a timeline-centered editing environment.

[ShotGrid](https://www.autodesk.com/products/shotgrid/overview) formerly Shotgun Software, is software for creative project management software and review tools for film, TV, and games that streamlines workflows for creative studios.

[Advance Steel®](https://www.autodesk.com/products/advance-steel/overview) is a 3D modeling software for steel detailing, design, fabrication, and construction. it connects engineers and detailers through a seamless design and detailing workflow between Advance Steel and Revit, you can reduce the time required to move from design to fabrication while simultaneously reducing errors along the way.

[Media & Entertainment Collection®](https://www.autodesk.com/collections/media-entertainment/overview) is a collection that includes all of the tools you need to build a powerful and scalable 3D animation pipeline for complex simulations, effects, and rendering.

[Civil 3D®](https://www.autodesk.com/products/civil-3d/overview) is a  civil engineering design software supports BIM (Building Information Modeling) with integrated features to improve drafting, design, and construction documentation.

[Inventor®](https://www.autodesk.com/products/inventor/overview) is a  CAD software that provides professional-grade 3D mechanical design, documentation, and product simulation tools. Work efficiently with a powerful blend of parametric, direct, freeform, and rules-based design capabilities.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687217-24724680-d1ca-11eb-9768-0fbcba5a0d41.png">
  <br />
</p>

**Autodesk® Inventor. Source:[Autodesk](https://www.autodesk.com/products/inventor/overview)**

[Inventor® CAM](https://www.autodesk.com/products/inventor-cam/overview) is an integrated CAM software for Inventor that simplifies CNC programming processes. Such as the machining workflow with CAD-embedded 2.5-axis to 5-axis milling, turning, and mill-turn capabilities.

[Inventor Nastran®](https://www.autodesk.com/products/inventor-nastran/overview) is a CAD-embedded finite element analysis software that delivers finite element analysis (FEA) tools for engineers and analysts. Simulation covers multiple analysis types, such as linear and nonlinear stress, dynamics, and heat transfer.

[Inventor® Nesting](https://www.autodesk.com/products/inventor-nesting/overview) is a CAD-embedded, true-shape nesting tools for Inventor that helps you optimize yield from flat raw material. Easily compare nesting studies to optimize efficiency and reduce costs, and export 3D models or DXF™ files of the completed nest for cutting path generation.

[Inventor Tolerance Analysis®](https://www.autodesk.com/products/inventor-tolerance-analysis/overview) is an CAD-embedded tolerance stackup analysis software that is designed to help Inventor users make more informed decisions while specifying manufacturing tolerances.

[Product Design & Manufacturing Collection](https://www.autodesk.com/collections/product-design-manufacturing/overview) is an integrated set of professional-grade applications that connect everyone, from concept to production, with shared tools to streamline your product development process.

[Navisworks®](https://www.autodesk.com/products/navisworks/overview) is a project review software to improve BIM (Building Information Modeling) coordination. That can combine design and construction data into a single model.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687230-2f2cdb80-d1ca-11eb-9bcf-5dc2fb858d7d.png">
  <br />
</p>

**Autodesk® Navisworks. Source:[Autodesk](https://www.autodesk.com/products/navisworks/overview)**

[BIM Collaborate](https://www.autodesk.com/products/bim-collaborate/overview) is cloud-based design collaboration and coordination software that connects AEC teams, helping you execute on design intent and deliver high-quality constructible models on a single platform.

[BIM Collaborate Pro](https://www.autodesk.com/products/bim-collaborate/overview) is cloud-based design collaboration and coordination software that connects AEC teams, helping you execute on design intent and deliver high-quality constructible models on a single platform.

[InfraWorks®](https://www.autodesk.com/products/infraworks/overview) is a conceptual design software lets architecture, engineering, and construction professionals model, analyze, and visualize infrastructure design concepts within the context of the built and natural environment—improving decision making and accelerating project approvals.

[SketchBook®](https://www.autodesk.com/products/sketchbook/overview) is a drawing and painting software lets designers, architects, and concept artists sketch ideas quickly and create stunning illustrations.

[Alias®](https://www.autodesk.com/products/alias-products/overview) is a product design software for sketching, concept modeling, surfacing, visualization. It can create and reuse templates across design and surfacing teams sharing surfacing language.

[Assemble BIM Data](https://construction.autodesk.com/products/assemble/) is a tool that helps keep projects on track. Along with condition and connect BIM data to design reviews, estimating, change management, scheduling, work-in-place tracking, and more.

[Autodesk® Forge](https://forge.autodesk.com) is a cloud-based developer platform from Autodesk. That let's you access design and engineering data in the cloud with the Forge platform. Whether you want to automate processes, connect teams and workflows, or visualize your data using Forge APIs.

[Autodesk® Rendering](https://www.autodesk.com/products/rendering/overview) is a fast, high-resolution cloud rendering software that let's you produce stunning, high-quality renderings from designs and models with cloud rendering. This service uses cloud credits, which is a universal measure across Autodesk consumption-based cloud services to perform certain tasks in the cloud.

[Autodesk® CFD](https://www.autodesk.com/products/cfd/overview) is a computational fluid dynamics simulation software that engineers and analysts use to intelligently predict how liquids and gases will perform. It helps to minimize the need for physical prototypes while providing deeper insight into fluid flow design performance.

[Autodesk® Drive](https://www.autodesk.com/subscription/drive) is a way to securely store, preview, and share your 2D and 3D design data.

[Autodesk® Viewer](https://www.autodesk.com/viewers) is a tool that supports most 2D and 3D files, including DWG, STEP, DWF, RVT, and Solidworks, and works with over 80 file types on any device. Get the feedback you need with Autodesk Viewer’s annotation and drawing tools for easy online collaboration.

[Autodesk BIM 360®](https://www.autodesk.com/bim-360/) is a tool is part of the Autodesk Construction Cloud, connecting workflows, teams, and data to help you build better.

[Autodesk® Build](https://construction.autodesk.com/products/autodesk-build/) is a construction management software for field execution and project management that empowers you to seamlessly collaborate and deliver construction projects on time, on budget.

[Autodesk® Takeoff](https://construction.autodesk.com/products/autodesk-takeoff/) is a tool that helps you work with competitive bids that are generated from accurate estimates produced from integrated 2D takeoffs and 3D quantities.

[BuildingConnected](https://www.buildingconnected.com) is the argest real-time construction network that connects owners and builders through an easy-to-use platform to streamline the bid and risk management process.

[Bid Board Pro](https://www.buildingconnected.com/bid-board/) is a tool that helps you see all bid invites across your entire office or division from one place. Know what needs to get done, who’s responsible for it and when it’s due. Track project files, deadlines and more during each stage of the bidding process.

[TradeTapp](https://www.buildingconnected.com/tradetapp/) is a tool that helps you significantly decrease the time it takes to analyze subcontractor risk, annually or for a specific project. Advanced risk profiles enable a streamlined process and offer financial benchmarking, key metric calculations, capacity recommendations and safety performance history.

[Design Review](https://www.autodesk.com/products/design-review/overview) is a CAD viewer software lets you view, mark up, print, and track changes to 2D and 3D files for free—without the original design software. Work with a variety of file formats, including: DWF, DWFx, DWG, and DXF (requires installation of [free DWG TrueView software](https://www.autodesk.com/products/dwg/viewers)); Adobe PDF; as well as image file types such as.bmp, .jpg, .gif, .pcx, .pct, .png, .rlc, .tga, .tif, .mil, .cal, and more.

[EAGLE](https://www.autodesk.com/products/eagle/overview) is electronic design automation (EDA) software that lets printed circuit board (PCB) designers seamlessly connect schematic diagrams, component placement, PCB routing, and comprehensive library content.

[Fabrication ESTmep™, CADmep™, and CAMduct™](https://www.autodesk.com/products/fabrication/overview) is a software that provides an integrated set of tools for MEP specialty contractors to estimate, detail, and drive fabrication of mechanical building systems. Also, create high LOD models of piping, plumbing, or ductwork systems in AutoCAD using CADmep. Content libraries used in ESTmep, CADmep, and CAMduct can also be used in Revit to support BIM workflows. Available stand-alone or in the Architecture, Engineering & Construction Collection..

[Formit](https://www.autodesk.com/products/formit/overview) is an architectural modeling software for BIM-based 3D sketching. The pro version of FormIt includes the tools in the FormIt app, plus Dynamo computation, and collaboration and analysis features.

[Helius Composite](https://www.autodesk.com/products/helius-composite/overview) is a tool that can help you simulate the material behavior of compound components. Built-in solvers minimize the need to have secondary finite element analysis (FEA) software to analyze material characteristics more quickly.

[Helius PFA](https://www.autodesk.com/products/helius-pfa/overview) is a progressive failure analysis software that predicts failure stages of composite materials. Helius PFA enables you to integrate composite and elastomeric material properties into your finite element analysis (FEA) program.

[HSMWorks](https://www.autodesk.com/products/hsmworks/overview) is an ambedded CAM software for [SOLIDWORKS®](https://www.solidworks.com/) to design and generate CAM toolpaths without the hassle of changing software. Reduce cycle time and rework with CAD-embedded 2.5 to 5-axis milling, turning, and mill-turn capabilities. HSMWorks is included with your Fusion 360 subscription.

[Insight](https://www.autodesk.com/products/insight/overview) is a building performance analysis software that empowers architects and engineers to design more energy-efficient buildings with advanced simulation engines and building performance analysis data integrated in Revit.

[Moldflow®](https://www.autodesk.com/products/moldflow/overview) is a software tool that lets you troubleshoot problems with plastic injection and compression molding for design and manufacturing. Advanced tools and a simplified user interface help you address manufacturing challenges, such as part warpage, cooling channel efficiency, and cycle time reduction.

[MotionBuilder®](https://www.autodesk.com/products/motionbuilder/overview) is a 3D character animation software. Work in an interactive environment optimized to help you work faster and more efficiently without compromising creativity.

[PlanGrid Build](https://construction.autodesk.com/products/autodesk-plangrid-build/?pgr=1) is a Construction app built for the field. It allows you to complete tasks from anywhere on the jobsite with seamless access to Autodesk Build data, even when you’re offline.

[Point Layout](https://www.autodesk.com/products/point-layout/overview) is a  construction layout software helps contractors and subcontractors bring model accuracy to the field and back. Connect models to layout and quality workflows. Get direct file format compatibility with robotic total station hardware, including Leica, Topcon, and Trimble.

[Structural Bridge Design®](https://www.autodesk.com/products/structural-bridge-design/overview) is a bridge analysis software for small to medium-span bridges used by engineers to deliver design reports faster.

[Vault®](https://www.autodesk.com/products/vault/overview) is a product data management (PDM) software helps streamline workflows. Everyone works from a central source of organized data—collaborating, reducing errors, and saving time.

[Vehicle Tracking®](https://www.autodesk.com/products/vehicle-tracking/overview) is a swept path analysis and design software to facilitate parking lot layout, roundabout design, and other design challenges impacted by vehicle movement.

[VRED®](https://www.autodesk.com/products/vred/overview) is a 3D visualization software helps automotive designers and engineers create product presentations, design reviews, and virtual prototypes using interactive GPU raytracing and both analytic and cloud-rendering modes.

[Within Medical®](https://www.autodesk.com/products/within-medical/overview) is a 3D printing orthopedic implant design software that enables designers to create medical implants to aid osseointegration.

[Pype](https://construction.autodesk.com/products/pype/) is a tool that helps you reduce project risk and strengthen client relationships by automating processes that are critical for owner satisfaction and contract compliance.

[Pype Closeout](https://pype.io/closeout/) is a tool provides a single portal for closeout documentation management, with digital document collection from subcontractors and powerful reporting dashboards. With subcontractor outreach automated, the Closeout platform ensures contract compliance and helps you get paid faster.

[Pype SmartPlans](https://pype.io/smartplans/) is a tool that locates and extracts all submittals from your uploaded plans automatically. Export product, equipment, and finish schedules into excel with a single click. SmartPlans’ powerful automation uses cutting edge artificial intelligence and machine learning to intelligently read your drawings to extract submittals and schedules.

[CAMplete](https://www.autodesk.com/products/camplete/overview) is a software tool that  provides G-code post-processing, verification, and simulation for different kinds of CNC machinery. Import data from leading CAM software then use proven post-processors and highly accurate 3D machine models, developed in partnership with machine tool builders, to rapidly produce high-quality, collision free NC machining code.

[Vault PLM](https://www.autodesk.com/products/vault-plm/overview) is a tool that combines Vault Professional with Fusion Lifecycle for enterprise-wide collaboration and product lifecycle management.

# LiDAR Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121950812-f5ae2900-cd0e-11eb-8989-9188bd18a68c.png">
  <br />
</p>

## LiDAR Learning Resources
[Back to the Top](https://github.com/mikeroyal/LiDAR-Guide#table-of-contents)

[Introduction to Lidar Course - NOAA](https://coast.noaa.gov/digitalcoast/training/intro-lidar.html)

[Lidar 101:An Introduction to Lidar Technology, Data, and Applications(PDF) - NOAA](https://coast.noaa.gov/data/digitalcoast/pdf/lidar-101.pdf)

[Understanding LiDAR Technologies - GIS Lounge](https://www.gislounge.com/understanding-lidar-technologies/)

[LiDAR University Free Lidar Training Courses on MODUS AI](https://www.modus-ai.com/lidar-university-2/)

[LiDAR | Learning Plan on ERSI](https://www.esri.com/training/catalog/5bccd52a6e9c0f01fb49e85d/lidar/#!)

[Light Detection and Ranging Sensors Course on Coursera](https://www.coursera.org/lecture/state-estimation-localization-self-driving-cars/lesson-1-light-detection-and-ranging-sensors-3NXgp)

[Quick Introduction to Lidar and Basic Lidar Tools(PDF)](https://training.fws.gov/courses/references/tutorials/geospatial/CSP7304/documents/Lidar.pdf)

[LIDAR - GIS Wiki](http://wiki.gis.com/wiki/index.php/Lidar)

[OpenStreetMap Wiki](https://wiki.openstreetmap.org/wiki/Main_Page)

[OpenStreetMap Frameworks](https://wiki.openstreetmap.org/wiki/Frameworks)

## LiDAR Tools & Frameworks

[Light Detection and Ranging (lidar)](https://www.usgs.gov/news/earthword-lidar) is a technology used to create high-resolution models of ground elevation with a vertical accuracy of 10 centimeters (4 inches). Lidar equipment, which includes a laser scanner, a Global Positioning System (GPS), and an Inertial Navigation System (INS), is typically mounted on a small aircraft. The laser scanner transmits brief pulses of light to the ground surface. Those pulses are reflected or scattered back and their travel time is used to calculate the distance between the laser scanner and the ground.  Lidar data is initially collected as a “point cloud” of individual points reflected from everything on the surface, including structures and vegetation. To produce a “bare earth” Digital Elevation Model (DEM), structures and vegetation are stripped away.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121950840-fe9efa80-cd0e-11eb-9a12-57c4799d63b5.png">
  <br />
</p>

**3D Data Visualization of Golden Gate Bridge. Source: [USGS](https://www.usgs.gov/core-science-systems/ngp/tnm-delivery)**

[Mola](https://docs.mola-slam.org/latest/) is a Modular Optimization framework for Localization and mApping (MOLA).

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121950850-01015480-cd0f-11eb-9fa6-1f93d6d87cd1.gif">
  <br />
</p>

**3D LiDAR SLAM from KITTI dataset. Source: [MOLA](https://docs.mola-slam.org/latest/demo-kitti-lidar-slam.html)**

[Lidar Toolbox™](https://www.mathworks.com/products/lidar.html) is a MATLAB tool that provides algorithms, functions, and apps for designing, analyzing, and testing lidar processing systems. You can perform object detection and tracking, semantic segmentation, shape fitting, lidar registration, and obstacle detection. Lidar Toolbox supports lidar-camera cross calibration for workflows that combine computer vision and lidar processing.

[Automated Driving Toolbox™](https://www.mathworks.com/products/automated-driving.html) is a MATLAB tool that provides algorithms and tools for designing, simulating, and testing ADAS and autonomous driving systems. You can design and test vision and lidar perception systems, as well as sensor fusion, path planning, and vehicle controllers. Visualization tools include a bird’s-eye-view plot and scope for sensor coverage, detections and tracks, and displays for video, lidar, and maps. The toolbox lets you import and work with HERE HD Live Map data and OpenDRIVE® road networks. It also provides reference application examples for common ADAS and automated driving features, including FCW, AEB, ACC, LKA, and parking valet. The toolbox supports C/C++ code generation for rapid prototyping and HIL testing, with support for sensor fusion, tracking, path planning, and vehicle controller algorithms.

[Microsoft AirSim](https://microsoft.github.io/AirSim/lidar.html) is a simulator for drones, cars and more, built on Unreal Engine (with an experimental Unity release). AirSim is open-source, cross platform, and supports [software-in-the-loop simulation](https://www.mathworks.com/help///ecoder/software-in-the-loop-sil-simulation.html) with popular flight controllers such as PX4 & ArduPilot and [hardware-in-loop](https://www.ni.com/en-us/innovations/white-papers/17/what-is-hardware-in-the-loop-.html) with PX4 for physically and visually realistic simulations. It is developed as an Unreal plugin that can simply be dropped into any Unreal environment. AirSim is being developed  as a platform for AI research to experiment with deep learning, computer vision and reinforcement learning algorithms for autonomous vehicles.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121950853-02328180-cd0f-11eb-9459-1b31d084bd3f.png">
  <br />
</p>

**3D Autonomous Vehicle Simulation in AirSim. Source: [Microsoft](https://microsoft.github.io/AirSim)**

[LASer(LAS)](https://www.asprs.org/divisions-committees/lidar-division/laser-las-file-format-exchange-activities) is a public file format for the interchange of 3-dimensional point cloud data data between data users. Although developed primarily for exchange of lidar point cloud data, this format supports the exchange of any 3-dimensional x,y,z tuplet. This binary file format is an alternative to proprietary systems or a generic ASCII file interchange system used by many companies. The problem with proprietary systems is obvious in that data cannot be easily taken from one system to another. There are two major problems with the ASCII file interchange. The first problem is performance because the reading and interpretation of ASCII elevation data can be very slow and the file size can be extremely large even for small amounts of data. The second problem is that all information specific to the lidar data is lost. The LAS file format is a binary file format that maintains information specific to the lidar nature of the data while not being overly complex.

[3D point cloud](https://www.onyxscan-lidar.com/point-cloud/) is a set of data points defined in a given three-dimensional coordinates system.. Point clouds can be produced directly by 3D scanner which records a large number of points returned from the external surfaces of objects or earth surface. These data are exchanged between LiDAR users mainly through LAS format files (.las).

[ArcGIS Desktop](https://www.esri.com/en-us/arcgis/products/arcgis-desktop/overview) is powerful and cost-effective desktop geographic information system (GIS) software. It is the essential software package for GIS professionals. ArcGIS Desktop users can create, analyze, manage, and share geographic information so decision-makers can make intelligent, informed decisions.

[USGS 3DEP Lidar Point Cloud Now Available as Amazon Public Dataset](https://www.usgs.gov/news/usgs-3dep-lidar-point-cloud-now-available-amazon-public-dataset)

[National Geospatial Program](https://www.usgs.gov/core-science-systems/national-geospatial-program)

[National Map Data Download and Visualization Services](https://www.usgs.gov/core-science-systems/ngp/tnm-delivery)

[USGS Lidar Base Specification(LBS) online edition](https://www.usgs.gov/core-science-systems/ngp/ss/lidar-base-specification-online)

# Linear Algebra
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124998626-9a1b4680-e001-11eb-9a49-1e97604e8a10.png">
  <br />
</p>

# Linear Algebra Learning Resources

[Linear algebra](https://en.wikipedia.org/wiki/Linear_algebra) is the math of vectors and matrices. The only prerequisite for this guide is a basic understanding of high school math concepts like numbers, variables, equations, and the fundamental arithmetic operations on real numbers: addition (denoted +), subtraction (denoted −), multiplication (denoted implicitly), and division (fractions). Also, you should also be familiar with functions that take real numbers as inputs and give real numbers as outputs, f : R → R.

[Linear Algebra - Online Courses | Harvard University](https://online-learning.harvard.edu/course/linear-algebra)

[Linear Algebra | MIT Open Learning Library](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+18.06SC+2T2019/about)

[Linear Algebra - Khan Academy](https://www.khanacademy.org/math/linear-algebra)

[Top Linear Algebra Courses on Coursera](https://www.coursera.org/courses?query=linear%20algebra)

[Mathematics for Machine Learning: Linear Algebra on Coursera](https://www.coursera.org/learn/linear-algebra-machine-learning)

[Top Linear Algebra Courses on Udemy](https://www.udemy.com/topic/linear-algebra/)

[Learn Linear Algebra with Online Courses and Classes on edX](https://www.edx.org/learn/linear-algebra)

[The Math of Data Science: Linear Algebra Course on edX](https://www.edx.org/course/math-of-data-science-linear-algebra)

[Linear Algebra in Twenty Five Lectures | UC Davis](https://www.math.ucdavis.edu/~linear/linear.pdf)

[Linear Algebra | UC San Diego Extension](https://extension.ucsd.edu/courses-and-programs/linear-algebra-1)

[Linear Algebra for Machine Learning | UC San Diego Extension](https://extension.ucsd.edu/courses-and-programs/linear-algebra-for-machine-learning)

[Introduction to Linear Algebra, Interactive Online Video | Wolfram](http://www.wolfram.com/wolfram-u/introduction-to-linear-algebra/)

[Linear Algebra Resources | Dartmouth](https://math.dartmouth.edu/~trs/linear-algebra-resources.php)

#  Defintions

### i. Vector operations

We now define the math operations for vectors. The operations we can perform on vectors ~u = (u1, u2, u3) and ~v = (v1, v2, v3) are: addition, subtraction, scaling, norm (length), dot product, and cross product:

The dot product and the cross product of two vectors can also be described in terms of the angle θ between the two vectors.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398163-26a7cb00-dcc9-11eb-9b70-3452d50762c5.png">
  <br />
</p>

**Vector Operations. Source: [slideserve](https://www.slideserve.com/krystal/streaming-simd-extension-sse)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124399554-fbc17500-dcd0-11eb-96b0-c31df664425a.png">
  <br />
</p>

**Vector Operations. Source: [pinterest](https://www.pinterest.com/pin/41799102767414798/)**

### ii. Matrix operations

We denote by A the matrix as a whole and refer to its entries as aij .The mathematical operations defined for matrices are the following:

• determinant (denoted det(A) or |A|)
Note that the matrix product is not a commutative operation.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398167-2ad3e880-dcc9-11eb-9455-9b0c3c6171cd.png">
  <br />
</p>

**Matrix Operations. Source: [SDSU Physics](https://sdsu-physics.org/math/pages/435_LA_ch2.html)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398169-2c051580-dcc9-11eb-934a-71c691325062.png">
  <br />
</p>

**Check for modules that allow Matrix Operations. Source: [DPS Concepts](https://dspconcepts.com/forums/audio-weaver-designer/347-check-modules-allow-matrix-operations)**

### iii. Matrix-vector product

The matrix-vector product is an important special case of the matrix product.

There are two fundamentally different yet equivalent ways to interpret the matrix-vector product. In the column picture, (C), the multiplication of the
matrix A by the vector ~x produces a linear combination of the columns of the matrix: ~y = A~x = x1A[:,1] + x2A[:,2], where A[:,1] and A[:,2] are the first and second columns of the matrix A. In the row picture, (R), multiplication of the matrix A by the vector ~x produces a column vector with coefficients equal to the dot products of rows of the matrix with the vector ~x.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398176-36bfaa80-dcc9-11eb-82c9-641f9ddd8563.png">
  <br />
</p>

**Matrix-vector product. Source: [wikimedia](https://commons.wikimedia.org/wiki/File:Matrix_vector_product_qtl1.svg)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398178-38896e00-dcc9-11eb-94c4-2b2fa7499989.png">
  <br />
</p>

**Matrix-vector Product. Source: [mathisfun](https://www.mathsisfun.com/algebra/scalar-vector-matrix.html)**

### iv. Linear transformations

The matrix-vector product is used to define the notion of a linear transformation, which is one of the key notions in the study of linear algebra. Multiplication by a matrix A ∈ R m×n can be thought of as computing a linear transformation TA that takes n-vectors as inputs and produces m-vectors as outputs:

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398182-3fb07c00-dcc9-11eb-815a-d31e591fe218.png">
  <br />
</p>

**Linear Transformations. Source: [slideserve](https://www.slideserve.com/hall-cobb/chap-6-linear-transformations)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398184-40e1a900-dcc9-11eb-90e9-36031124610f.png">
  <br />
</p>

**Elementary matrices for linear transformations in R^2. Source:[Quora](https://www.quora.com/What-is-a-linear-transformation)**

### v. Fundamental vector spaces

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398197-4fc85b80-dcc9-11eb-9abc-3741bda9b63e.png">
  <br />
</p>

**Fundamental theorem of linear algebra for Vector Spaces. Source: [wikimedia](https://en.wikipedia.org/wiki/Fundamental_theorem_of_linear_algebra)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398199-50f98880-dcc9-11eb-8fd0-994dc48f62d6.png">
  <br />
</p>

**Fundamental theorem of linear algebra. Source: [wolfram](https://mathworld.wolfram.com/FundamentalTheoremofLinearAlgebra.html)**

# Computational Linear Algebra

### i. Solving systems of equations

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398355-307dfe00-dcca-11eb-8668-ba037de5aca5.png">
  <br />
</p>

**System of Linear Equations by Graphing. Source: [slideshare](https://www.slideshare.net/JITENDRATHAKOR/systems-of-linear-equations-43550732)**

### ii. Systems of equations as matrix equations

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398360-34118500-dcca-11eb-94eb-81ee66a9dc8a.png">
  <br />
</p>

**Systems of equations as matrix equations. Source: [mathisfun](https://www.mathsisfun.com/algebra/systems-linear-equations-matrices.html?ref=binfind.com%2Fweb)**

# Computing the Inverse of a Matrix

In this section we’ll look at several different approaches for computing the inverse of a matrix. The matrix inverse is unique so no matter which
method we use to find the inverse, we’ll always obtain the same answer.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398409-71761280-dcca-11eb-9add-d105af886569.png">
  <br />
</p>

**Inverse of 2x2 Matrix. Source: [pinterest](https://www.pinterest.com/pin/375276581446966518/)**

### i. Using row operations

One approach for computing the inverse is to use the Gauss–Jordan elimination procedure.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398532-0c6eec80-dccb-11eb-9c82-6a65916fa43a.png">
  <br />
</p>

**Elementray row operations. Source: [YouTube](http://www.youtube.com/watch?v=DH2JSYx52nk)**

### ii. Using elementary matrices

Every row operation we perform on a matrix is equivalent to a leftmultiplication by an elementary matrix.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398426-83f04c00-dcca-11eb-8dde-54deedff30f7.png">
  <br />
</p>

**Elementary Matrices. Source: [SDSU Physics](http://sdsu-physics.org/math/pages/435_LA_ch2.html)**

### iii. Transpose of a Matrix

Finding the inverse of a matrix is to use the Transpose method.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398574-34f6e680-dccb-11eb-8112-ca77aad96004.png">
  <br />
</p>

**Transpose of a Matrix. Source: [slideserve](https://www.slideserve.com/jaimin/matrix-inverse-and-transpose)**

# Other Linear Topics

In this section discuss a number of other important topics of linear algebra.

### i. Basis

Intuitively, a basis is any set of vectors that can be used as a coordinate system for a vector space. You are certainly familiar with the standard basis for the xy-plane that is made up of two orthogonal axes: the x-axis and the y-axis.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398635-a040b880-dccb-11eb-8d5f-0e6ec65b742d.png">
  <br />
</p>

**Basis. Source: [wikimedia](https://en.wikipedia.org/wiki/Basis_(linear_algebra))**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398636-a171e580-dccb-11eb-8a40-8e6a9e24b6af.png">
  <br />
</p>

**Change of Basis. Source: [wikimedia](https://en.wikipedia.org/wiki/Change_of_basis)**

### ii. Matrix representations of linear transformations

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398653-b9e20000-dccb-11eb-8985-1d203f52f131.png">
  <br />
</p>

**Matrix representations of linear transformations. Source: [slideserve](https://www.slideserve.com/sylvie/two-dimensional-geometric-transformations)**

### iii. Dimension and Basis for Vector Spaces

The dimension of a vector space is defined as the number of vectors in a basis for that vector space. Consider the following vector space S = span{(1, 0, 0),(0, 1, 0),(1, 1, 0)}. Seeing that the space is described by three vectors, we might think that S is 3-dimensional. This is not the case, however, since the three vectors are not linearly independent so they don’t form a basis for S. Two vectors are sufficient to describe any vector in S; we can write S = span{(1, 0, 0),(0, 1, 0)}, and we see these two vectors are linearly independent so they form a basis and dim(S) = 2. There is a general procedure for finding a basis for a vector space. Suppose you are given a description of a vector space in terms of m vectors V = span{~v1, ~v2, . . . , ~vm} and you are asked to find a basis for V and the dimension of V. To find a basis for V, you must find a set of linearly independent vectors that span V. We can use the Gauss–Jordan elimination procedure to accomplish this task. Write the vectors ~vi as the rows of a matrix M. The vector space V corresponds to the row space of the matrix M. Next, use row operations to find the reduced row echelon form (RREF) of the matrix M. Since row operations do not change the row space of the matrix, the row space of reduced row echelon form of the matrix M is the same as the row space of the original set of vectors. The nonzero rows in the RREF of the matrix form a basis for vector space V and the numbers of nonzero rows is the dimension of V.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398664-c5352b80-dccb-11eb-866e-61808bcf953d.png">
  <br />
</p>

**Basis and Dimension. Source: [sliderserve](https://www.slideserve.com/kalil/chapter-3-vector-space)**

### iv. Row space, columns space, and rank of a matrix

Recall the fundamental vector spaces for matrices that we defined in Section II-E: the column space C(A), the null space N (A), and the row space R(A). A standard linear algebra exam question is to give you a certain matrix A and ask you to find the dimension and a basis for each of its fundamental spaces. In the previous section we described a procedure based on Gauss–Jordan elimination which can be used “distill” a set of linearly independent vectors which form a basis for the row space R(A). We will now illustrate this procedure with an example, and also show how to use the RREF of the matrix A to find bases for C(A) and N (A).

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398677-d67e3800-dccb-11eb-8052-dfd1b01920fd.png">
  <br />
</p>

**Row space and Column space. Source: [slideshare](https://www.slideshare.net/VishveshJasani/row-space-column-space-null-space-rank-nullity)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398679-d8e09200-dccb-11eb-8707-e340933063d4.png">
  <br />
</p>

**Row space and Column space. Source: [slideshare](http://www.slideshare.net/RonakMachhi/null-space-rank-and-nullity-theorem)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398681-d9792880-dccb-11eb-8c6f-0c483cf860a4.png">
  <br />
</p>

**Rank and Nullity. Source: [slideshare](https://www.slideshare.net/VishveshJasani/row-space-column-space-null-space-rank-nullity)**

### v. Invertible matrix theorem

There is an important distinction between matrices that are invertible and those that are not as formalized by the following theorem. Theorem. For an n×n matrix A, the following statements are equivalent:

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398692-e6961780-dccb-11eb-98d9-dae7199a6365.png">
  <br />
</p>

**Invertible Matrix theorem. Source: [SDSU Physics](https://sdsu-physics.org/math/pages/435_LA_ch2.html)**

### vi. Determinants

The determinant of a matrix, denoted det(A) or |A|, is a special way to combine the entries of a matrix that serves to check if a matrix is invertible or not.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398703-f9105100-dccb-11eb-8d4e-e6db343304ec.png">
  <br />
</p>

**Determinant of a Square Matrix. Source: [stackexchange](https://math.stackexchange.com/questions/1354148/proving-the-formula-for-finding-the-determinant-of-a-square-matrix)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398705-fa417e00-dccb-11eb-8d1f-0cbf01d77f3d.png">
  <br />
</p>

**Determinant of matrix. Source: [onlinemathlearning](https://www.onlinemathlearning.com/matrix-determinants.html)**

### vii. Eigenvalues and eigenvectors

The set of eigenvectors of a matrix is a special set of input vectors for which the action of the matrix is described as a simple scaling. When a matrix is multiplied by one of its eigenvectors the output is the same eigenvector multiplied by a constant A~eλ = λ~eλ. The constant λ is called an eigenvalue of A.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398717-03cae600-dccc-11eb-86f2-72a816b9231a.png">
  <br />
</p>

**Generalized EigenVectors. Source: [YouTube](https://www.youtube.com/watch?v=xyhaYHGZN-w)**

### viii. Linear Regression

[Linear regression](https://en.wikipedia.org/wiki/Linear_regression) is an approach to model the relationship between two variables by fitting a linear equation to observed data. One variable is considered to be an explanatory variable, and the other is considered to be a dependent variable.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398722-0af1f400-dccc-11eb-9ac7-1de7c6e43ff5.png">
  <br />
</p>

**Multiple Linear Regression. Source: [Medium](https://medium.com/@subarna.lamsal1/multiple-linear-regression-sklearn-and-statsmodels-798750747755)**

# Algorithms
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

[Fuzzy logic](https://www.investopedia.com/terms/f/fuzzy-logic.asp) is a heuristic approach that allows for more advanced decision-tree processing and better integration with rules-based programming.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/123861872-858dce80-d8dc-11eb-9a2c-51205d1541e9.png">
  <br />
</p>

**Architecture of a Fuzzy Logic System. Source: [ResearchGate](https://www.researchgate.net/figure/Architecture-of-a-fuzzy-logic-system_fig2_309452475)**

[Support Vector Machine (SVM)](https://web.stanford.edu/~hastie/MOOC-Slides/svm.pdf) is a supervised machine learning model that uses classification algorithms for two-group classification problems.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/123858065-ec5cb900-d8d7-11eb-81c5-c6a8feefa84f.png">
  <br />
</p>

**Support Vector Machine (SVM). Source:[OpenClipArt](https://openclipart.org/detail/182977/svm-support-vector-machines)**

[Neural networks](https://www.ibm.com/cloud/learn/neural-networks) are a subset of machine learning and are at the heart of deep learning algorithms. The name/structure is inspired by the human brain copying the process that biological neurons/nodes signal to one another.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/123858036-e5ce4180-d8d7-11eb-8c52-43d7c7e6e3c4.png">
  <br />
</p>

**Deep neural network. Source: [IBM](https://www.ibm.com/cloud/learn/neural-networks)**

[Convolutional Neural Networks (R-CNN)](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-convolutional-neural-networks) is an object detection algorithm that first segments the image to find potential relevant bounding boxes and then run the detection algorithm to find most probable objects in those bounding boxes.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/123858026-e36be780-d8d7-11eb-9034-8859d6f09490.png">
  <br />
</p>

**Convolutional Neural Networks. Source:[CS231n](https://cs231n.github.io/convolutional-networks/#conv)**

[Recurrent neural networks (RNNs)](https://www.ibm.com/cloud/learn/recurrent-neural-networks) is a type of artificial neural network which uses sequential data or time series data.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/123858062-ebc42280-d8d7-11eb-9252-97e058bda8bd.png">
  <br />
</p>

**Recurrent Neural Networks. Source: [Slideteam](https://www.slideteam.net/recurrent-neural-networks-rnns-ppt-powerpoint-presentation-file-templates.html)**

[Multilayer Perceptrons (MLPs)](https://deepai.org/machine-learning-glossary-and-terms/multilayer-perceptron) is multi-layer neural networks composed of multiple layers of [perceptrons](https://en.wikipedia.org/wiki/Perceptron) with a threshold activation.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/123858053-e8c93200-d8d7-11eb-844c-60463ecf662c.png">
  <br />
</p>

**Multilayer Perceptrons. Source: [DeepAI](https://deepai.org/machine-learning-glossary-and-terms/multilayer-perceptron)**

[Random forest](https://www.ibm.com/cloud/learn/random-forest) is a commonly-used machine learning algorithm, which combines the output of multiple decision trees to reach a single result. A decision tree in a forest cannot be pruned for sampling and therefore, prediction selection. Its ease of use and flexibility have fueled its adoption, as it handles both classification and regression problems.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398881-fe21d000-dccc-11eb-8f5f-0a0730d85d55.png">
  <br />
</p>

**Random forest. Source: [wikimedia](https://community.tibco.com/wiki/random-forest-template-tibco-spotfirer-wiki-page)**

[Decision trees](https://www.cs.cmu.edu/~bhiksha/courses/10-601/decisiontrees/) are tree-structured models for classification and regression.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398883-ffeb9380-dccc-11eb-9adb-66729a353132.png">
  <br />
</p>

***Decision Trees. Source: [CMU](http://www.cs.cmu.edu/~bhiksha/courses/10-601/decisiontrees/)*

[Naive Bayes](https://en.wikipedia.org/wiki/Naive_Bayes_classifier) is a machine learning algorithm that is used solved calssification problems. It's based on applying [Bayes' theorem](https://www.mathsisfun.com/data/bayes-theorem.html) with strong independence assumptions between the features.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398885-00842a00-dccd-11eb-89c1-bd4c1adbf305.png">
  <br />
</p>

**Bayes' theorem. Source:[mathisfun](https://www.mathsisfun.com/data/bayes-theorem.html)**


# Machine Learning
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/96352527-ad077880-1078-11eb-98b7-da1c0586cf0e.png">
  <br />
</p>

<img src="https://user-images.githubusercontent.com/45159366/105645196-dccfd480-5e4e-11eb-95d1-c5eb560b72fd.jpeg">

**Machine Learning/Deep Learning Frameworks.**

## Learning Resources for ML

[Machine Learning](https://www.ibm.com/cloud/learn/machine-learning) is a branch of artificial intelligence (AI) focused on building apps using algorithms that learn from data models and improve their accuracy over time without needing to be programmed.

[Machine Learning by Stanford University from Coursera](https://www.coursera.org/learn/machine-learning)

[AWS Training and Certification for Machine Learning (ML) Courses](https://aws.amazon.com/training/learning-paths/machine-learning/)

[Machine Learning Scholarship Program for Microsoft Azure from Udacity](https://www.udacity.com/scholarships/machine-learning-scholarship-microsoft-azure)

[Microsoft Certified: Azure Data Scientist Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-data-scientist)

[Microsoft Certified: Azure AI Engineer Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-ai-engineer)

[Azure Machine Learning training and deployment](https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/azure-machine-learning)

[Learning Machine learning and artificial intelligence from Google Cloud Training](https://cloud.google.com/training/machinelearning-ai)

[Machine Learning Crash Course for Google Cloud](https://developers.google.com/machine-learning/crash-course/)

[JupyterLab](https://jupyterlab.readthedocs.io/)

[Scheduling Jupyter notebooks on Amazon SageMaker ephemeral instances](https://aws.amazon.com/blogs/machine-learning/scheduling-jupyter-notebooks-on-sagemaker-ephemeral-instances/)

[How to run Jupyter Notebooks in your Azure Machine Learning workspace](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-run-jupyter-notebooks)

[Machine Learning Courses Online from Udemy](https://www.udemy.com/topic/machine-learning/)

[Machine Learning Courses Online from Coursera](https://www.coursera.org/courses?query=machine%20learning&)

[Learn Machine Learning with Online Courses and Classes from edX](https://www.edx.org/learn/machine-learning)

## ML Frameworks, Libraries, and Tools

[TensorFlow](https://www.tensorflow.org) is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.

[Keras](https://keras.io) is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano.It was developed with a focus on enabling fast experimentation. It is capable of running on top of TensorFlow, Microsoft Cognitive Toolkit, R, Theano, or PlaidML.

[PyTorch](https://pytorch.org) is a library for deep learning on irregular input data such as graphs, point clouds, and manifolds. Primarily developed by Facebook's AI Research lab.

[Amazon SageMaker](https://aws.amazon.com/sagemaker/) is a fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning (ML) models quickly. SageMaker removes the heavy lifting from each step of the machine learning process to make it easier to develop high quality models.

[Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/) is a fast and collaborative Apache Spark-based big data analytics service designed for data science and data engineering. Azure Databricks, sets up your Apache Spark environment in minutes, autoscale, and collaborate on shared projects in an interactive workspace. Azure Databricks supports Python, Scala, R, Java, and SQL, as well as data science frameworks and libraries including TensorFlow, PyTorch, and scikit-learn.

[Microsoft Cognitive Toolkit (CNTK)](https://docs.microsoft.com/en-us/cognitive-toolkit/) is an open-source toolkit for commercial-grade distributed deep learning. It describes neural networks as a series of computational steps via a directed graph. CNTK allows the user to easily realize and combine popular model types such as feed-forward DNNs, convolutional neural networks (CNNs) and recurrent neural networks (RNNs/LSTMs). CNTK implements stochastic gradient descent (SGD, error backpropagation) learning with automatic differentiation and parallelization across multiple GPUs and servers.

[Apple CoreML](https://developer.apple.com/documentation/coreml) is a framework that helps integrate machine learning models into your app. Core ML provides a unified representation for all models. Your app uses Core ML APIs and user data to make predictions, and to train or fine-tune models, all on the user's device. A model is the result of applying a machine learning algorithm to a set of training data. You use a model to make predictions based on new input data.

[Tensorflow_macOS](https://github.com/apple/tensorflow_macos) is a Mac-optimized version of TensorFlow and TensorFlow Addons for macOS 11.0+ accelerated using Apple's ML Compute framework.

[Apache OpenNLP](https://opennlp.apache.org/) is an open-source library for a machine learning based toolkit used in the processing of natural language text. It features an API for use cases like [Named Entity Recognition](https://en.wikipedia.org/wiki/Named-entity_recognition), [Sentence Detection](), [POS(Part-Of-Speech) tagging](https://en.wikipedia.org/wiki/Part-of-speech_tagging), [Tokenization](https://en.wikipedia.org/wiki/Tokenization_(data_security)) [Feature extraction](https://en.wikipedia.org/wiki/Feature_extraction), [Chunking](https://en.wikipedia.org/wiki/Chunking_(psychology)), [Parsing](https://en.wikipedia.org/wiki/Parsing), and [Coreference resolution](https://en.wikipedia.org/wiki/Coreference).

[Apache Airflow](https://airflow.apache.org) is an open-source workflow management platform created by the community to programmatically author, schedule and monitor workflows. Install. Principles. Scalable. Airflow has a modular architecture and uses a message queue to orchestrate an arbitrary number of workers. Airflow is ready to scale to infinity.

[Open Neural Network Exchange(ONNX)](https://github.com/onnx) is an open ecosystem that empowers AI developers to choose the right tools as their project evolves. ONNX provides an open source format for AI models, both deep learning and traditional ML. It defines an extensible computation graph model, as well as definitions of built-in operators and standard data types.

[Apache MXNet](https://mxnet.apache.org/) is a deep learning framework designed for both efficiency and flexibility. It allows you to mix symbolic and imperative programming to maximize efficiency and productivity. At its core, MXNet contains a dynamic dependency scheduler that automatically parallelizes both symbolic and imperative operations on the fly. A graph optimization layer on top of that makes symbolic execution fast and memory efficient. MXNet is portable and lightweight, scaling effectively to multiple GPUs and multiple machines. Support for Python, R, Julia, Scala, Go, Javascript and more.

[AutoGluon](https://autogluon.mxnet.io/index.html) is toolkit for Deep learning that automates machine learning tasks enabling you to easily achieve strong predictive performance in your applications. With just a few lines of code, you can train and deploy high-accuracy deep learning models on tabular, image, and text data.

[Anaconda](https://www.anaconda.com/) is a very popular Data Science platform for machine learning and deep learning that enables users to develop models, train them, and deploy them.

[PlaidML](https://github.com/plaidml/plaidml) is an advanced and portable tensor compiler for enabling deep learning on laptops, embedded devices, or other devices where the available computing hardware is not well supported or the available software stack contains unpalatable license restrictions.

[OpenCV](https://opencv.org) is a highly optimized library with focus on real-time computer vision applications. The C++, Python, and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a Python module for machine learning built on top of SciPy, NumPy, and matplotlib, making it easier to apply robust and simple implementations of many popular machine learning algorithms.

[Weka](https://www.cs.waikato.ac.nz/ml/weka/) is an open source machine learning software that can be accessed through a graphical user interface, standard terminal applications, or a Java API. It is widely used for teaching, research, and industrial applications, contains a plethora of built-in tools for standard machine learning tasks, and additionally gives transparent access to well-known toolboxes such as scikit-learn, R, and Deeplearning4j.

[Caffe](https://github.com/BVLC/caffe) is a deep learning framework made with expression, speed, and modularity in mind. It is developed by Berkeley AI Research (BAIR)/The Berkeley Vision and Learning Center (BVLC) and community contributors.

[Theano](https://github.com/Theano/Theano) is a Python library that allows you to define, optimize, and evaluate mathematical expressions involving multi-dimensional arrays efficiently including tight integration with NumPy.

[nGraph](https://github.com/NervanaSystems/ngraph) is an open source C++ library, compiler and runtime for Deep Learning. The nGraph Compiler aims to accelerate developing AI workloads using any deep learning framework and deploying to a variety of hardware targets.It provides the freedom, performance, and ease-of-use to AI developers.

[NVIDIA cuDNN](https://developer.nvidia.com/cudnn) is a GPU-accelerated library of primitives for [deep neural networks](https://developer.nvidia.com/deep-learning). cuDNN provides highly tuned implementations for standard routines such as forward and backward convolution, pooling, normalization, and activation layers. cuDNN accelerates widely used deep learning frameworks, including [Caffe2](https://caffe2.ai/), [Chainer](https://chainer.org/), [Keras](https://keras.io/), [MATLAB](https://www.mathworks.com/solutions/deep-learning.html), [MxNet](https://mxnet.incubator.apache.org/), [PyTorch](https://pytorch.org/), and [TensorFlow](https://www.tensorflow.org/).

[Jupyter Notebook](https://jupyter.org/) is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Jupyter is used widely in industries that do data cleaning and transformation, numerical simulation, statistical modeling, data visualization, data science, and machine learning.

[Apache Spark](https://spark.apache.org/) is a unified analytics engine for large-scale data processing. It provides high-level APIs in Scala, Java, Python, and R, and an optimized engine that supports general computation graphs for data analysis. It also supports a rich set of higher-level tools including Spark SQL for SQL and DataFrames, MLlib for machine learning, GraphX for graph processing, and Structured Streaming for stream processing.

[Apache Spark Connector for SQL Server and Azure SQL](https://github.com/microsoft/sql-spark-connector) is a high-performance connector that enables you to use transactional data in big data analytics and persists results for ad-hoc queries or reporting. The connector allows you to use any SQL database, on-premises or in the cloud, as an input data source or output data sink for Spark jobs.

[Apache PredictionIO](https://predictionio.apache.org/) is an open source machine learning framework for developers, data scientists, and end users. It supports event collection, deployment of algorithms, evaluation, querying predictive results via REST APIs. It is based on scalable open source services like Hadoop, HBase (and other DBs), Elasticsearch, Spark and implements what is called a Lambda Architecture.

[Cluster Manager for Apache Kafka(CMAK)](https://github.com/yahoo/CMAK) is a tool for managing [Apache Kafka](https://kafka.apache.org/) clusters.

[BigDL](https://bigdl-project.github.io/) is a distributed deep learning library for Apache Spark. With BigDL, users can write their deep learning applications as standard Spark programs, which can directly run on top of existing Spark or Hadoop clusters.

[Eclipse Deeplearning4J (DL4J)](https://deeplearning4j.konduit.ai/) is a set of projects intended to support all the needs of a JVM-based(Scala, Kotlin, Clojure, and Groovy) deep learning application. This means starting with the raw data, loading and preprocessing it from wherever and whatever format it is in to building and tuning a wide variety of simple and complex deep learning networks.

[Tensorman](https://github.com/pop-os/tensorman) is a utility for easy management of Tensorflow containers by developed by [System76]( https://system76.com).Tensorman allows Tensorflow to operate in an isolated environment that is contained from the rest of the system. This virtual environment can operate independent of the base system, allowing you to use any version of Tensorflow on any version of a Linux distribution that supports the Docker runtime.

[Numba](https://github.com/numba/numba) is an open source, NumPy-aware optimizing compiler for Python sponsored by Anaconda, Inc. It uses the LLVM compiler project to generate machine code from Python syntax. Numba can compile a large subset of numerically-focused Python, including many NumPy functions. Additionally, Numba has support for automatic parallelization of loops, generation of GPU-accelerated code, and creation of ufuncs and C callbacks.

[Chainer](https://chainer.org/) is a Python-based deep learning framework aiming at flexibility. It provides automatic differentiation APIs based on the define-by-run approach (dynamic computational graphs) as well as object-oriented high-level APIs to build and train neural networks. It also supports CUDA/cuDNN using [CuPy](https://github.com/cupy/cupy) for high performance training and inference.

[XGBoost](https://xgboost.readthedocs.io/) is an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable. It implements machine learning algorithms under the Gradient Boosting framework. XGBoost provides a parallel tree boosting (also known as GBDT, GBM) that solve many data science problems in a fast and accurate way. It supports distributed training on multiple machines, including AWS, GCE, Azure, and Yarn clusters. Also, it can be integrated with Flink, Spark and other cloud dataflow systems.

[cuML](https://github.com/rapidsai/cuml) is a suite of libraries that implement machine learning algorithms and mathematical primitives functions that share compatible APIs with other RAPIDS projects. cuML enables data scientists, researchers, and software engineers to run traditional tabular ML tasks on GPUs without going into the details of CUDA programming. In most cases, cuML's Python API matches the API from scikit-learn.

# Deep Learning
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/133943699-6dcfcb40-ddf7-4501-86e0-41e8aee91fe2.png">
  <br />
</p>

## Deep Learning Learning Resources

[Deep Learning](https://www.ibm.com/cloud/learn/deep-learning) is a subset of machine learning, which is essentially a neural network with three or more layers. These neural networks attempt to simulate the behavior of the human brain,though, far from matching its ability. This allows the neural networks to "learn" from large amounts of data. The Learning can be [supervised](https://en.wikipedia.org/wiki/Supervised_learning), [semi-supervised](https://en.wikipedia.org/wiki/Semi-supervised_learning) or [unsupervised](https://en.wikipedia.org/wiki/Unsupervised_learning).

[Deep Learning Online Courses | NVIDIA](https://www.nvidia.com/en-us/training/online/)

[Top Deep Learning Courses Online | Coursera](https://www.coursera.org/courses?query=deep%20learning)

[Top Deep Learning Courses Online | Udemy](https://www.udemy.com/topic/deep-learning/)

[Learn Deep Learning with Online Courses and Lessons | edX](https://www.edx.org/learn/deep-learning)

[Deep Learning Online Course Nanodegree | Udacity](https://www.udacity.com/course/deep-learning-nanodegree--nd101)

[Machine Learning Course by Andrew Ng | Coursera](https://www.coursera.org/learn/machine-learning?)

[Machine Learning Engineering for Production (MLOps) course by Andrew Ng | Coursera](https://www.coursera.org/specializations/machine-learning-engineering-for-production-mlops)

[Data Science: Deep Learning and Neural Networks in Python | Udemy](https://www.udemy.com/course/data-science-deep-learning-in-python/)

[Understanding Machine Learning with Python | Pluralsight ](https://www.pluralsight.com/courses/python-understanding-machine-learning)

[How to Think About Machine Learning Algorithms | Pluralsight](https://www.pluralsight.com/courses/machine-learning-algorithms)

[Deep Learning Courses | Stanford Online](https://online.stanford.edu/courses/cs230-deep-learning)

[Deep Learning - UW Professional & Continuing Education](https://www.pce.uw.edu/courses/deep-learning)

[Deep Learning Online Courses | Harvard University](https://online-learning.harvard.edu/course/deep-learning-0)

[Machine Learning for Everyone Courses | DataCamp](https://www.datacamp.com/courses/introduction-to-machine-learning-with-r)

[Artificial Intelligence Expert Course: Platinum Edition | Udemy](https://www.udemy.com/course/artificial-intelligence-exposed-future-10-extreme-edition/)

[Top Artificial Intelligence Courses Online | Coursera](https://www.coursera.org/courses?query=artificial%20intelligence)

[Learn Artificial Intelligence with Online Courses and Lessons | edX](https://www.edx.org/learn/artificial-intelligence)

[Professional Certificate in Computer Science for Artificial Intelligence | edX](https://www.edx.org/professional-certificate/harvardx-computer-science-for-artifical-intelligence)

[Artificial Intelligence Nanodegree program](https://www.udacity.com/course/ai-artificial-intelligence-nanodegree--nd898)

[Artificial Intelligence (AI) Online Courses | Udacity](https://www.udacity.com/school-of-ai)

[Intro to Artificial Intelligence Course | Udacity](https://www.udacity.com/course/intro-to-artificial-intelligence--cs271)

[Edge AI for IoT Developers Course | Udacity](https://www.udacity.com/course/intel-edge-ai-for-iot-developers-nanodegree--nd131)

[Reasoning: Goal Trees and Rule-Based Expert Systems | MIT OpenCourseWare](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-034-artificial-intelligence-fall-2010/lecture-videos/lecture-3-reasoning-goal-trees-and-rule-based-expert-systems/)

[Expert Systems and Applied Artificial Intelligence](https://www.umsl.edu/~joshik/msis480/chapt11.htm)

[Autonomous Systems - Microsoft AI](https://www.microsoft.com/en-us/ai/autonomous-systems)

[Introduction to Microsoft Project Bonsai](https://docs.microsoft.com/en-us/learn/autonomous-systems/intro-to-project-bonsai/)

[Machine teaching with the Microsoft Autonomous Systems platform](https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/articles/autonomous-systems)

[Autonomous Maritime Systems Training | AMC Search](https://www.amcsearch.com.au/ams-training)

[Top Autonomous Cars Courses Online | Udemy](https://www.udemy.com/topic/autonomous-cars/)

[Applied Control Systems 1: autonomous cars: Math + PID + MPC | Udemy](https://www.udemy.com/course/applied-systems-control-for-engineers-modelling-pid-mpc/)

[Learn Autonomous Robotics with Online Courses and Lessons | edX](https://www.edx.org/learn/autonomous-robotics)

[Artificial Intelligence Nanodegree program](https://www.udacity.com/course/ai-artificial-intelligence-nanodegree--nd898)

[Autonomous Systems Online Courses & Programs | Udacity](https://www.udacity.com/school-of-autonomous-systems)

[Edge AI for IoT Developers Course | Udacity](https://www.udacity.com/course/intel-edge-ai-for-iot-developers-nanodegree--nd131)

[Autonomous Systems MOOC and Free Online Courses | MOOC List](https://www.mooc-list.com/tags/autonomous-systems)

[Robotics and Autonomous Systems Graduate Program | Standford Online](https://online.stanford.edu/programs/robotics-and-autonomous-systems-graduate-program)

[Mobile Autonomous Systems Laboratory | MIT OpenCourseWare](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-186-mobile-autonomous-systems-laboratory-january-iap-2005/lecture-notes/)

## Deep Learning Tools, Libraries, and Frameworks

[NVIDIA cuDNN](https://developer.nvidia.com/cudnn) is a GPU-accelerated library of primitives for [deep neural networks](https://developer.nvidia.com/deep-learning). cuDNN provides highly tuned implementations for standard routines such as forward and backward convolution, pooling, normalization, and activation layers. cuDNN accelerates widely used deep learning frameworks, including [Caffe2](https://caffe2.ai/), [Chainer](https://chainer.org/), [Keras](https://keras.io/), [MATLAB](https://www.mathworks.com/solutions/deep-learning.html), [MxNet](https://mxnet.incubator.apache.org/), [PyTorch](https://pytorch.org/), and [TensorFlow](https://www.tensorflow.org/).

[NVIDIA DLSS (Deep Learning Super Sampling)](https://developer.nvidia.com/dlss) is a temporal image upscaling AI rendering technology that increases graphics performance using dedicated Tensor Core AI processors on GeForce RTX™ GPUs. DLSS uses the power of a deep learning neural network to boost frame rates and generate beautiful, sharp images for your games.

[AMD FidelityFX Super Resolution (FSR)](https://www.amd.com/en/technologies/radeon-software-fidelityfx) is an open source, high-quality solution for producing high resolution frames from lower resolution inputs. It uses a collection of cutting-edge Deep Learning algorithms with a particular emphasis on creating high-quality edges, giving large performance improvements compared to rendering at native resolution directly. FSR enables “practical performance” for costly render operations, such as hardware ray tracing for the AMD RDNA™ and AMD RDNA™ 2 architectures.

[Intel Xe Super Sampling (XeSS)](https://www.youtube.com/watch?v=Y9hfpf-SqEg) is a temporal image upscaling AI rendering technology that increases graphics performance similar to NVIDIA's [DLSS (Deep Learning Super Sampling)](https://developer.nvidia.com/dlss). Intel's Arc GPU architecture (early 2022) will have GPUs that feature dedicated Xe-cores to run XeSS. The GPUs will have Xe Matrix eXtenstions matrix (XMX) engines for hardware-accelerated AI processing. XeSS will be able to run on devices without XMX, including integrated graphics, though, the performance of XeSS will be lower on non-Intel graphics cards because it will be powered by [DP4a instruction](https://www.intel.com/content/dam/www/public/us/en/documents/reference-guides/11th-gen-quick-reference-guide.pdf).

[Jupyter Notebook](https://jupyter.org/) is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Jupyter is used widely in industries that do data cleaning and transformation, numerical simulation, statistical modeling, data visualization, data science, and machine learning.

[Apache Spark](https://spark.apache.org/) is a unified analytics engine for large-scale data processing. It provides high-level APIs in Scala, Java, Python, and R, and an optimized engine that supports general computation graphs for data analysis. It also supports a rich set of higher-level tools including Spark SQL for SQL and DataFrames, MLlib for machine learning, GraphX for graph processing, and Structured Streaming for stream processing.

[Apache Spark Connector for SQL Server and Azure SQL](https://github.com/microsoft/sql-spark-connector) is a high-performance connector that enables you to use transactional data in big data analytics and persists results for ad-hoc queries or reporting. The connector allows you to use any SQL database, on-premises or in the cloud, as an input data source or output data sink for Spark jobs.

[Apache PredictionIO](https://predictionio.apache.org/) is an open source machine learning framework for developers, data scientists, and end users. It supports event collection, deployment of algorithms, evaluation, querying predictive results via REST APIs. It is based on scalable open source services like Hadoop, HBase (and other DBs), Elasticsearch, Spark and implements what is called a Lambda Architecture.

[Cluster Manager for Apache Kafka(CMAK)](https://github.com/yahoo/CMAK) is a tool for managing [Apache Kafka](https://kafka.apache.org/) clusters.

[BigDL](https://bigdl-project.github.io/) is a distributed deep learning library for Apache Spark. With BigDL, users can write their deep learning applications as standard Spark programs, which can directly run on top of existing Spark or Hadoop clusters.

[Eclipse Deeplearning4J (DL4J)](https://deeplearning4j.konduit.ai/) is a set of projects intended to support all the needs of a JVM-based(Scala, Kotlin, Clojure, and Groovy) deep learning application. This means starting with the raw data, loading and preprocessing it from wherever and whatever format it is in to building and tuning a wide variety of simple and complex deep learning networks.

[Deep Learning Toolbox™](https://www.mathworks.com/products/deep-learning.html) is a tool that provides a framework for designing and implementing deep neural networks with algorithms, pretrained models, and apps. You can use convolutional neural networks (ConvNets, CNNs) and long short-term memory (LSTM) networks to perform classification and regression on image, time-series, and text data. You can build network architectures such as generative adversarial networks (GANs) and Siamese networks using automatic differentiation, custom training loops, and shared weights. With the Deep Network Designer app, you can design, analyze, and train networks graphically. It can exchange models with TensorFlow™ and PyTorch through the ONNX format and import models from TensorFlow-Keras and Caffe. The toolbox supports transfer learning with DarkNet-53, ResNet-50, NASNet, SqueezeNet and many other pretrained models.

[Reinforcement Learning Toolbox™](https://www.mathworks.com/products/reinforcement-learning.html) is a tool that provides an app, functions, and a Simulink® block for training policies using reinforcement learning algorithms, including DQN, PPO, SAC, and DDPG. You can use these policies to implement controllers and decision-making algorithms for complex applications such as resource allocation, robotics, and autonomous systems.

[Deep Learning HDL Toolbox™](https://www.mathworks.com/products/deep-learning-hdl.html) is a tool that provides functions and tools to prototype and implement deep learning networks on FPGAs and SoCs. It provides pre-built bitstreams for running a variety of deep learning networks on supported Xilinx® and Intel® FPGA and SoC devices. Profiling and estimation tools let you customize a deep learning network by exploring design, performance, and resource utilization tradeoffs.

[Parallel Computing Toolbox™](https://www.mathworks.com/products/matlab-parallel-server.html) is a tool that lets you solve computationally and data-intensive problems using multicore processors, GPUs, and computer clusters. High-level constructs such as parallel for-loops, special array types, and parallelized numerical algorithms enable you to parallelize MATLAB® applications without CUDA or MPI programming. The toolbox lets you use parallel-enabled functions in MATLAB and other toolboxes. You can use the toolbox with Simulink® to run multiple simulations of a model in parallel. Programs and models can run in both interactive and batch modes.

[XGBoost](https://xgboost.readthedocs.io/) is an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable. It implements machine learning algorithms under the Gradient Boosting framework. XGBoost provides a parallel tree boosting (also known as GBDT, GBM) that solve many data science problems in a fast and accurate way. It supports distributed training on multiple machines, including AWS, GCE, Azure, and Yarn clusters. Also, it can be integrated with Flink, Spark and other cloud dataflow systems.

[LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) is an integrated software for support vector classification, (C-SVC, nu-SVC), regression (epsilon-SVR, nu-SVR) and distribution estimation (one-class SVM). It supports multi-class classification.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a simple and efficient tool for data mining and data analysis. It is built on NumPy,SciPy, and mathplotlib.

[TensorFlow](https://www.tensorflow.org) is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.

[Keras](https://keras.io) is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano.It was developed with a focus on enabling fast experimentation. It is capable of running on top of TensorFlow, Microsoft Cognitive Toolkit, R, Theano, or PlaidML.

[PyTorch](https://pytorch.org) is a library for deep learning on irregular input data such as graphs, point clouds, and manifolds. Primarily developed by Facebook's AI Research lab.

[Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/) is a fast and collaborative Apache Spark-based big data analytics service designed for data science and data engineering. Azure Databricks, sets up your Apache Spark environment in minutes, autoscale, and collaborate on shared projects in an interactive workspace. Azure Databricks supports Python, Scala, R, Java, and SQL, as well as data science frameworks and libraries including TensorFlow, PyTorch, and scikit-learn.

[Microsoft Cognitive Toolkit (CNTK)](https://docs.microsoft.com/en-us/cognitive-toolkit/) is an open-source toolkit for commercial-grade distributed deep learning. It describes neural networks as a series of computational steps via a directed graph. CNTK allows the user to easily realize and combine popular model types such as feed-forward DNNs, convolutional neural networks (CNNs) and recurrent neural networks (RNNs/LSTMs). CNTK implements stochastic gradient descent (SGD, error backpropagation) learning with automatic differentiation and parallelization across multiple GPUs and servers.

[Tensorflow_macOS](https://github.com/apple/tensorflow_macos) is a Mac-optimized version of TensorFlow and TensorFlow Addons for macOS 11.0+ accelerated using Apple's ML Compute framework.

[Apache Airflow](https://airflow.apache.org) is an open-source workflow management platform created by the community to programmatically author, schedule and monitor workflows. Install. Principles. Scalable. Airflow has a modular architecture and uses a message queue to orchestrate an arbitrary number of workers. Airflow is ready to scale to infinity.

[Open Neural Network Exchange(ONNX)](https://github.com/onnx) is an open ecosystem that empowers AI developers to choose the right tools as their project evolves. ONNX provides an open source format for AI models, both deep learning and traditional ML. It defines an extensible computation graph model, as well as definitions of built-in operators and standard data types.

[Apache MXNet](https://mxnet.apache.org/) is a deep learning framework designed for both efficiency and flexibility. It allows you to mix symbolic and imperative programming to maximize efficiency and productivity. At its core, MXNet contains a dynamic dependency scheduler that automatically parallelizes both symbolic and imperative operations on the fly. A graph optimization layer on top of that makes symbolic execution fast and memory efficient. MXNet is portable and lightweight, scaling effectively to multiple GPUs and multiple machines. Support for Python, R, Julia, Scala, Go, Javascript and more.

[AutoGluon](https://autogluon.mxnet.io/index.html) is toolkit for Deep learning that automates machine learning tasks enabling you to easily achieve strong predictive performance in your applications. With just a few lines of code, you can train and deploy high-accuracy deep learning models on tabular, image, and text data.

[Anaconda](https://www.anaconda.com/) is a very popular Data Science platform for machine learning and deep learning that enables users to develop models, train them, and deploy them.

[PlaidML](https://github.com/plaidml/plaidml) is an advanced and portable tensor compiler for enabling deep learning on laptops, embedded devices, or other devices where the available computing hardware is not well supported or the available software stack contains unpalatable license restrictions.

[OpenCV](https://opencv.org) is a highly optimized library with focus on real-time computer vision applications. The C++, Python, and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a Python module for machine learning built on top of SciPy, NumPy, and matplotlib, making it easier to apply robust and simple implementations of many popular machine learning algorithms.

[Weka](https://www.cs.waikato.ac.nz/ml/weka/) is an open source machine learning software that can be accessed through a graphical user interface, standard terminal applications, or a Java API. It is widely used for teaching, research, and industrial applications, contains a plethora of built-in tools for standard machine learning tasks, and additionally gives transparent access to well-known toolboxes such as scikit-learn, R, and Deeplearning4j.

[Caffe](https://github.com/BVLC/caffe) is a deep learning framework made with expression, speed, and modularity in mind. It is developed by Berkeley AI Research (BAIR)/The Berkeley Vision and Learning Center (BVLC) and community contributors.

[Theano](https://github.com/Theano/Theano) is a Python library that allows you to define, optimize, and evaluate mathematical expressions involving multi-dimensional arrays efficiently including tight integration with NumPy.

[Microsoft Project Bonsai](https://azure.microsoft.com/en-us/services/project-bonsai/) is a low-code AI platform that speeds AI-powered automation development and part of the Autonomous Systems suite from Microsoft. Bonsai is used to build AI components that can provide operator guidance or make independent decisions to optimize process variables, improve production efficiency, and reduce downtime.

[Microsoft AirSim](https://microsoft.github.io/AirSim/lidar.html) is a simulator for drones, cars and more, built on Unreal Engine (with an experimental Unity release). AirSim is open-source, cross platform, and supports [software-in-the-loop simulation](https://www.mathworks.com/help///ecoder/software-in-the-loop-sil-simulation.html) with popular flight controllers such as PX4 & ArduPilot and [hardware-in-loop](https://www.ni.com/en-us/innovations/white-papers/17/what-is-hardware-in-the-loop-.html) with PX4 for physically and visually realistic simulations. It is developed as an Unreal plugin that can simply be dropped into any Unreal environment. AirSim is being developed  as a platform for AI research to experiment with deep learning, computer vision and reinforcement learning algorithms for autonomous vehicles.

[CARLA](https://github.com/carla-simulator/carla) is an open-source simulator for autonomous driving research. CARLA has been developed from the ground up to support development, training, and validation of autonomous driving systems. In addition to open-source code and protocols, CARLA provides open digital assets (urban layouts, buildings, vehicles) that were created for this purpose and can be used freely.

[ROS/ROS2 bridge for CARLA(package)](https://github.com/carla-simulator/ros-bridge) is a bridge that enables two-way communication between ROS and CARLA. The information from the CARLA server is translated to ROS topics. In the same way, the messages sent between nodes in ROS get translated to commands to be applied in CARLA.

[ROS Toolbox](https://www.mathworks.com/products/ros.html) is a tool that provides an interface connecting MATLAB® and Simulink® with the Robot Operating System (ROS and ROS 2), enabling you to create a network of ROS nodes. The toolbox includes MATLAB functions and Simulink blocks to import, analyze, and play back ROS data recorded in rosbag files. You can also connect to a live ROS network to access ROS messages.

[Robotics Toolbox™](https://www.mathworks.com/products/robotics.html) provides a toolbox that brings robotics specific functionality(designing, simulating, and testing manipulators, mobile robots, and humanoid robots) to MATLAB, exploiting the native capabilities of MATLAB (linear algebra, portability, graphics). The toolbox also supports mobile robots with functions for robot motion models (bicycle), path planning algorithms (bug, distance transform, D*, PRM), kinodynamic planning (lattice, RRT), localization (EKF, particle filter), map building (EKF) and simultaneous localization and mapping (EKF), and a Simulink model a of non-holonomic vehicle. The Toolbox also including a detailed Simulink model for a quadrotor flying robot.

[Image Processing Toolbox™](https://www.mathworks.com/products/image.html) is a tool that provides a comprehensive set of reference-standard algorithms and workflow apps for image processing, analysis, visualization, and algorithm development. You can perform image segmentation, image enhancement, noise reduction, geometric transformations, image registration, and 3D image processing.

[Computer Vision Toolbox™](https://www.mathworks.com/products/computer-vision.html) is a tool that provides algorithms, functions, and apps for designing and testing computer vision, 3D vision, and video processing systems. You can perform object detection and tracking, as well as feature detection, extraction, and matching. You can automate calibration workflows for single, stereo, and fisheye cameras. For 3D vision, the toolbox supports visual and point cloud SLAM, stereo vision, structure from motion, and point cloud processing.

[Robotics Toolbox™](https://www.mathworks.com/products/robotics.html) is a tool that provides a toolbox that brings robotics specific functionality(designing, simulating, and testing manipulators, mobile robots, and humanoid robots) to MATLAB, exploiting the native capabilities of MATLAB (linear algebra, portability, graphics). The toolbox also supports mobile robots with functions for robot motion models (bicycle), path planning algorithms (bug, distance transform, D*, PRM), kinodynamic planning (lattice, RRT), localization (EKF, particle filter), map building (EKF) and simultaneous localization and mapping (EKF), and a Simulink model a of non-holonomic vehicle. The Toolbox also including a detailed Simulink model for a quadrotor flying robot.

[Model Predictive Control Toolbox™](https://www.mathworks.com/products/model-predictive-control.html) is a tool that provides functions, an app, and Simulink® blocks for designing and simulating controllers using linear and nonlinear model predictive control (MPC). The toolbox lets you specify plant and disturbance models, horizons, constraints, and weights. By running closed-loop simulations, you can evaluate controller performance.

[Predictive Maintenance Toolbox™](https://www.mathworks.com/products/predictive-maintenance.html)  is a tool that lets you manage sensor data, design condition indicators, and estimate the remaining useful life (RUL) of a machine. The toolbox provides functions and an interactive app for exploring, extracting, and ranking features using data-based and model-based techniques, including statistical, spectral, and time-series analysis.

[Vision HDL Toolbox™](https://www.mathworks.com/products/vision-hdl.html) is a tool that provides pixel-streaming algorithms for the design and implementation of vision systems on FPGAs and ASICs. It provides a design framework that supports a diverse set of interface types, frame sizes, and frame rates. The image processing, video, and computer vision algorithms in the toolbox use an architecture appropriate for HDL implementations.

[Automated Driving Toolbox™](https://www.mathworks.com/products/automated-driving.html) is a MATLAB tool that provides algorithms and tools for designing, simulating, and testing ADAS and autonomous driving systems. You can design and test vision and lidar perception systems, as well as sensor fusion, path planning, and vehicle controllers. Visualization tools include a bird’s-eye-view plot and scope for sensor coverage, detections and tracks, and displays for video, lidar, and maps. The toolbox lets you import and work with HERE HD Live Map data and OpenDRIVE® road networks. It also provides reference application examples for common ADAS and automated driving features, including FCW, AEB, ACC, LKA, and parking valet. The toolbox supports C/C++ code generation for rapid prototyping and HIL testing, with support for sensor fusion, tracking, path planning, and vehicle controller algorithms.

[UAV Toolbox](https://www.mathworks.com/products/uav.html) is an application that provides tools and reference applications for designing, simulating, testing, and deploying unmanned aerial vehicle (UAV) and drone applications. You can design autonomous flight algorithms, UAV missions, and flight controllers. The Flight Log Analyzer app lets you interactively analyze 3D flight paths, telemetry information, and sensor readings from common flight log formats.

[Navigation Toolbox™](https://www.mathworks.com/products/navigation.html) is a tool that provides algorithms and analysis tools for motion planning, simultaneous localization and mapping (SLAM), and inertial navigation. The toolbox includes customizable search and sampling-based path planners, as well as metrics for validating and comparing paths. You can create 2D and 3D map representations, generate maps using SLAM algorithms, and interactively visualize and debug map generation with the SLAM map builder app.

[Lidar Toolbox™](https://www.mathworks.com/products/lidar.html) is a tool that provides algorithms, functions, and apps for designing, analyzing, and testing lidar processing systems. You can perform object detection and tracking, semantic segmentation, shape fitting, lidar registration, and obstacle detection. Lidar Toolbox supports lidar-camera cross calibration for workflows that combine computer vision and lidar processing.

[Mapping Toolbox™](https://www.mathworks.com/products/mapping.html) is a tool that provides algorithms and functions for transforming geographic data and creating map displays. You can visualize your data in a geographic context, build map displays from more than 60 map projections, and transform data from a variety of sources into a consistent geographic coordinate system.

# CUDA Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/94306481-e17b8f00-ff27-11ea-832f-c85374acb3b1.png">
  <br />
</p>


<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/117718735-55a23480-b191-11eb-874d-e690d09cd490.png">
  <br />
</p>

**CUDA Toolkit. Source: [NVIDIA Developer CUDA](https://developer.nvidia.com/cuda-zone)**

## CUDA Learning Resources

[CUDA](https://developer.nvidia.com/cuda-zone) is a parallel computing platform and programming model developed by NVIDIA for general computing on graphical processing units (GPUs). With CUDA, developers are able to dramatically speed up computing applications by harnessing the power of GPUs. In GPU-accelerated applications, the sequential part of the workload runs on the CPU, which is optimized for single-threaded. The compute intensive portion of the application runs on thousands of GPU cores in parallel. When using CUDA, developers can program in popular languages such as C, C++, Fortran, Python and MATLAB.

[CUDA Toolkit Documentation](https://docs.nvidia.com/cuda/index.html)

[CUDA Quick Start Guide](https://docs.nvidia.com/cuda/cuda-quick-start-guide/index.html)

[CUDA on WSL](https://docs.nvidia.com/cuda/wsl-user-guide/index.html)

[CUDA GPU support for TensorFlow](https://www.tensorflow.org/install/gpu)

[NVIDIA Deep Learning cuDNN Documentation](https://docs.nvidia.com/deeplearning/cudnn/api/index.html)

[NVIDIA GPU Cloud Documentation](https://docs.nvidia.com/ngc/ngc-introduction/index.html)

[NVIDIA NGC](https://ngc.nvidia.com/) is a hub for GPU-optimized software for deep learning, machine learning, and high-performance computing (HPC) workloads.

[NVIDIA NGC Containers](https://www.nvidia.com/en-us/gpu-cloud/containers/) is a registry that provides researchers, data scientists, and developers with simple access to a comprehensive catalog of GPU-accelerated software for AI, machine learning and HPC. These containers take full advantage of NVIDIA GPUs on-premises and in the cloud.

## CUDA Tools Libraries, and Frameworks

[CUDA Toolkit](https://developer.nvidia.com/cuda-downloads) is a collection of tools & libraries that provide a development environment for creating high performance GPU-accelerated applications. The CUDA Toolkit allows you can develop, optimize, and deploy your applications on GPU-accelerated embedded systems, desktop workstations, enterprise data centers, cloud-based platforms and HPC supercomputers. The toolkit includes GPU-accelerated libraries, debugging and optimization tools, a C/C++ compiler, and a runtime library to build and deploy your application on major architectures including x86, Arm and POWER.

[NVIDIA cuDNN](https://developer.nvidia.com/cudnn) is a GPU-accelerated library of primitives for [deep neural networks](https://developer.nvidia.com/deep-learning). cuDNN provides highly tuned implementations for standard routines such as forward and backward convolution, pooling, normalization, and activation layers. cuDNN accelerates widely used deep learning frameworks, including [Caffe2](https://caffe2.ai/), [Chainer](https://chainer.org/), [Keras](https://keras.io/), [MATLAB](https://www.mathworks.com/solutions/deep-learning.html), [MxNet](https://mxnet.incubator.apache.org/), [PyTorch](https://pytorch.org/), and [TensorFlow](https://www.tensorflow.org/).

[CUDA-X HPC](https://www.nvidia.com/en-us/technologies/cuda-x/) is a collection of libraries, tools, compilers and APIs that help developers solve the world's most challenging problems. CUDA-X HPC includes highly tuned kernels essential for high-performance computing (HPC).

[NVIDIA Container Toolkit](https://github.com/NVIDIA/nvidia-docker) is a collection of tools & libraries that allows users to build and run GPU accelerated Docker containers. The toolkit includes a container runtime [library](https://github.com/NVIDIA/libnvidia-container) and utilities to automatically configure containers to leverage NVIDIA GPUs.

[Minkowski Engine](https://nvidia.github.io/MinkowskiEngine) is an auto-differentiation library for sparse tensors. It supports all standard neural network layers such as convolution, pooling, unpooling, and broadcasting operations for sparse tensors.

[CUTLASS](https://github.com/NVIDIA/cutlass) is a collection of CUDA C++ template abstractions for implementing high-performance matrix-multiplication (GEMM) at all levels and scales within CUDA. It incorporates strategies for hierarchical decomposition and data movement similar to those used to implement cuBLAS.

[CUB](https://github.com/NVIDIA/cub) is a cooperative primitives for CUDA C++ kernel authors.

[Tensorman](https://github.com/pop-os/tensorman) is a utility for easy management of Tensorflow containers by developed by [System76]( https://system76.com).Tensorman allows Tensorflow to operate in an isolated environment that is contained from the rest of the system. This virtual environment can operate independent of the base system, allowing you to use any version of Tensorflow on any version of a Linux distribution that supports the Docker runtime.

[Numba](https://github.com/numba/numba) is an open source, NumPy-aware optimizing compiler for Python sponsored by Anaconda, Inc. It uses the LLVM compiler project to generate machine code from Python syntax. Numba can compile a large subset of numerically-focused Python, including many NumPy functions. Additionally, Numba has support for automatic parallelization of loops, generation of GPU-accelerated code, and creation of ufuncs and C callbacks.

[Chainer](https://chainer.org/) is a Python-based deep learning framework aiming at flexibility. It provides automatic differentiation APIs based on the define-by-run approach (dynamic computational graphs) as well as object-oriented high-level APIs to build and train neural networks. It also supports CUDA/cuDNN using [CuPy](https://github.com/cupy/cupy) for high performance training and inference.

[CuPy](https://cupy.dev/) is an implementation of NumPy-compatible multi-dimensional array on CUDA. CuPy consists of the core multi-dimensional array class, cupy.ndarray, and many functions on it. It supports a subset of numpy.ndarray interface.

[CatBoost](https://catboost.ai/) is a fast, scalable, high performance [Gradient Boosting](https://en.wikipedia.org/wiki/Gradient_boosting) on Decision Trees library, used for ranking, classification, regression and other machine learning tasks for Python, R, Java, C++. Supports computation on CPU and GPU.

[cuDF](https://rapids.ai/) is a GPU DataFrame library for loading, joining, aggregating, filtering, and otherwise manipulating data. cuDF provides a pandas-like API that will be familiar to data engineers & data scientists, so they can use it to easily accelerate their workflows without going into the details of CUDA programming.

[cuML](https://github.com/rapidsai/cuml) is a suite of libraries that implement machine learning algorithms and mathematical primitives functions that share compatible APIs with other RAPIDS projects. cuML enables data scientists, researchers, and software engineers to run traditional tabular ML tasks on GPUs without going into the details of CUDA programming. In most cases, cuML's Python API matches the API from scikit-learn.

[ArrayFire](https://arrayfire.com/) is a general-purpose library that simplifies the process of developing software that targets parallel and massively-parallel architectures including CPUs, GPUs, and other hardware acceleration devices.

[Thrust](https://github.com/NVIDIA/thrust) is a C++ parallel programming library which resembles the C++ Standard Library. Thrust's high-level interface greatly enhances programmer productivity while enabling performance portability between GPUs and multicore CPUs.

[AresDB](https://eng.uber.com/aresdb/) is a GPU-powered real-time analytics storage and query engine. It features low query latency, high data freshness and highly efficient in-memory and on disk storage management.

[Arraymancer](https://mratsim.github.io/Arraymancer/) is a tensor (N-dimensional array) project in Nim. The main focus is providing a fast and ergonomic CPU, Cuda and OpenCL ndarray library on which to build a scientific computing ecosystem.

[Kintinuous](https://github.com/mp3guy/Kintinuous) is a real-time dense visual SLAM system capable of producing high quality globally consistent point and mesh reconstructions over hundreds of metres in real-time with only a low-cost commodity RGB-D sensor.

[GraphVite](https://graphvite.io/) is a general graph embedding engine, dedicated to high-speed and large-scale embedding learning in various applications.

# MATLAB Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/94306473-de809e80-ff27-11ea-924b-0a6947ae38bc.png">
  <br />
</p>

## MATLAB Learning Resources

[MATLAB](https://www.mathworks.com/products/matlab.html) is a programming language that does numerical computing such as expressing matrix and array mathematics directly.

[MATLAB Documentation](https://www.mathworks.com/help/matlab/)

[Getting Started with MATLAB ](https://www.mathworks.com/help/matlab/getting-started-with-matlab.html)

[MATLAB and Simulink Training from MATLAB Academy](https://matlabacademy.mathworks.com)

[MathWorks Certification Program](https://www.mathworks.com/services/training/certification.html)

[MATLAB Online Courses from Udemy](https://www.udemy.com/topic/matlab/)

[MATLAB Online Courses from Coursera](https://www.coursera.org/courses?query=matlab)

[MATLAB Online Courses from edX](https://www.edx.org/learn/matlab)

[Building a MATLAB GUI](https://www.mathworks.com/discovery/matlab-gui.html)

[MATLAB Style Guidelines 2.0](https://www.mathworks.com/matlabcentral/fileexchange/46056-matlab-style-guidelines-2-0)

[Setting Up Git Source Control with MATLAB & Simulink](https://www.mathworks.com/help/matlab/matlab_prog/set-up-git-source-control.html)

[Pull, Push and Fetch Files with Git with MATLAB & Simulink](https://www.mathworks.com/help/matlab/matlab_prog/push-and-fetch-with-git.html)

[Create New Repository with MATLAB & Simulink](https://www.mathworks.com/help/matlab/matlab_prog/add-folder-to-source-control.html)

[PRMLT](http://prml.github.io/) is Matlab code for machine learning algorithms in the PRML book.

## MATLAB Tools, Libraries, Frameworks

**[MATLAB and Simulink Services & Applications List](https://www.mathworks.com/products.html)**

[MATLAB in the Cloud](https://www.mathworks.com/solutions/cloud.html) is a service that allows you to run in cloud environments from [MathWorks Cloud](https://www.mathworks.com/solutions/cloud.html#browser) to [Public Clouds](https://www.mathworks.com/solutions/cloud.html#public-cloud) including [AWS](https://aws.amazon.com/) and [Azure](https://azure.microsoft.com/).

[MATLAB Online™](https://matlab.mathworks.com) is a service that allows to users to uilitize MATLAB and Simulink through a web browser such as Google Chrome.

[Simulink](https://www.mathworks.com/products/simulink.html) is a block diagram environment for Model-Based Design. It supports simulation, automatic code generation, and continuous testing of embedded systems.

[Simulink Online™](https://www.mathworks.com/products/simulink-online.html) is a service that provides access to Simulink through your web browser.

[MATLAB Drive™](https://www.mathworks.com/products/matlab-drive.html) is a service that gives you the ability to store, access, and work with your files from anywhere.

[MATLAB Parallel Server™](https://www.mathworks.com/products/matlab-parallel-server.html) is a tool that lets you scale MATLAB® programs and Simulink® simulations to clusters and clouds. You can prototype your programs and simulations on the desktop and then run them on clusters and clouds without recoding. MATLAB Parallel Server supports batch jobs, interactive parallel computations, and distributed computations with large matrices.

[MATLAB Schemer](https://github.com/scottclowe/matlab-schemer) is a MATLAB package makes it easy to change the color scheme (theme) of the MATLAB display and GUI.

[LRSLibrary](https://github.com/andrewssobral/lrslibrary) is a Low-Rank and Sparse Tools for Background Modeling and Subtraction in Videos. The library was designed for moving object detection in videos, but it can be also used for other computer vision and machine learning problems.

[Image Processing Toolbox™](https://www.mathworks.com/products/image.html) is a tool that provides a comprehensive set of reference-standard algorithms and workflow apps for image processing, analysis, visualization, and algorithm development. You can perform image segmentation, image enhancement, noise reduction, geometric transformations, image registration, and 3D image processing.

[Computer Vision Toolbox™](https://www.mathworks.com/products/computer-vision.html) is a tool that provides algorithms, functions, and apps for designing and testing computer vision, 3D vision, and video processing systems. You can perform object detection and tracking, as well as feature detection, extraction, and matching. You can automate calibration workflows for single, stereo, and fisheye cameras. For 3D vision, the toolbox supports visual and point cloud SLAM, stereo vision, structure from motion, and point cloud processing.

[Statistics and Machine Learning Toolbox™](https://www.mathworks.com/products/statistics.html) is a tool that provides functions and apps to describe, analyze, and model data. You can use descriptive statistics, visualizations, and clustering for exploratory data analysis; fit probability distributions to data; generate random numbers for Monte Carlo simulations, and perform hypothesis tests. Regression and classification algorithms let you draw inferences from data and build predictive models either interactively, using the Classification and Regression Learner apps, or programmatically, using AutoML.

[Lidar Toolbox™](https://www.mathworks.com/products/lidar.html) is a tool that provides algorithms, functions, and apps for designing, analyzing, and testing lidar processing systems. You can perform object detection and tracking, semantic segmentation, shape fitting, lidar registration, and obstacle detection. Lidar Toolbox supports lidar-camera cross calibration for workflows that combine computer vision and lidar processing.

[Mapping Toolbox™](https://www.mathworks.com/products/mapping.html) is a tool that provides algorithms and functions for transforming geographic data and creating map displays. You can visualize your data in a geographic context, build map displays from more than 60 map projections, and transform data from a variety of sources into a consistent geographic coordinate system.

[UAV Toolbox](https://www.mathworks.com/products/uav.html) is an application that provides tools and reference applications for designing, simulating, testing, and deploying unmanned aerial vehicle (UAV) and drone applications. You can design autonomous flight algorithms, UAV missions, and flight controllers. The Flight Log Analyzer app lets you interactively analyze 3D flight paths, telemetry information, and sensor readings from common flight log formats.

[Parallel Computing Toolbox™](https://www.mathworks.com/products/matlab-parallel-server.html) is a tool that lets you solve computationally and data-intensive problems using multicore processors, GPUs, and computer clusters. High-level constructs such as parallel for-loops, special array types, and parallelized numerical algorithms enable you to parallelize MATLAB® applications without CUDA or MPI programming. The toolbox lets you use parallel-enabled functions in MATLAB and other toolboxes. You can use the toolbox with Simulink® to run multiple simulations of a model in parallel. Programs and models can run in both interactive and batch modes.

[Partial Differential Equation Toolbox™](https://www.mathworks.com/products/pde.html) is a tool that provides functions for solving structural mechanics, heat transfer, and general partial differential equations (PDEs) using finite element analysis.

[ROS Toolbox](https://www.mathworks.com/products/ros.html) is a tool that provides an interface connecting MATLAB® and Simulink® with the Robot Operating System (ROS and ROS 2), enabling you to create a network of ROS nodes. The toolbox includes MATLAB functions and Simulink blocks to import, analyze, and play back ROS data recorded in rosbag files. You can also connect to a live ROS network to access ROS messages.

[Robotics Toolbox™](https://www.mathworks.com/products/robotics.html) provides a toolbox that brings robotics specific functionality(designing, simulating, and testing manipulators, mobile robots, and humanoid robots) to MATLAB, exploiting the native capabilities of MATLAB (linear algebra, portability, graphics). The toolbox also supports mobile robots with functions for robot motion models (bicycle), path planning algorithms (bug, distance transform, D*, PRM), kinodynamic planning (lattice, RRT), localization (EKF, particle filter), map building (EKF) and simultaneous localization and mapping (EKF), and a Simulink model a of non-holonomic vehicle. The Toolbox also including a detailed Simulink model for a quadrotor flying robot.

[Deep Learning Toolbox™](https://www.mathworks.com/products/deep-learning.html) is a tool that provides a framework for designing and implementing deep neural networks with algorithms, pretrained models, and apps. You can use convolutional neural networks (ConvNets, CNNs) and long short-term memory (LSTM) networks to perform classification and regression on image, time-series, and text data. You can build network architectures such as generative adversarial networks (GANs) and Siamese networks using automatic differentiation, custom training loops, and shared weights. With the Deep Network Designer app, you can design, analyze, and train networks graphically. It can exchange models with TensorFlow™ and PyTorch through the ONNX format and import models from TensorFlow-Keras and Caffe. The toolbox supports transfer learning with DarkNet-53, ResNet-50, NASNet, SqueezeNet and many other pretrained models.

[Reinforcement Learning Toolbox™](https://www.mathworks.com/products/reinforcement-learning.html) is a tool that provides an app, functions, and a Simulink® block for training policies using reinforcement learning algorithms, including DQN, PPO, SAC, and DDPG. You can use these policies to implement controllers and decision-making algorithms for complex applications such as resource allocation, robotics, and autonomous systems.

[Deep Learning HDL Toolbox™](https://www.mathworks.com/products/deep-learning-hdl.html) is a tool that provides functions and tools to prototype and implement deep learning networks on FPGAs and SoCs. It provides pre-built bitstreams for running a variety of deep learning networks on supported Xilinx® and Intel® FPGA and SoC devices. Profiling and estimation tools let you customize a deep learning network by exploring design, performance, and resource utilization tradeoffs.

[Model Predictive Control Toolbox™](https://www.mathworks.com/products/model-predictive-control.html) is a tool that provides functions, an app, and Simulink® blocks for designing and simulating controllers using linear and nonlinear model predictive control (MPC). The toolbox lets you specify plant and disturbance models, horizons, constraints, and weights. By running closed-loop simulations, you can evaluate controller performance.

[Vision HDL Toolbox™](https://www.mathworks.com/products/vision-hdl.html) is a tool that provides pixel-streaming algorithms for the design and implementation of vision systems on FPGAs and ASICs. It provides a design framework that supports a diverse set of interface types, frame sizes, and frame rates. The image processing, video, and computer vision algorithms in the toolbox use an architecture appropriate for HDL implementations.

[SoC Blockset™](https://www.mathworks.com/products/soc.html) is a tool that provides Simulink® blocks and visualization tools for modeling, simulating, and analyzing hardware and software architectures for ASICs, FPGAs, and systems on a chip (SoC). You can build your system architecture using memory models, bus models, and I/O models, and simulate the architecture together with the algorithms.

[Wireless HDL Toolbox™](https://www.mathworks.com/products/wireless-hdl.html) is a tool that provides pre-verified, hardware-ready Simulink® blocks and subsystems for developing 5G, LTE, and custom OFDM-based wireless communication applications. It includes reference applications, IP blocks, and gateways between frame and sample-based processing.

[ThingSpeak™](https://www.mathworks.com/products/thingspeak.html) is an IoT analytics service that allows you to aggregate, visualize, and analyze live data streams in the cloud. ThingSpeak provides instant visualizations of data posted by your devices to ThingSpeak. With the ability to execute MATLAB® code in ThingSpeak, you can perform online analysis and process data as it comes in. ThingSpeak is often used for prototyping and proof-of-concept IoT systems that require analytics.

[SEA-MAT](https://sea-mat.github.io/sea-mat/) is a collaborative effort to organize and distribute Matlab tools for the Oceanographic Community.

[Gramm](https://github.com/piermorel/gramm) is a complete data visualization toolbox for Matlab. It provides an easy to use and high-level interface to produce publication-quality plots of complex data with varied statistical visualizations. Gramm is inspired by R's ggplot2 library.

[hctsa](https://hctsa-users.gitbook.io/hctsa-manual) is a software package for running highly comparative time-series analysis using Matlab.

[Plotly](https://plot.ly/matlab/) is a Graphing Library for MATLAB.

[YALMIP](https://yalmip.github.io/) is a MATLAB toolbox for optimization modeling.

[GNU Octave](https://www.gnu.org/software/octave/) is a high-level interpreted language, primarily intended for numerical computations. It provides capabilities for the numerical solution of linear and nonlinear problems, and for performing other numerical experiments. It also provides extensive graphics capabilities for data visualization and manipulation.

# C/C++ Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/146693483-c944138d-e703-4066-b19d-f2b0d9d69cbf.png">
  <br />
</p>

## C/C++ Learning Resources

[C++](https://www.cplusplus.com/doc/tutorial/) is a cross-platform language that can be used to build high-performance applications developed by Bjarne Stroustrup, as an extension to the C language.

[C](https://www.iso.org/standard/74528.html) is a general-purpose, high-level language that was originally developed by Dennis M. Ritchie to develop the UNIX operating system at Bell Labs. It supports structured programming, lexical variable scope, and recursion, with a static type system. C also provides constructs that map efficiently to typical machine instructions, which makes it one was of the most widely used programming languages today.

[Embedded C](https://en.wikipedia.org/wiki/Embedded_C) is a set of language extensions for the C programming language by the [C Standards Committee](https://isocpp.org/std/the-committee) to address issues that exist between C extensions for different [embedded systems](https://en.wikipedia.org/wiki/Embedded_system). The extensions hep enhance microprocessor features such as fixed-point arithmetic, multiple distinct memory banks, and basic I/O operations. This makes Embedded C the most popular embedded software language in the world.

[C & C++ Developer Tools from JetBrains](https://www.jetbrains.com/cpp/)

[Open source C++ libraries on cppreference.com](https://en.cppreference.com/w/cpp/links/libs)

[C++ Graphics libraries](https://cpp.libhunt.com/libs/graphics)

[C++ Libraries in MATLAB](https://www.mathworks.com/help/matlab/call-cpp-library-functions.html)

[C++ Tools and Libraries Articles](https://www.cplusplus.com/articles/tools/)

[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

[Introduction C++ Education course on Google Developers](https://developers.google.com/edu/c++/)

[C++ style guide for Fuchsia](https://fuchsia.dev/fuchsia-src/development/languages/c-cpp/cpp-style)

[C and C++ Coding Style Guide by OpenTitan](https://docs.opentitan.org/doc/rm/c_cpp_coding_style/)

[Chromium C++ Style Guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/c++/c++.md)

[C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md)

[C++ Style Guide for ROS](http://wiki.ros.org/CppStyleGuide)

[Learn C++](https://www.learncpp.com/)

[Learn C : An Interactive C Tutorial](https://www.learn-c.org/)

[C++ Institute](https://cppinstitute.org/free-c-and-c-courses)

[C++ Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/c-plus-plus)

[C++ Tutorials on W3Schools](https://www.w3schools.com/cpp/default.asp)

[Learn C Programming Online Courses on edX](https://www.edx.org/learn/c-programming)

[Learn C++ with Online Courses on edX](https://www.edx.org/learn/c-plus-plus)

[Learn C++ on Codecademy](https://www.codecademy.com/learn/learn-c-plus-plus)

[Coding for Everyone: C and C++ course on Coursera](https://www.coursera.org/specializations/coding-for-everyone)

[C++ For C Programmers on Coursera](https://www.coursera.org/learn/c-plus-plus-a)

[Top C Courses on Coursera](https://www.coursera.org/courses?query=c%20programming)

[C++ Online Courses on Udemy](https://www.udemy.com/topic/c-plus-plus/)

[Top C Courses on Udemy](https://www.udemy.com/topic/c-programming/)

[Basics of Embedded C Programming for Beginners on Udemy](https://www.udemy.com/course/embedded-c-programming-for-embedded-systems/)

[C++ For Programmers Course on Udacity](https://www.udacity.com/course/c-for-programmers--ud210)

[C++ Fundamentals Course on Pluralsight](https://www.pluralsight.com/courses/learn-program-cplusplus)

[Introduction to C++ on MIT Free Online Course Materials](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-096-introduction-to-c-january-iap-2011/)

[Introduction to C++ for Programmers | Harvard ](https://online-learning.harvard.edu/course/introduction-c-programmers)

[Online C Courses | Harvard University](https://online-learning.harvard.edu/subject/c)


## C/C++ Tools and Frameworks

[AWS SDK for C++](https://aws.amazon.com/sdk-for-cpp/)

[Azure SDK for C++](https://github.com/Azure/azure-sdk-for-cpp)

[Azure SDK for C](https://github.com/Azure/azure-sdk-for-c)

[C++ Client Libraries for Google Cloud Services](https://github.com/googleapis/google-cloud-cpp)

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Vcpkg](https://github.com/microsoft/vcpkg) is a C++ Library Manager for Windows, Linux, and MacOS.

[ReSharper C++](https://www.jetbrains.com/resharper-cpp/features/) is a Visual Studio Extension for C++ developers developed by JetBrains.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages. All code inspections are run on the fly.

[CLion](https://www.jetbrains.com/clion/features/) is a cross-platform IDE for C and C++ developers developed by JetBrains.

[Code::Blocks](https://www.codeblocks.org/) is a free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable. Built around a plugin framework, Code::Blocks can be extended with plugins.

[CppSharp](https://github.com/mono/CppSharp) is a tool and set of libraries which facilitates the usage of native C/C++ code with the .NET ecosystem. It consumes C/C++ header and library files and generates the necessary glue code to surface the native API as a managed API. Such an API can be used to consume an existing native library in your managed code or add managed scripting support to a native codebase.

[Conan](https://conan.io/) is an Open Source Package Manager for C++ development and dependency management into the 21st century and on par with the other development ecosystems.

[High Performance Computing (HPC) SDK](https://developer.nvidia.com/hpc) is a comprehensive toolbox for GPU accelerating HPC modeling and simulation applications. It includes the C, C++, and Fortran compilers, libraries, and analysis tools necessary for developing HPC applications on the NVIDIA platform.

[Thrust](https://github.com/NVIDIA/thrust) is a C++ parallel programming library which resembles the C++ Standard Library. Thrust's high-level interface greatly enhances programmer productivity while enabling performance portability between GPUs and multicore CPUs. Interoperability with established technologies such as CUDA, TBB, and OpenMP integrates with existing software.

[Boost](https://www.boost.org/) is an educational opportunity focused on cutting-edge C++. Boost has been a participant in the annual Google Summer of Code since 2007, in which students develop their skills by working on Boost Library development.

[Automake](https://www.gnu.org/software/automake/) is a tool for automatically generating Makefile.in files compliant with the GNU Coding Standards. Automake requires the use of GNU Autoconf.

[Cmake](https://cmake.org/) is an open-source, cross-platform family of tools designed to build, test and package software. CMake is used to control the software compilation process using simple platform and compiler independent configuration files, and generate native makefiles and workspaces that can be used in the compiler environment of your choice.

[GDB](http://www.gnu.org/software/gdb/) is a debugger, that allows you to see what is going on `inside' another program while it executes or what another program was doing at the moment it crashed.

[GCC](https://gcc.gnu.org/) is a compiler Collection that includes front ends for C, C++, Objective-C, Fortran, Ada, Go, and D, as well as libraries for these languages.

[GSL](https://www.gnu.org/software/gsl/) is a numerical library for C and C++ programmers. It is free software under the GNU General Public License. The library provides a wide range of mathematical routines such as random number generators, special functions and least-squares fitting. There are over 1000 functions in total with an extensive test suite.

[OpenGL Extension Wrangler Library (GLEW)](https://www.opengl.org/sdk/libs/GLEW/) is a cross-platform open-source C/C++ extension loading library. GLEW provides efficient run-time mechanisms for determining which OpenGL extensions are supported on the target platform.

[Libtool](https://www.gnu.org/software/libtool/) is a generic library support script that hides the complexity of using shared libraries behind a consistent, portable interface. To use Libtool, add the new generic library building commands to your Makefile, Makefile.in, or Makefile.am.

[Maven](https://maven.apache.org/) is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

[TAU (Tuning And Analysis Utilities)](http://www.cs.uoregon.edu/research/tau/home.php) is capable of gathering performance information through instrumentation of functions, methods, basic blocks, and statements as well as event-based sampling. All C++ language features are supported including templates and namespaces.

[Clang](https://clang.llvm.org/) is a production quality C, Objective-C, C++ and Objective-C++ compiler when targeting X86-32, X86-64, and ARM (other targets may have caveats, but are usually easy to fix). Clang is used in production to build performance-critical software like Google Chrome or Firefox.

[OpenCV](https://opencv.org/) is a highly optimized library with focus on real-time applications. Cross-Platform C++, Python and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Libcu++](https://nvidia.github.io/libcudacxx) is the NVIDIA C++ Standard Library for your entire system. It provides a heterogeneous implementation of the C++ Standard Library that can be used in and between CPU and GPU code.

[ANTLR (ANother Tool for Language Recognition)](https://www.antlr.org/) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build parse trees and also generates a listener interface that makes it easy to respond to the recognition of phrases of interest.

[Oat++](https://oatpp.io/) is a light and powerful C++ web framework for highly scalable and resource-efficient web application. It's zero-dependency and easy-portable.

[JavaCPP](https://github.com/bytedeco/javacpp) is a program that provides efficient access to native C++ inside Java, not unlike the way some C/C++ compilers interact with assembly language.

[Cython](https://cython.org/) is a language that makes writing C extensions for Python as easy as Python itself. Cython is based on Pyrex, but supports more cutting edge functionality and optimizations such as calling C functions and declaring C types on variables and class attributes.

[Spdlog](https://github.com/gabime/spdlog) is a very fast, header-only/compiled, C++ logging library.

[Infer](https://fbinfer.com/) is a static analysis tool for Java, C++, Objective-C, and C. Infer is written in [OCaml](https://ocaml.org/).

# Python Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93133273-ce490380-f68b-11ea-81d0-7f6a3debe6c0.png">
  <br />
</p>

## Python Learning Resources

[Python](https://www.python.org) is an interpreted, high-level programming language. Python is used heavily in the fields of Data Science and Machine Learning.

[Python Developer’s Guide](https://devguide.python.org) is a comprehensive resource for contributing to Python – for both new and experienced contributors. It is maintained by the same community that maintains Python.

[Azure Functions Python developer guide](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference-python) is an introduction to developing Azure Functions using Python. The content below assumes that you've already read the [Azure Functions developers guide](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference).

[CheckiO](https://checkio.org/) is a programming learning platform and a gamified website that teaches Python through solving code challenges and competing for the most elegant and creative solutions.

[Python Institute](https://pythoninstitute.org)

[PCEP – Certified Entry-Level Python Programmer certification](https://pythoninstitute.org/pcep-certification-entry-level/)

[PCAP – Certified Associate in Python Programming certification](https://pythoninstitute.org/pcap-certification-associate/)

[PCPP – Certified Professional in Python Programming 1 certification](https://pythoninstitute.org/pcpp-certification-professional/)

[PCPP – Certified Professional in Python Programming 2](https://pythoninstitute.org/pcpp-certification-professional/)

[MTA: Introduction to Programming Using Python Certification](https://docs.microsoft.com/en-us/learn/certifications/mta-introduction-to-programming-using-python)

[Getting Started with Python in Visual Studio Code](https://code.visualstudio.com/docs/python/python-tutorial)

[Google's Python Style Guide](https://google.github.io/styleguide/pyguide.html)

[Google's Python Education Class](https://developers.google.com/edu/python/)

[Real Python](https://realpython.com)

[The Python Open Source Computer Science Degree by Forrest Knight](https://github.com/ForrestKnight/open-source-cs-python)

[Intro to Python for Data Science](https://www.datacamp.com/courses/intro-to-python-for-data-science)

[Intro to Python by W3schools](https://www.w3schools.com/python/python_intro.asp)

[Codecademy's Python 3 course](https://www.codecademy.com/learn/learn-python-3)

[Learn Python with Online Courses and Classes from edX](https://www.edx.org/learn/python)

[Python Courses Online from Coursera](https://www.coursera.org/courses?query=python)

## Python Frameworks, Libraries, and Tools

[Python Package Index (PyPI)](https://pypi.org/) is a repository of software for the Python programming language. PyPI helps you find and install software developed and shared by the Python community.

[PyCharm](https://www.jetbrains.com/pycharm/) is the best IDE I've ever used. With PyCharm, you can access the command line, connect to a database, create a virtual environment, and manage your version control system all in one place, saving time by avoiding constantly switching between windows.

[Python Tools for Visual Studio(PTVS)](https://microsoft.github.io/PTVS/) is a free, open source plugin that turns Visual Studio into a Python IDE. It supports editing, browsing, IntelliSense, mixed Python/C++ debugging, remote Linux/MacOS debugging, profiling, IPython, and web development with Django and other frameworks.

[Django](https://www.djangoproject.com/) is a high-level Python Web framework that encourages rapid development and clean, pragmatic design.

[Flask](https://flask.palletsprojects.com/) is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries.

[Web2py](http://web2py.com/) is an open-source web application framework written in Python allowing allows web developers to program dynamic web content. One web2py instance can run multiple web sites using different databases.

[AWS Chalice](https://github.com/aws/chalice) is a framework for writing serverless apps in python. It allows you to quickly create and deploy applications that use AWS Lambda.

[Tornado](https://www.tornadoweb.org/) is a Python web framework and asynchronous networking library. Tornado uses a non-blocking network I/O, which can scale to tens of thousands of open connections.

[HTTPie](https://github.com/httpie/httpie) is a command line HTTP client that makes CLI interaction with web services as easy as possible. HTTPie is designed for testing, debugging, and generally interacting with APIs & HTTP servers.

[Scrapy](https://scrapy.org/) is a fast high-level web crawling and web scraping framework, used to crawl websites and extract structured data from their pages. It can be used for a wide range of purposes, from data mining to monitoring and automated testing.

[Sentry](https://sentry.io/) is a service that helps you monitor and fix crashes in realtime. The server is in Python, but it contains a full API for sending events from any language, in any application.

[Pipenv](https://github.com/pypa/pipenv) is a tool that aims to bring the best of all packaging worlds (bundler, composer, npm, cargo, yarn, etc.) to the Python world.

[Python Fire](https://github.com/google/python-fire) is a library for automatically generating command line interfaces (CLIs) from absolutely any Python object.

[Bottle](https://github.com/bottlepy/bottle) is a fast, simple and lightweight [WSGI](https://www.wsgi.org/) micro web-framework for Python. It is distributed as a single file module and has no dependencies other than the [Python Standard Library](https://docs.python.org/library/).

[CherryPy](https://cherrypy.org) is a minimalist Python object-oriented HTTP web framework.

[Sanic](https://github.com/huge-success/sanic) is a Python 3.6+ web server and web framework that's written to go fast.

[Pyramid](https://trypyramid.com) is a small and fast open source Python web framework. It makes real-world web application development and deployment more fun and more productive.

[TurboGears](https://turbogears.org) is a hybrid web framework able to act both as a Full Stack framework or as a Microframework.

[Falcon](https://falconframework.org/) is a reliable, high-performance Python web framework for building large-scale app backends and microservices with support for MongoDB, Pluggable Applications and autogenerated Admin.

[Neural Network Intelligence(NNI)](https://github.com/microsoft/nni) is an open source AutoML toolkit for automate machine learning lifecycle, including [Feature Engineering](https://github.com/microsoft/nni/blob/master/docs/en_US/FeatureEngineering/Overview.md), [Neural Architecture Search](https://github.com/microsoft/nni/blob/master/docs/en_US/NAS/Overview.md), [Model Compression](https://github.com/microsoft/nni/blob/master/docs/en_US/Compressor/Overview.md) and [Hyperparameter Tuning](https://github.com/microsoft/nni/blob/master/docs/en_US/Tuner/BuiltinTuner.md).

[Dash](https://plotly.com/dash) is a popular Python framework for building ML & data science web apps for Python, R, Julia, and Jupyter.

[Luigi](https://github.com/spotify/luigi) is a Python module that helps you build complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization etc. It also comes with Hadoop support built-in.

[Locust](https://github.com/locustio/locust) is an easy to use, scriptable and scalable performance testing tool.

[spaCy](https://github.com/explosion/spaCy) is a library for advanced Natural Language Processing in Python and Cython.

[NumPy](https://www.numpy.org/) is the fundamental package needed for scientific computing with Python.

[Pillow](https://python-pillow.org/) is a friendly PIL(Python Imaging Library) fork.

[IPython](https://ipython.org/) is a command shell for interactive computing in multiple programming languages, originally developed for the Python programming language, that offers enhanced introspection, rich media, additional shell syntax, tab completion, and rich history.

[GraphLab Create](https://turi.com/) is a Python library, backed by a C++ engine, for quickly building large-scale, high-performance machine learning models.

[Pandas](https://pandas.pydata.org/) is a fast, powerful, and easy to use open source data structrures, data analysis and manipulation tool, built on top of the Python programming language.

[PuLP](https://coin-or.github.io/pulp/) is an Linear Programming modeler written in python. PuLP can generate LP files and call on use highly optimized solvers, GLPK, COIN CLP/CBC, CPLEX, and GUROBI, to solve these linear problems.

[Matplotlib](https://matplotlib.org/) is a 2D plotting library for creating static, animated, and interactive visualizations in Python. Matplotlib produces publication-quality figures in a variety of hardcopy formats and interactive environments across platforms.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a simple and efficient tool for data mining and data analysis. It is built on NumPy,SciPy, and mathplotlib.

# Lua Development
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/99859431-e1bd9280-2b44-11eb-84f7-854d3e015e21.png">
  <br />
</p>

## Lua Learning Resources

[Lua](https://www.lua.org/) is a subset of the C programming language designed to be a lightweight embeddable scripting language used by many frameworks and games.

[Programming in Lua ebook](https://www.lua.org/pil/contents.html)

[Getting started with Lua](https://www.lua.org/start.html)

[Intro to Lua from Core Academy](https://learn.coregames.com/courses/intro-to-lua/)

[Online Lua Classes on Skillshare](https://www.skillshare.com/browse/lua)

[Online Lua Classes on Udemy](https://www.udemy.com/topic/lua/?ratings=4.0&sort=popularity)

[Lua Training Courses from Nobleprog](https://www.nobleprog.com/lua-training)

[RoboCode Academy from Roblox](https://corp.roblox.com/education/)

## Lua Tools, Libraries, and Frameworks

[Lua Language Server](https://github.com/sumneko/lua-language-server) is an extension for VSCode that provides support for the Lua Language Server.

[Apache APISIX](https://github.com/apache/apisix) is a dynamic, real-time, high-performance API gateway, based on the Nginx library and etcd.

[NodeMCU](https://github.com/nodemcu/nodemcu-firmware) is an open source Lua based firmware for the [ESP8266 WiFi SOC from Espressif](https://espressif.com/en/products/esp8266/) and uses an on-module flash-based [SPIFFS](https://github.com/pellepl/spiffs) file system.

[GopherLua](https://github.com/yuin/gopher-lua) is a Lua 5.1 VM and compiler written in Go.

[MoonScript](https://github.com/leafo/moonscript) is a programmer friendly language that compiles into Lua.

[Lapis](https://github.com/leafo/lapis) is a web framework for Lua/MoonScript supporting [OpenResty](https://openresty.org/en/) or [http.server](https://github.com/daurnimator/lua-http).

[Algernon](https://algernon.roboticoverlords.org) is a web server with built-in support for QUIC, HTTP/2, Lua, Markdown, Pongo2, HyperApp, Amber, Sass(SCSS), GCSS, JSX, BoltDB (built-in, stores the database in a file, like SQLite), Redis, PostgreSQL, MariaDB/MySQL, rate limiting, graceful shutdown, plugins, users and permissions.

[Lua Fun](https://luafun.github.io/) is a high-performance functional programming library for Lua designed with LuaJIT's trace compiler in mind.

[Luakit](https://luakit.github.io/) is a fast, light and simple to use micro-browser framework extensible by Lua using the WebKit web content engine and the GTK+ toolkit.

[Lua Resty HTTP](https://github.com/ledgetech/lua-resty-http) is an HTTP client cosocket driver for [OpenResty](https://openresty.org/en/)/ [ngx_lua](https://github.com/openresty/lua-nginx-module).

[NLua](https://github.com/NLua/NLua) is a bridge between Lua world and the .NET (compatible with .NET Core/UWP/Mac/Linux/Android/iOS/tvOS).

# Networking
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/82833053-d1687b80-9e71-11ea-8c6d-074100f2f54b.png">
  <br />
</p>

## Networking Tools & Concepts

[cURL](https://curl.se/) is a computer software project providing a library and command-line tool for transferring data using various network protocols(HTTP, HTTPS, FTP, FTPS, SCP, SFTP, TFTP, DICT, TELNET, LDAP LDAPS, MQTT, POP3, POP3S, RTMP, RTMPS, RTSP, SCP, SFTP, SMB, SMBS, SMTP or SMTPS). cURL is also used in cars, television sets, routers, printers, audio equipment, mobile phones, tablets, settop boxes, media players and is the Internet transfer engine for thousands of software applications in over ten billion installations.

[cURL Fuzzer](https://github.com/curl/curl-fuzzer) is a quality assurance testing for the curl project.

[DoH](https://github.com/curl/doh) is a stand-alone application for DoH (DNS-over-HTTPS) name resolves and lookups.

[Authelia](https://www.authelia.com/) is an open-source highly-available authentication server providing single sign-on capability and two-factor authentication to applications running behind [NGINX](https://nginx.org/en/).

[nginx(engine x)](https://nginx.org/en/) is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server, originally written by Igor Sysoev.

[Proxmox Virtual Environment(VE)](https://www.proxmox.com/en/) is a complete open-source platform for enterprise virtualization. It inlcudes a built-in web interface that you can easily manage VMs and containers, software-defined storage and networking, high-availability clustering, and multiple out-of-the-box tools on a single solution.

[Wireshark](https://www.wireshark.org/) is a very popular network protocol analyzer that is commonly used for network troubleshooting, analysis, and communications protocol development. Learn more about the other useful [Wireshark Tools](https://wiki.wireshark.org/Tools) available.

[HTTPie](https://github.com/httpie/httpie) is a command-line HTTP client. Its goal is to make CLI interaction with web services as human-friendly as possible. HTTPie is designed for testing, debugging, and generally interacting with APIs & HTTP servers.

[HTTPStat](https://github.com/reorx/httpstat) is a tool that visualizes curl statistics in a simple layout.

[Wuzz](https://github.com/asciimoo/wuzz) is an interactive cli tool for HTTP inspection. It can be used to inspect/modify requests copied from the browser's network inspector with the "copy as cURL" feature.

[Websocat](https://github.com/vi/websocat) is a ommand-line client for WebSockets, like netcat (or curl) for ws:// with advanced socat-like functions.

    • Connection: In networking, a connection refers to pieces of related information that are transferred through a network. This generally infers that a connection is built before the data transfer (by following the procedures laid out in a protocol) and then is deconstructed at the at the end of the data transfer.

    • Packet: A packet is, generally speaking, the most basic unit that is transferred over a network. When communicating over a network, packets are the envelopes that carry your data (in pieces) from one end point to the other.

Packets have a header portion that contains information about the packet including the source and destination, timestamps, network hops. The main portion of a packet contains the actual data being transferred. It is sometimes called the body or the payload.

    • Network Interface: A network interface can refer to any kind of software interface to networking hardware. For instance, if you have two network cards in your computer, you can control and configure each network interface associated with them individually.

A network interface may be associated with a physical device, or it may be a representation of a virtual interface. The "loop-back" device, which is a virtual interface to the local machine, is an example of this.

    • LAN: LAN stands for "local area network". It refers to a network or a portion of a network that is not publicly accessible to the greater internet. A home or office network is an example of a LAN.

    • WAN: WAN stands for "wide area network". It means a network that is much more extensive than a LAN. While WAN is the relevant term to use to describe large, dispersed networks in general, it is usually meant to mean the internet, as a whole.
If an interface is connected to the WAN, it is generally assumed that it is reachable through the internet.

    • Protocol: A protocol is a set of rules and standards that basically define a language that devices can use to communicate. There are a great number of protocols in use extensively in networking, and they are often implemented in different layers.

Some low level protocols are TCP, UDP, IP, and ICMP. Some familiar examples of application layer protocols, built on these lower protocols, are HTTP (for accessing web content), SSH, TLS/SSL, and FTP.

    • Port: A port is an address on a single machine that can be tied to a specific piece of software. It is not a physical interface or location, but it allows your server to be able to communicate using more than one application.

    • Firewall: A firewall is a program that decides whether traffic coming into a server or going out should be allowed. A firewall usually works by creating rules for which type of traffic is acceptable on which ports. Generally, firewalls block ports that are not used by a specific application on a server.

    • NAT: Network address translation is a way to translate requests that are incoming into a routing server to the relevant devices or servers that it knows about in the LAN. This is usually implemented in physical LANs as a way to route requests through one IP address to the necessary backend servers.

    • VPN: Virtual private network is a means of connecting separate LANs through the internet, while maintaining privacy. This is used as a means of connecting remote systems as if they were on a local network, often for security reasons.

## Network Layers

	While networking is often discussed in terms of topology in a horizontal way, between hosts, its implementation is layered in a vertical fashion throughout a computer or network. This means is that there are multiple technologies and protocols that are built on top of each other in order for communication to function more easily. Each successive, higher layer abstracts the raw data a little bit more, and makes it simpler to use for applications and users. It also allows you to leverage lower layers in new ways without having to invest the time and energy to develop the protocols and applications that handle those types of traffic.

	As data is sent out of one machine, it begins at the top of the stack and filters downwards. At the lowest level, actual transmission to another machine takes place. At this point, the data travels back up through the layers of the other computer. Each layer has the ability to add its own "wrapper" around the data that it receives from the adjacent layer, which will help the layers that come after decide what to do with the data when it is passed off.

	One method of talking about the different layers of network communication is the OSI model. OSI stands for Open Systems Interconnect.This model defines seven separate layers. The layers in this model are:

    • Application: The application layer is the layer that the users and user-applications most often interact with. Network communication is discussed in terms of availability of resources, partners to communicate with, and data synchronization.

    • Presentation: The presentation layer is responsible for mapping resources and creating context. It is used to translate lower level networking data into data that applications expect to see.

    • Session: The session layer is a connection handler. It creates, maintains, and destroys connections between nodes in a persistent way.

    • Transport: The transport layer is responsible for handing the layers above it a reliable connection. In this context, reliable refers to the ability to verify that a piece of data was received intact at the other end of the connection. This layer can resend information that has been dropped or corrupted and can acknowledge the receipt of data to remote computers.

    • Network: The network layer is used to route data between different nodes on the network. It uses addresses to be able to tell which computer to send information to. This layer can also break apart larger messages into smaller chunks to be reassembled on the opposite end.

    • Data Link: This layer is implemented as a method of establishing and maintaining reliable links between different nodes or devices on a network using existing physical connections.

    • Physical: The physical layer is responsible for handling the actual physical devices that are used to make a connection. This layer involves the bare software that manages physical connections as well as the hardware itself (like Ethernet).

The TCP/IP model, more commonly known as the Internet protocol suite, is another layering model that is simpler and has been widely adopted.It defines the four separate layers, some of which overlap with the OSI model:

    • Application: In this model, the application layer is responsible for creating and transmitting user data between applications. The applications can be on remote systems, and should appear to operate as if locally to the end user.
The communication takes place between peers network.

    • Transport: The transport layer is responsible for communication between processes. This level of networking utilizes ports to address different services. It can build up unreliable or reliable connections depending on the type of protocol used.

    • Internet: The internet layer is used to transport data from node to node in a network. This layer is aware of the endpoints of the connections, but does not worry about the actual connection needed to get from one place to another. IP addresses are defined in this layer as a way of reaching remote systems in an addressable manner.

    • Link: The link layer implements the actual topology of the local network that allows the internet layer to present an addressable interface. It establishes connections between neighboring nodes to send data.

### Interfaces
**Interfaces** are networking communication points for your computer. Each interface is associated with a physical or virtual networking device. Typically, your server will have one configurable network interface for each Ethernet or wireless internet card you have. In addition, it will define a virtual network interface called the "loopback" or localhost interface. This is used as an interface to connect applications and processes on a single computer to other applications and processes. You can see this referenced as the "lo" interface in many tools.

## Network Protocols

Networking works by piggybacks on a number of different protocols on top of each other. In this way, one piece of data can be transmitted using multiple protocols encapsulated within one another.

**Media Access Control(MAC)** is a communications protocol that is used to distinguish specific devices. Each device is supposed to get a unique MAC address during the manufacturing process that differentiates it from every other device on the internet. Addressing hardware by the MAC address allows you to reference a device by a unique value even when the software on top may change the name for that specific device during operation. Media access control is one of the only protocols from the link layer that you are likely to interact with on a regular basis.

**The IP protocol** is one of the fundamental protocols that allow the internet to work. IP addresses are unique on each network and they allow machines to address each other across a network. It is implemented on the internet layer in the IP/TCP model. Networks can be linked together, but traffic must be routed when crossing network boundaries. This protocol assumes an unreliable network and multiple paths to the same destination that it can dynamically change between. There are a number of different implementations of the protocol. The most common implementation today is IPv4, although IPv6 is growing in popularity as an alternative due to the scarcity of IPv4 addresses available and improvements in the protocols capabilities.

**ICMP: internet control message protocol** is used to send messages between devices to indicate the availability or error conditions. These packets are used in a variety of network diagnostic tools, such as ping and traceroute. Usually ICMP packets are transmitted when a packet of a different kind meets some kind of a problem. Basically, they are used as a feedback mechanism for network communications.

**TCP: Transmission control protocol** is implemented in the transport layer of the IP/TCP model and is used to establish reliable connections. TCP is one of the protocols that encapsulates data into packets. It then transfers these to the remote end of the connection using the methods available on the lower layers. On the other end, it can check for errors, request certain pieces to be resent, and reassemble the information into one logical piece to send to the application layer. The protocol builds up a connection prior to data transfer using a system called a three-way handshake. This is a way for the two ends of the communication to acknowledge the request and agree upon a method of ensuring data reliability. After the data has been sent, the connection is torn down using a similar four-way handshake. TCP is the protocol of choice for many of the most popular uses for the internet, including WWW, FTP, SSH, and email. It is safe to say that the internet we know today would not be here without TCP.

**UDP: User datagram protocol** is a popular companion protocol to TCP and is also implemented in the transport layer. The fundamental difference between UDP and TCP is that UDP offers unreliable data transfer. It does not verify that data has been received on the other end of the connection. This might sound like a bad thing, and for many purposes, it is. However, it is also extremely important for some functions. It’s not required to wait for confirmation that the data was received and forced to resend data, UDP is much faster than TCP. It does not establish a connection with the remote host, it simply fires off the data to that host and doesn't care if it is accepted or not. Since UDP is a simple transaction, it is useful for simple communications like querying for network resources. It also doesn't maintain a state, which makes it great for transmitting data from one machine to many real-time clients. This makes it ideal for VOIP, games, and other applications that cannot afford delays.

**HTTP: Hypertext transfer protocol** is a protocol defined in the application layer that forms the basis for communication on the web. HTTP defines a number of functions that tell the remote system what you are requesting. For instance, GET, POST, and DELETE all interact with the requested data in a different way.

**FTP: File transfer protocol** is in the application layer and provides a way of transferring complete files from one host to another. It is inherently insecure, so it is not recommended for any externally facing network unless it is implemented as a public, download-only resource.

**DNS: Domain name system** is an application layer protocol used to provide a human-friendly naming mechanism for internet resources. It is what ties a domain name to an IP address and allows you to access sites by name in your browser.

**SSH: Secure shell** is an encrypted protocol implemented in the application layer that can be used to communicate with a remote server in a secure way. Many additional technologies are built around this protocol because of its end-to-end encryption and ubiquity. There are many other protocols that we haven't covered that are equally important. However, this should give you a good overview of some of the fundamental technologies that make the internet and networking possible.

[REST(REpresentational State Transfer)](https://www.codecademy.com/articles/what-is-rest) is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other.

[JSON Web Token (JWT)](https://jwt.io) is a compact URL-safe means of representing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is digitally signed using JSON Web Signature (JWS).

[OAuth 2.0](https://oauth.net/2/) is an open source authorization framework that enables applications to obtain limited access to user accounts on an HTTP service, such as Amazon, Google, Facebook, Microsoft, Twitter GitHub, and DigitalOcean. It works by delegating user authentication to the service that hosts the user account, and authorizing third-party applications to access the user account.

# Databases
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119279004-daec0700-bbdd-11eb-9662-b1fc86ec8448.png">
  <br />
</p>

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119279002-da537080-bbdd-11eb-9d7a-44efb52f3506.png">
  <br />
</p>

## SQL/NoSQL Learning Resources

[SQL](https://en.wikipedia.org/wiki/SQL) is a standard language for storing, manipulating and retrieving data in relational databases.

[NoSQL](https://www.ibm.com/cloud/blog/sql-vs-nosql) is a database that is interchangeably referred to as "nonrelational, or "non-SQL" to highlight that the database can handle huge volumes of rapidly changing, unstructured data in different ways than a relational (SQL-based) database with rows and tables.

[Transact-SQL(T-SQL)](https://docs.microsoft.com/en-us/sql/t-sql/language-reference) is a Microsoft extension of SQL with all of the tools and applications communicating to a SQL database by sending T-SQL commands.

[Introduction to Transact-SQL](https://docs.microsoft.com/en-us/learn/modules/introduction-to-transact-sql/)

[SQL Tutorial by W3Schools](https://www.w3schools.com/sql/)

[Learn SQL Skills Online from Coursera](https://www.coursera.org/courses?query=sql)

[SQL Courses Online from Udemy](https://www.udemy.com/topic/sql/)

[SQL Online Training Courses from LinkedIn Learning](https://www.linkedin.com/learning/topics/sql)

[Learn SQL For Free from Codecademy](https://www.codecademy.com/learn/learn-sql)

[GitLab's SQL Style Guide](https://about.gitlab.com/handbook/business-ops/data-team/platform/sql-style-guide/)

[OracleDB SQL Style Guide Basics](https://oracle.readthedocs.io/en/latest/sql/basics/style-guide.html)

[Tableau CRM: BI Software and Tools](https://www.salesforce.com/products/crm-analytics/overview/)

[Databases on AWS](https://aws.amazon.com/products/databases/)

[Best Practices and Recommendations for SQL Server Clustering in AWS EC2.](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/aws-sql-clustering.html)

[Connecting from Google Kubernetes Engine to a Cloud SQL instance.](https://cloud.google.com/sql/docs/mysql/connect-kubernetes-engine)

[Educational Microsoft Azure SQL resources](https://docs.microsoft.com/en-us/sql/sql-server/educational-sql-resources?view=sql-server-ver15)

[MySQL Certifications](https://www.mysql.com/certification/)

[SQL vs. NoSQL Databases: What's the Difference?](https://www.ibm.com/cloud/blog/sql-vs-nosql)

[What is NoSQL?](https://aws.amazon.com/nosql/)

## SQL/NoSQL Tools and Databases

[Netdata](https://github.com/netdata/netdata) is high-fidelity infrastructure monitoring and troubleshooting, real-time monitoring Agent collects thousands of metrics from systems, hardware, containers, and applications with zero configuration. It runs permanently on all your physical/virtual servers, containers, cloud deployments, and edge/IoT devices, and is perfectly safe to install on your systems mid-incident without any preparation.

[Azure Data Studio](https://github.com/Microsoft/azuredatastudio) is an open source data management tool that enables working with SQL Server, Azure SQL DB and SQL DW from Windows, macOS and Linux.

[Azure SQL Database](https://azure.microsoft.com/en-us/services/sql-database/)  is the intelligent, scalable, relational database service built for the cloud. It’s evergreen and always up to date, with AI-powered and automated features that optimize performance and durability for you. Serverless compute and Hyperscale storage options automatically scale resources on demand, so you can focus on building new applications without worrying about storage size or resource management.

[Azure SQL Managed Instance](https://azure.microsoft.com/en-us/services/azure-sql/sql-managed-instance/) is a fully managed SQL Server Database engine instance that's hosted in Azure and placed in your network. This deployment model makes it easy to lift and shift your on-premises applications to the cloud with very few application and database changes. Managed instance has split compute and storage components.

[Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/) is a limitless analytics service that brings together enterprise data warehousing and Big Data analytics. It gives you the freedom to query data on your terms, using either serverless or provisioned resources at scale. It brings together the best of the SQL technologies used in enterprise data warehousing, Spark technologies used in big data analytics, and Pipelines for data integration and ETL/ELT.

[MSSQL for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql) is an extension for developing Microsoft SQL Server, Azure SQL Database and SQL Data Warehouse everywhere with a rich set of functionalities.

[SQL Server Data Tools (SSDT)](https://docs.microsoft.com/en-us/sql/ssdt/download-sql-server-data-tools-ssdt) is a development tool for building SQL Server relational databases, Azure SQL Databases, Analysis Services (AS) data models, Integration Services (IS) packages, and Reporting Services (RS) reports. With SSDT, a developer can design and deploy any SQL Server content type with the same ease as they would develop an application in Visual Studio or Visual Studio Code.

[Bulk Copy Program](https://docs.microsoft.com/en-us/sql/tools/bcp-utility) is a command-line tool that comes with Microsoft SQL Server. BCP, allows you to import and export large amounts of data in and out of SQL Server databases quickly snd efficeiently.

[SQL Server Migration Assistant](https://www.microsoft.com/en-us/download/details.aspx?id=54258) is a tool from Microsoft that simplifies database migration process from Oracle to SQL Server, Azure SQL Database, Azure SQL Database Managed Instance and Azure SQL Data Warehouse.

[SQL Server Integration Services](https://docs.microsoft.com/en-us/sql/integration-services/sql-server-integration-services?view=sql-server-ver15) is a development platform for building enterprise-level data integration and data transformations solutions. Use Integration Services to solve complex business problems by copying or downloading files, loading data warehouses, cleansing and mining data, and managing SQL Server objects and data.

[SQL Server Business Intelligence(BI)](https://www.microsoft.com/en-us/sql-server/sql-business-intelligence) is a collection of tools in Microsoft's SQL Server for transforming raw data into information businesses can use to make decisions.

[Tableau](https://www.tableau.com/) is a Data Visualization software used in relational databases, cloud databases, and spreadsheets. Tableau was acquired by [Salesforce in August 2019](https://investor.salesforce.com/press-releases/press-release-details/2019/Salesforce-Completes-Acquisition-of-Tableau/default.aspx).

[DataGrip](https://www.jetbrains.com/datagrip/) is a professional DataBase IDE developed by Jet Brains that provides context-sensitive code completion, helping you to write SQL code faster. Completion is aware of the tables structure, foreign keys, and even database objects created in code you're editing.

[RStudio](https://rstudio.com/) is an integrated development environment for R and Python, with a console, syntax-highlighting editor that supports direct code execution, and tools for plotting, history, debugging and workspace management.

[MySQL](https://www.mysql.com/) is a fully managed database service to deploy cloud-native applications using the world's most popular open source database.

[PostgreSQL](https://www.postgresql.org/) is a powerful, open source object-relational database system with over 30 years of active development that has earned it a strong reputation for reliability, feature robustness, and performance.

[Amazon DynamoDB](https://aws.amazon.com/dynamodb/) is a key-value and document database that delivers single-digit millisecond performance at any scale. It is a fully managed, multiregion, multimaster, durable database with built-in security, backup and restore, and in-memory caching for internet-scale applications.

[Apache Cassandra™](https://cassandra.apache.org/) is an open source NoSQL distributed database trusted by thousands of companies for scalability and high availability without compromising performance. Cassandra provides linear scalability and proven fault-tolerance on commodity hardware or cloud infrastructure make it the perfect platform for mission-critical data.

[Apache HBase™](https://hbase.apache.org/) is an open-source, NoSQL, distributed big data store. It enables random, strictly consistent, real-time access to petabytes of data. HBase is very effective for handling large, sparse datasets. HBase serves as a direct input and output to the Apache MapReduce framework for Hadoop, and works with Apache Phoenix to enable SQL-like queries over HBase tables.

[Hadoop Distributed File System (HDFS)](https://www.ibm.com/analytics/hadoop/hdfs) is a distributed file system that handles large data sets running on commodity hardware. It is used to scale a single Apache Hadoop cluster to hundreds (and even thousands) of nodes. HDFS is one of the major components of Apache Hadoop, the others being [MapReduce](https://www.ibm.com/analytics/hadoop/mapreduce) and [YARN](https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html).

[Apache Mesos](http://mesos.apache.org/) is a cluster manager that provides efficient resource isolation and sharing across distributed applications, or frameworks. It can run Hadoop, Jenkins, Spark, Aurora, and other frameworks on a dynamically shared pool of nodes.

[Apache Spark](https://spark.apache.org/) is a unified analytics engine for big data processing, with built-in modules for streaming, SQL, machine learning and graph processing.

[ElasticSearch](https://www.elastic.co/) is a search engine based on the Lucene library. It provides a distributed, multitenant-capable full-text search engine with an HTTP web interface and schema-free JSON documents. Elasticsearch is developed in Java.

[Logstash](https://www.elastic.co/products/logstash) is a tool for managing events and logs. When used generically, the term encompasses a larger system of log collection, processing, storage and searching activities.

[Kibana](https://www.elastic.co/products/kibana) is an open source data visualization plugin for Elasticsearch. It provides visualization capabilities on top of the content indexed on an Elasticsearch cluster. Users can create bar, line and scatter plots, or pie charts and maps on top of large volumes of data.

[Trino](https://trino.io/) is a Distributed SQL query engine for big data. It is able to tremendously speed up [ETL processes](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/etl), allow them all to use standard SQL statement, and work with numerous data sources and targets all in the same system.

[Extract, transform, and load (ETL)](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/etl) is a data pipeline used to collect data from various sources, transform the data according to business rules, and load it into a destination data store.

[Redis(REmote DIctionary Server)](https://redis.io/) is an open source (BSD licensed), in-memory data structure store, used as a database, cache, and message broker. It provides data structures such as strings, hashes, lists, sets, sorted sets with range queries, bitmaps, hyperloglogs, geospatial indexes, and streams.

[FoundationDB](https://www.foundationdb.org/) is an open source distributed database designed to handle large volumes of structured data across clusters of commodity servers. It organizes data as an ordered key-value store and employs ACID transactions for all operations. It is especially well-suited for read/write workloads but also has excellent performance for write-intensive workloads. FoundationDB was acquired by [Apple in 2015](https://techcrunch.com/2015/03/24/apple-acquires-durable-database-company-foundationdb/).

[IBM DB2](https://www.ibm.com/analytics/db2) is a collection of hybrid data management products offering a complete suite of AI-empowered capabilities designed to help you manage both structured and unstructured data on premises as well as in private and public cloud environments. Db2 is built on an intelligent common SQL engine designed for scalability and flexibility.

[MongoDB](https://www.mongodb.com/) is a document database meaning it stores data in JSON-like documents.

[OracleDB](https://www.oracle.com/database/) is a powerful fully managed database helps developers manage business-critical data with the highest availability, reliability, and security.

[MariaDB](https://mariadb.com/) is an enterprise open source database solution for modern, mission-critical applications.

[SQLite](https://sqlite.org/index.html) is a C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.SQLite is the most used database engine in the world. SQLite is built into all mobile phones and most computers and comes bundled inside countless other applications that people use every day.

[SQLite Database Browser](https://sqlitebrowser.org/) is an open source SQL tool that allows users to create, design and edits SQLite database files. It lets users show a log of all the SQL commands that have been issued by them and by the application itself.

[InfluxDB](https://www.influxdata.com/) is an open source time series platform.  This includes APIs for storing and querying data, processing it in the background for [ETL](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/etl) or monitoring and alerting purposes, user dashboards, Internet of Things sensor data, and visualizing and exploring the data and more. It also has support for processing data from [Graphite](http://graphiteapp.org/).

[Atlas](https://github.com/Netflix/atlas) is an in-memory dimensional [time series database](https://en.wikipedia.org/wiki/Time_series_database).

[CouchbaseDB](https://www.couchbase.com/) is an open source distributed [multi-model NoSQL document-oriented database](https://en.wikipedia.org/wiki/Multi-model_database). It creates a key-value store with managed cache for sub-millisecond data operations, with purpose-built indexers for efficient queries and a powerful query engine for executing SQL queries.

[dbWatch](https://www.dbwatch.com/) is a complete database monitoring/management solution for SQL Server, Oracle, PostgreSQL, Sybase, MySQL and Azure. Designed for proactive management and automation of routine maintenance in large scale on-premise, hybrid/cloud database environments.

[Cosmos DB Profiler](https://hibernatingrhinos.com/products/cosmosdbprof) is a real-time visual debugger allowing a development team to gain valuable insight and perspective into their usage of Cosmos DB database. It identifies over a dozen suspicious behaviors from your application’s interaction with Cosmos DB.

[Adminer](https://www.adminer.org/) is an SQL management client tool for managing databases, tables, relations, indexes, users. Adminer has support for all the popular database management systems such as MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Firebird, SimpleDB, Elasticsearch and MongoDB.

[DBeaver](https://dbeaver.io/) is an open source database tool for developers and database administrators. It offers supports for JDBC compliant databases such as MySQL, Oracle, IBM DB2, SQL Server, Firebird, SQLite, Sybase, Teradata, Firebird, Apache Hive, Phoenix, and Presto.

[DbVisualizer](https://dbvis.com/) is a SQL management tool that allows users to manage a wide range of databases such as Oracle, Sybase, SQL Server, MySQL, H3, and SQLite.

[AppDynamics Database](https://www.appdynamics.com/supported-technologies/database) is a management product for Microsoft SQL Server. With AppDynamics you can monitor and trend key performance metrics such as resource consumption, database objects, schema statistics and more, allowing you to proactively tune and fix issues in a High-Volume Production Environment.

[Toad](https://www.quest.com/toad/) is a SQL Server DBMS toolset developed by Quest. It increases productivity by using extensive automation, intuitive workflows, and built-in expertise. This SQL management tool resolve issues, manage change and promote the highest levels of code quality for both relational and non-relational databases.

[Lepide SQL Server](https://www.lepide.com/sql-storage-manager/) is an open source storage manager utility to analyse the performance of SQL Servers. It provides a complete overview of all configuration and permission changes being made to your SQL Server environment through an easy-to-use, graphical user interface.

[Sequel Pro](https://sequelpro.com/) is a fast MacOS database management tool for working with MySQL. This SQL management tool helpful for interacting with your database by easily to adding new databases, new tables, and new rows.


## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Unreal-Engine-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/Unreal-Engine-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).

