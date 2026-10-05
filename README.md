# game-dev-arc

This entire project is meant to show me learning C# and tools to code a game. This entire project is done without agents or any AI tools outside of planning/debugging everything is going to be done by hand. This is to stop my brain from atrophying when it comes to coding:)!


Objectives/Milestones:
1. C#
Read: Microsoft Learn's C# docs and tutorials (learn.microsoft.com/dotnet/csharp)
Watch: Brackeys, "How to Program in C#" series
Build: A console text RPG with a character class, stats, a turn-based fight, and inventory as a List<Item>.
2. Unity fundamentals
Read: Unity Learn "Junior Programmer" pathway (learn.unity.com), with the Unity Manual as reference
Watch: Brackeys and Code Monkey for beginner tutorials, Sebastian Lague's "Coding Adventures" for inspiration
Build: Roll-a-Ball, then a small 3D game where you collect items and dodge hazards, with a win/lose screen.
3. 3D math
Read: 3D Math Primer for Graphics and Game Development, free online at gamemath.com
Watch: Freya Holmér's "Math for Game Devs," and 3Blue1Brown's "Essence of Linear Algebra" alongside CSCI 2033
Build: An enemy that only notices you inside its vision cone (dot product), an orbiting camera, and homing projectiles.
4. Third-person controller and camera
Read: Cinemachine docs, plus Unity's free Starter Assets Third Person Controller (read its code)
Watch: iHeartGameDev's character movement and animation series
Build: A controller with run, jump, and dodge, an orbit camera that doesn't clip through walls, and lock-on targeting.
5. RPG systems architecture
Read: Game Programming Patterns by Robert Nystrom, free at gameprogrammingpatterns.com (State, Observer, Component, Command chapters)
Watch: Ryan Hipple's Unite talk "Game Architecture with Scriptable Objects"
Build: Your Nen system as ScriptableObjects (types, abilities, cooldowns), plus save/load to JSON.
6. Combat
Read: The State chapter of Game Programming Patterns, and Unity's Animator docs on animation events
Watch: Mix and Jam, who recreates mechanics from real games and explains how they work
Build: One enemy with hitboxes and hurtboxes, an attack combo, and an idle/chase/attack/stagger state machine. Then a boss with two phases.
7. Shaders and toon rendering
Read: The Book of Shaders (thebookofshaders.com), Catlike Coding's Unity rendering tutorials (catlikecoding.com), and Roystan's toon shader tutorial (roystan.net)
Watch: Freya Holmér's shader course, Ben Cloward's Shader Graph videos, and the "Genshin shader breakdown" videos you'll find on YouTube
Build: A toon shader on a character model: cel bands, rim light, outlines, and a face-shadow trick.
8. Characters and art
Read: The Blender Manual, VRoid Studio's guide, and Mixamo for animations
Watch: Blender Guru's donut tutorial (the classic Blender start), then any anime character modeling series
Build: A VRoid character imported into Unity with Mixamo animations and your toon shader. Later, model one original character in Blender.
9. Optimization
Read: Unity Profiler docs, and Unity's free performance e-books on their site
Watch: Unity's official channel talks on profiling
Build: Spawn 1,000 enemies, profile the game, then fix it with object pooling and LOD and measure the difference.
10. C++ and OpenGL (side track)
Read: learncpp.com, then learnopengl.com from start to finish
Watch: The Cherno's C++ and OpenGL series
Build: A renderer with a camera, model loading, and lighting. Then port your toon shader into it.