# unity graphics programmer roadmap.

This roadmap is taken from Telegram channel aobut computer graphics in Unity Engine.
Link to the channel: https://t.me/unity_cg

Every step of the roadmap is arranged in order of complication and increasing depth of understanding. 

The Author of this roadmap is the creator of the Telegram channel (https://t.me/unity_cg), not me. This is just a copy of the message from the channel to make accessible. You can find more information in mentioned Telegram channel.

DISCLAIMER:
- Some little amount content may be in Russian language
- https://t.me/unity_cg uses Russian language as the main, but in case you'll write in English, I think people will understand you / answer to you.

0. Math
- https://gamemath.com/book - on of the best book about math in games.

1. Basics of Render Pipelines
- https://habr.com/ru/post/337484/ - very basics
- https://simonschreibt.de/gat/renderhell - slightly deeper
- https://catlikecoding.com/unity/tutorials/custom-srp - practice
- OpenGLInsights-TileBasedArchitectures.pdf - mobile related
 (http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.296.5501&rep=rep1&type=pdf)- https://fgiesen.wordpress.com/2011/07/09/a-trip-through-the-graphics-pipeline-2011-index - in case you need more of this.

p.s. I would also recommend reading everything related to rendering from the book "Game Engine Architecture" / "Game Engine" in order to understand how the above works with the engine.

2. Writing shaders (using code, not nodes)
- https://shaderdev.com - paid, but complete.
- https://www.cyanilux.com/tutorials/urp-shader-code - about new RPs.
- https://catlikecoding.com/unity/tutorials/rendering/
- https://thebookofshaders.com/ - how to make it beautifull. GLSL.

- Real-time rendering - The book. Something like a bible for graphical programmer.

https://learn.jettelly.com/unity-shader-bible/ - wip, but seems good.

3. Optimizations
- Frame Debugger, Unity Profiler - learn this tools in the first place.
- https://developer.arm.com/solutions/graphics-and-gaming/gaming-engine/unity/arm-guide-for-unity-developers
- Optimizing AAA Games for Mobile Platforms.pdf - Google it.
- Moving Mobile Graphics Cramming Software onto Mobile GPUs Lecturer Andrew Garrard Samsung R&D Institute UK SIGGRAPH August 2015 - google it.
- Usefull articles from playrix about Mobile GPU: 1 (https://habr.com/ru/company/playrix/blog/492874/), 2 (https://habr.com/ru/company/playrix/blog/498564/), 3 (https://habr.com/ru/company/playrix/blog/506232/)
- 
- 4. Instruments
- https://www.desmos.com/calculator - formulas
- https://xibanya.github.io/UnityShaderViewer 
- 
- - Дебаг:
1. Renderdoc (https://renderdoc.org/)
2. Xcode (https://developer.apple.com/documentation/metal/basic_tasks_and_concepts/viewing_your_gpu_workload_with_the_metal_debugger)
3. 3. Visual Studio (https://docs.unity3d.com/Manual/SL-DebuggingD3D11ShadersWithVS.html) (like renderdoc, but less functional) 
4. Tools from manufacturers. ARM Studio for mobile, Snapdragon profiler (very detailed, but very uncomfortable to work with) and Xcode. 
5. You can find more about Tools in Telegram channel (https://t.me/unity_cg)

About Mali debugging (https://blogs.unity3d.com/ru/2021/03/11/tackling-profiling-for-mobile-games-with-unity-and-arm/)

5. Usefull links
- https://www.pbr-book.org/3ed-2018/contents - book about PBR
- https://www.shadertoy.com/ - fullscreen glsl shaders.
- https://www.scratchapixel.com/index.php - lots of useful articles.
- https://www.youtube.com/channel/UCEklP9iLcpExB8vp_fWQseg/videos - more usefull articles.
- https://iquilezles.org/www/index.htm - usefull alghorithms.

Interesting blogs:
- https://www.alanzucconi.com/
- https://danielilett.com/tutorials/
- https://minionsart.github.io/tutorials/#shaders
- https://www.ronja-tutorials.com/
- https://cyangamedev.wordpress.com/
