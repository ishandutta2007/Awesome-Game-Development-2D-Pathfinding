# Awesome-Game-Development-2D-Pathfinding

<p align="center">

  <img src="./assets/banner.svg" alt="Top Game Development & 2D Pathfinding" width="100%" />

</p>



<p align="center">

  <a href="https://github.com"><img src="https://shields.io" alt="Awesome"/></a>

  <a href="https://discord.gg"><img src="https://shields.io" alt="Discord" /></a>

  <a href="https://github.com"><img src="https://shields.io" alt="GitHub stars" /></a>

  <a href="https://github.com"><img src="https://shields.io" alt="GitHub forks" /></a>

  <a href="https://github.com"><img alt="GitHub followers" src="https://shields.io" /></a>

</p>



# 🧭 Top Game Development & 2D Pathfinding



**Curated List of Commercial/Engine Suites & Open-Source GitHub Projects**  

*Focused on Grid/Hex A*, Jump Point Search (JPS+), Flow Fields, Recast/Detour NavMesh, RVO2 Crowd Avoidance & Pixel-Level 2D Navigation*  

**Last updated: November 2026**



This repository tracks notable **Commercial/Engine platforms** and **open-source projects** for **Game Development & 2D Pathfinding**. These tools power grid, hex, and pixel-accurate 2D pathfinding (`A*`, `Dijkstra`, `Theta*`, `JPS+`, `Flow Fields`), polygon navigation meshes (`Recast & Detour`, `Polyanya`), reciprocal velocity obstacle (RVO2/ORCA) multi-agent crowd avoidance, and built-in engine navigation suites for indie game developers, AI gameplay engineers, and RTS/roguelike creators.



**Examples** include Unreal AI Navigation (Epic Games), Unity NavMesh & AI Navigation, A* Pathfinding Project Pro (Aron Granberg), Godot NavigationServer, Recast Navigation (Commercial/Engine Integrations), JPS+ (Jump Point Search Plus), PathFinding.js, MicroPather, PathLib, and GridPath (the category leaders).



**🚀 Open-source emphasis**: This section is heavily expanded with every major active project for pixel/grid 2D pathfinding (`pixel-path`, `PathFinding.js`, `EasyStar.js`, `python-pathfinding`, `pathfinding` Rust, `GridPath`), navmesh & polygon navigation (`Recast & Detour`, `NavMesh2D`, `Polyanya`, `Godot Navigation`), and multi-agent crowd steering (`RVO2 / ORCA`, `OpenSteer`, `Boids`) — ideal for game developers building fast, deterministic 2D/2.5D navigation without commercial middleware fees.



🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)

- [☁️ Commercial / Engine-Integrated Platforms](#️-commercial--engine-integrated-platforms)

- [💻 Open-Source GitHub Projects](#-open-source-github-projects)

- [🛠️ How to Contribute](#️-how-to-contribute)

- [⚠️ Disclaimer](#️-disclaimer)

- [💖 Support & Thank You](#-support--thank-you)



## 📊 Sector Overview & Market Dynamics



The global Game Engine & Middleware Development Software market is valued at approximately **$5.4B–$6.8B+ in 2026**, expanding at a ~14%–18% CAGR driven by indie 2D/roguelike hits, massive RTS/simulation crowd counts, and AI-assisted gameplay systems. The core engine layer exhibits **strong winner-take-most consolidation** around Unity, Unreal Engine, and open-source Godot, whereas the specialized 2D pathfinding, grid search, and crowd-avoidance middleware layer is **overwhelmingly open-source and language-native** (`Recast & Detour`, `PathFinding.js`, `RVO2`, `pathfinding` Rust, `EasyStar.js`), complemented by premier indie plugins like *A* Pathfinding Project Pro*.



## ☁️ Commercial / Engine-Integrated Platforms



*Sorted descending by company valuation / annual revenue scale.*



| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Trial Limit |

| :--- | :--- | :--- | :--- | :--- |

| **[Unreal AI Navigation (Epic Games)](https://unrealengine.com)** | Built-in Recast/Detour NavMesh, NavLinks, Environment Query System (EQS), and MassEntity crowd avoidance inside Unreal Engine 5. | **~$22.5B+ Valuation** (~$6B+ annual revenue; backed by Tencent/Sony/Disney) | **5% gross royalty** only after a commercial game exceeds **$1,000,000** lifetime gross revenue | **100% Free Forever** (Full C++ source access, Recast NavMesh, and EQS AI navigation up to **$1M lifetime revenue**) |

| **[Unity NavMesh & AI Navigation](https://unity.com)** | Official Unity `com.unity.ai.navigation` package providing runtime NavMesh baking, NavMeshAgents, Off-Mesh Links, and 2D NavMeshPlus workflows. | **~$1.8B+ Annual Revenue** (~$8B–$10B public market cap) | **$2,040 / seat / year** ($185/mo) for Unity Pro (required once revenue/funding exceeds $200k/yr) | **Forever Free Unity Personal** (100% free full Unity Engine and AI Navigation package for developers/studios under **$200k annual revenue**) |

| **[A* Pathfinding Project Pro (Aron Granberg)](https://arongranberg.com)** | Gold-standard Unity pathfinding suite featuring multithreaded Burst/Jobs Grid, Layered Grid, Recast, and Point graphs plus RVO2 local avoidance. | **Flagship Indie Unity Asset Studio** (15+ years in production; >15,000 commercial studios) | **$125 one-time license** on the Unity Asset Store (includes full C# source code and RVO2 crowd avoidance) | **Forever Free Base Edition** (Free downloadable A* Pathfinding Project Free version with Grid & Point graphs for Unity) |

| **[JPS+ with Goal Bounding (Steve Rabin / Commercial SDKs)](https://gameaipro.com)** | Ultra-fast Jump Point Search Plus precomputed symmetry-breaking grid pathfinding algorithm achieving 100x+ speedups over standard A*. | **Industry Algorithm / Academic & Studio Standard** (DigiPen / Game AI Pro) | **$0 / Open Algorithm** (Available in open-source C++/C# implementations and custom studio engines) | **100% Free Open Algorithm** (Royalty-free algorithm specification and open reference implementations on GitHub) |

| **[Godot Navigation (`NavigationServer2D` / `3D`)](https://godotengine.org)** | Native, high-performance 2D and 3D navigation server built directly into Godot 4 featuring `NavigationRegion2D`, obstacle avoidance (RVO2), and runtime baking. | **Non-Profit Open-Source Foundation** (Godot Foundation; >$1M+ annual sponsorships) | **$0 / Free Open-Source** (Optional Patreon/Foundation sponsorship tiers) | **100% Free Forever** (MIT-licensed, zero royalties, zero seat fees, and full native 2D polygon NavMesh + RVO2 avoidance) |

| **[Recast Navigation (Engine & Middleware Integrations)](https://recastnav.com)** | Industry-standard automated navigation-mesh generation and Detour crowd pathfinding toolkit embedded across Unreal, Unity, Godot, and O3DE. | **Open-Source Industry Standard** (Created by Mikko Mononen; Zlib-licensed) | **$0 / Free Open-Source** (Used commercially in thousands of AAA and indie titles with zero licensing fees) | **100% Free Forever** (Permissive Zlib license allowing unrestricted proprietary and open-source commercial use) |

| **[PathFinding.js (Hosted Visual Demo & Web Ecosystem)](https://github.io)** | Interactive browser-based 2D grid pathfinding visualizer and JavaScript library comparing A*, IDA*, Jump Point Search, Dijkstra, and Theta*. | **Community Open-Source Project** (Maintained by Xueqiao Xu & contributors) | **$0 / Free Open-Source** (MIT-licensed npm package & hosted GitHub Pages interactive grid playground) | **100% Free Forever** (Unlimited browser and Node.js 2D grid pathfinding queries and visual algorithm benchmarking) |

| **[MicroPather (Lee Thomason)](https://github.com)** | Lightweight, self-contained C++ A* solver and state-graph pathfinder engineered for minimal memory footprint in embedded and 2D games. | **Independent Open-Source Author** (Creator of TinyXML; Zlib-licensed) | **$0 / Free Open-Source** (Permissive Zlib license for commercial and indie C++ engines) | **100% Free Forever** (Zero-dependency C++ source files with built-in path caching for rapid 2D grid/graph queries) |

| **[PathLib (`python-pathfinding` / C++ PathLib Ecosystems)](https://github.com)** | Cross-language 2D grid and graph pathfinding libraries offering A*, Dijkstra, Best-First, Bi-Directional A*, IDA*, and Minimum Spanning Tree solvers. | **Open-Source Developer Ecosystem** (MIT-licensed Python/C++ packages) | **$0 / Free Open-Source** (Installable via `pip install pathfinding` or C++ headers) | **100% Free Forever** (Unlimited local 2D matrix pathfinding with diagonal movement and weighted terrain costs) |

| **[GridPath (`GridPath` / 2D Matrix Routing Tools)](https://github.com)** | Dedicated 2D grid, tilemap, and orthogonal/diagonal matrix routing utilities built for roguelikes, tower defense, and tactical turn-based games. | **Open-Source Indie Game Dev Ecosystem** (MIT / Apache-2.0 repositories) | **$0 / Free Open-Source** (Zero licensing or cloud runtime costs) | **100% Free Forever** (Unlimited offline and real-time 2D tilemap pathfinding calculations) |



## 💻 Open-Source GitHub Projects

*Sorted descending by GitHub stars count. Click the star badge to visit stargazers.*

| Project | Stars | License / Cost | Free Plan / Self-Hosted Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Godot Engine (`godotengine/godot`)](https://github.com/godotengine/godot)** | [![GitHub stars](https://img.shields.io/github/stars/godotengine/godot?style=social&color=white)](https://github.com/godotengine/godot/stargazers) | **MIT License** ($0) | **100% Free Forever** (Zero royalties, unlimited commercial use, full C++ source code access) | Feature-packed multi-platform 2D & 3D game engine featuring native `NavigationServer2D`, `NavigationRegion2D`, polygon navmesh baking, and RVO2 obstacle avoidance. |
| **[PathFinding.js (`qiao/PathFinding.js`)](https://github.com/qiao/PathFinding.js)** | [![GitHub stars](https://img.shields.io/github/stars/qiao/PathFinding.js?style=social&color=white)](https://github.com/qiao/PathFinding.js/stargazers) | **MIT License** ($0) | **100% Free Forever** (Unrestricted local browser & Node.js execution, unlimited path queries) | Comprehensive JavaScript/TypeScript 2D pathfinding library supporting A*, Jump Point Search (JPS), Breadth-First, Dijkstra, Best-First, Bi-Directional A*, and IDA*. |
| **[Recast Navigation (`recastnavigation/recastnavigation`)](https://github.com/recastnavigation/recastnavigation)** | [![GitHub stars](https://img.shields.io/github/stars/recastnavigation/recastnavigation?style=social&color=white)](https://github.com/recastnavigation/recastnavigation/stargazers) | **Zlib License** ($0) | **100% Free Forever** (Permissive Zlib license, zero seat fees, unlimited commercial integration) | The industry-standard automated navigation-mesh generation and runtime spatial pathfinding/Detour crowd-simulation engine used across top game engines. |
| **[NavMeshPlus (`h8man/NavMeshPlus`)](https://github.com/h8man/NavMeshPlus)** | [![GitHub stars](https://img.shields.io/github/stars/h8man/NavMeshPlus?style=social&color=white)](https://github.com/h8man/NavMeshPlus/stargazers) | **MIT License** ($0) | **100% Free Forever** (Unrestricted use in any personal or commercial Unity project) | Complete Unity 2D NavMesh pathfinding toolkit extending Unity's built-in Navigation system to 2D sprites, tilemaps, and root-motion 2D agents. |
| **[Nez (`prime31/Nez`)](https://github.com/prime31/Nez)** | [![GitHub stars](https://img.shields.io/github/stars/prime31/Nez?style=social&color=white)](https://github.com/prime31/Nez/stargazers) | **MIT License** ($0) | **100% Free Forever** (Permissive open-source MonoGame/FNA framework) | High-performance 2D framework for MonoGame/FNA featuring built-in spatial hashing, 2D A* pathfinding, breadth-first search, and polygon collision detection. |
| **[EasyStar.js (`prettymuchbryce/easystarjs`)](https://github.com/prettymuchbryce/easystarjs)** | [![GitHub stars](https://img.shields.io/github/stars/prettymuchbryce/easystarjs?style=social&color=white)](https://github.com/prettymuchbryce/easystarjs/stargazers) | **MIT License** ($0) | **100% Free Forever** (Unrestricted local and browser use without rate limits) | Asynchronous 2D A* pathfinding API for HTML5 and Node.js games designed to compute paths across grids without blocking the UI/game render loop. |
| **[javascript-astar (`bgrins/javascript-astar`)](https://github.com/bgrins/javascript-astar)** | [![GitHub stars](https://img.shields.io/github/stars/bgrins/javascript-astar?style=social&color=white)](https://github.com/bgrins/javascript-astar/stargazers) | **MIT License** ($0) | **100% Free Forever** (Standalone zero-dependency JS library) | Fast, lightweight 2D grid A* search implementation in JavaScript with diagonal movement, heuristic options, and binary heap priority queues. |
| **[three-pathfinding (`donmccurdy/three-pathfinding`)](https://github.com/donmccurdy/three-pathfinding)** | [![GitHub stars](https://img.shields.io/github/stars/donmccurdy/three-pathfinding?style=social&color=white)](https://github.com/donmccurdy/three-pathfinding/stargazers) | **MIT License** ($0) | **100% Free Forever** (Permissive MIT license for WebGL/Three.js interactive apps) | Navigation mesh pathfinding library for Three.js based on PatrolJS, enabling fast polygon path queries and agent waypoint clamping in 2D/3D web games. |
| **[gdx-ai (`libgdx/gdx-ai`)](https://github.com/libgdx/gdx-ai)** | [![GitHub stars](https://img.shields.io/github/stars/libgdx/gdx-ai?style=social&color=white)](https://github.com/libgdx/gdx-ai/stargazers) | **Apache-2.0 License** ($0) | **100% Free Forever** (Permissive Apache 2.0 license for Java/libGDX projects) | Comprehensive Artificial Intelligence framework for 2D/3D games featuring hierarchical state machines, behavior trees, steering behaviors, and indexed A* pathfinding. |
| **[libtcod (`libtcod/libtcod`)](https://github.com/libtcod/libtcod)** | [![GitHub stars](https://img.shields.io/github/stars/libtcod/libtcod?style=social&color=white)](https://github.com/libtcod/libtcod/stargazers) | **BSD-3-Clause License** ($0) | **100% Free Forever** (Permissive BSD license, full source distribution) | The quintessential roguelike development library in C/C++/Python providing field-of-view, fast 2D grid Dijkstra & A* pathfinders, and BSP dungeon generation. |
| **[pathfinding Rust (`evenfurther/pathfinding`)](https://github.com/evenfurther/pathfinding)** | [![GitHub stars](https://img.shields.io/github/stars/evenfurther/pathfinding?style=social&color=white)](https://github.com/evenfurther/pathfinding/stargazers) | **Apache-2.0 / MIT** ($0) | **100% Free Forever** (Zero-dependency Rust crate with zero cost abstractions) | Industrial-strength pathfinding library for Rust implementing A*, IDA*, Dijkstra, Fringe search, Jump Point Search, and topological sorting algorithms. |
| **[RVO2 Library (`snape/RVO2`)](https://github.com/snape/RVO2)** | [![GitHub stars](https://img.shields.io/github/stars/snape/RVO2?style=social&color=white)](https://github.com/snape/RVO2/stargazers) | **Apache-2.0 License** ($0) | **100% Free Forever** (Royalty-free academic & commercial crowd simulation library) | Gold-standard Optimal Reciprocal Collision Avoidance (ORCA) library in 2D C++ for collision-free multi-agent crowd steering and movement. |
| **[python-pathfinding (`brean/python-pathfinding`)](https://github.com/brean/python-pathfinding)** | [![GitHub stars](https://img.shields.io/github/stars/brean/python-pathfinding?style=social&color=white)](https://github.com/brean/python-pathfinding/stargazers) | **MIT License** ($0) | **100% Free Forever** (Unrestricted local execution via `pip install pathfinding`) | 2D matrix pathfinding toolkit in Python containing A*, Dijkstra, Best-First, Bi-directional A*, Breadth-First Search, and Jump Point Search implementations. |
| **[MicroPather (`leethomason/MicroPather`)](https://github.com/leethomason/MicroPather)** | [![GitHub stars](https://img.shields.io/github/stars/leethomason/MicroPather?style=social&color=white)](https://github.com/leethomason/MicroPather/stargazers) | **Zlib License** ($0) | **100% Free Forever** (Zero-dependency single C++ header/source file) | Ultra-compact, low-memory C++ A* solver and pathfinder designed for quick integration into 2D embedded game engines and custom graphics pipelines. |
