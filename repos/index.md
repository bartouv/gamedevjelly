# Repos

Open-source repos worth knowing for Unity.

- [UniTask](https://github.com/Cysharp/UniTask) (Async & reactive, ★11245, last push 2026-10-06): You want async/await in Unity without allocations, with PlayerLoop-aware delays and cancellation. Install: https://github.com/Cysharp/UniTask.git?path=src/UniTask/Assets/Plugins/UniTask
- [R3](https://github.com/Cysharp/R3) (Async & reactive, ★4017, last push 2026-10-08, Unity 7: workaround): You want Rx-style reactive streams; the successor to UniRx.
- [MessagePipe](https://github.com/Cysharp/MessagePipe) (Async & reactive, ★2000, last push 2026-10-07): You need an in-process pub/sub or mediator that works with DI containers.
- [ZString](https://github.com/Cysharp/ZString) (Serialization & data, ★2814, last push 2026-10-07): You build strings every frame and want zero allocations.
- [MemoryPack](https://github.com/Cysharp/MemoryPack) (Serialization & data, ★4751, last push 2026-10-07): You need very fast binary serialization for save data or networking.
- [MessagePack-CSharp](https://github.com/MessagePack-CSharp/MessagePack-CSharp) (Serialization & data, ★6787, last push 2026-10-09): You want compact, fast MessagePack serialization with Unity (IL2CPP) support.
- [MagicOnion](https://github.com/Cysharp/MagicOnion) (Networking & backend, ★4453, last push 2026-10-07): You want type-safe RPC between a Unity client and a C# server.
- [VContainer](https://github.com/hadashiA/VContainer) (Dependency injection, ★3072, last push 2026-10-06): You want a fast, lightweight DI container with low GC pressure. Install: https://github.com/hadashiA/VContainer.git?path=VContainer/Assets/VContainer
- [Reflex](https://github.com/gustavopsantos/Reflex) (Dependency injection, ★1634, last push 2026-10-10, Unity 7: ok): You want a minimal DI container with a small API.
- [Zenject](https://github.com/modesttree/Zenject) (Dependency injection, ★2939, last push 2024-01-26): You use Zenject. Its last push was Jan 2024; the maintained Extenject fork (below) is the one to install for new work.
- [PrimeTween](https://github.com/KyryloKuzyk/PrimeTween) (UI & tweening, ★2003, last push 2026-07-18): You want allocation-free tweens and sequences in one line.
- [dotween](https://github.com/Demigiant/dotween) (UI & tweening, ★2691, last push 2026-07-26, Unity 7: wip): You want the long-standing tween library; free tier, with a paid Pro add-on.
- [SoftMaskForUGUI](https://github.com/mob-sakai/SoftMaskForUGUI) (UI & tweening, ★2833, last push 2026-08-27): You need soft (alpha) masks in uGUI.
- [UIEffect](https://github.com/mob-sakai/UIEffect) (UI & tweening, ★7681, last push 2026-08-27): You want shader-based effects (shadow, gradient, dissolve, blur) on uGUI.
- [NaughtyAttributes](https://github.com/dbrizov/NaughtyAttributes) (Editor & debugging, ★5220, last push 2026-09-16): You want inspector attributes (ShowIf, Button, Foldout) without writing editors. Install: https://github.com/dbrizov/NaughtyAttributes.git#upm
- [graphy](https://github.com/Tayx94/graphy) (Editor & debugging, ★2908, last push 2026-08-29): You want an on-screen FPS, memory and audio overlay in builds.
- [Harmony](https://github.com/pardeike/Harmony) (Editor & debugging, ★6685, last push 2026-10-11): You need to patch .NET methods at runtime, mostly for modding.
- [UnityCsReference](https://github.com/Unity-Technologies/UnityCsReference) (Official source & samples, ★13022, last push 2026-10-08): You want to read Unity's C# source for the engine and editor.
- [Graphics](https://github.com/Unity-Technologies/Graphics) (Official source & samples, ★3010, last push 2026-09-29): You want the source and samples for URP, HDRP, Shader Graph and VFX Graph.
- [InputSystem](https://github.com/Unity-Technologies/InputSystem) (Official source & samples, ★1527, last push 2026-10-07, Unity 7: ok): You use the new Input System and want its source and issues.
- [Unity.Mathematics](https://github.com/Unity-Technologies/Unity.Mathematics) (Official source & samples, ★1441, last push 2026-08-06): You want Burst-friendly math types (float3, quaternion, noise).
- [EntityComponentSystemSamples](https://github.com/Unity-Technologies/EntityComponentSystemSamples) (Official source & samples, ★8199, last push 2026-10-10): You are learning DOTS/ECS and want official samples.
- [SpaceshipDemo](https://github.com/Unity-Technologies/SpaceshipDemo) (Official source & samples, ★1182, last push 2025-10-24): You want a full HDRP showcase project to read and learn from.
- [BoatAttack](https://github.com/Unity-Technologies/BoatAttack) (Official source & samples, ★2797, last push 2025-12-05): You want a URP showcase project (water, boats, race game).
- [com.unity.netcode.gameobjects](https://github.com/Unity-Technologies/com.unity.netcode.gameobjects) (Networking & backend, ★2324, last push 2026-10-11, Unity 7: ok): You want Unity's official GameObject-based multiplayer.
- [Mirror](https://github.com/MirrorNetworking/Mirror) (Networking & backend, ★6356, last push 2026-09-19): You want a mature, community-driven multiplayer framework.
- [FishNet](https://github.com/FirstGearGames/FishNet) (Networking & backend, ★2064, last push 2026-10-09): You want a feature-rich networking framework with prediction support.
- [unity-builder](https://github.com/game-ci/unity-builder) (CI & build, ★1101, last push 2026-09-16): You want to build Unity projects in GitHub Actions.
- [unity-mcp](https://github.com/CoplayDev/unity-mcp) (AI & agents, ★14841, last push 2026-10-08, Unity 7: ok): You want an AI client (Claude, Cursor, etc.) to drive the Unity Editor over MCP. Most popular option.
- [Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) (AI & agents, ★4418, last push 2026-10-11): You want an MCP bridge between AI agents and the Unity Editor and runtime.
- [StableFluids](https://github.com/keijiro/StableFluids) (Rendering & VFX, ★1171, last push 2025-08-28): You want a GPU implementation of Stam's Stable Fluids.
- [Marching-Cubes](https://github.com/SebLague/Marching-Cubes) (Learning repos, ★1121, last push 2019-07-11): You want the marching cubes algorithm in Unity.
