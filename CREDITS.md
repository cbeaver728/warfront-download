# Credits

Third-party assets in the game, with their source and license. Everything else (code, primitive
models, shaders, sounds made in code) is this project's own.

The bacta station/bottle meshes and near-miss/healing sounds added in November
2026 are original procedural assets, built in BactaArt.cs and SoundBank.cs.

| Asset | File | Source | License |
|---|---|---|---|
| Outworld — vitalezzz (approved B, full menu track) | `game/assets/music/outworld.mp3` | https://opengameart.org/content/outworld | CC0 1.0 |
| Determined Pursuit — Emma_MA (approved F, full battle track) | `game/assets/music/determined-pursuit.wav` | https://opengameart.org/content/determined-pursuit-epic-orchestra-loop | CC0 1.0 |
| Epic Boss Battle — Juhani Junkala / SubspaceAudio (approved G, full battle track) | `game/assets/music/epic-boss-battle.wav` | https://opengameart.org/content/boss-battle-music | CC0 1.0 |
| Subspace — vitalezzz (approved E, archived for future strategy music) | `assets/future-music/subspace.mp3` | https://opengameart.org/content/subspace | CC0 1.0 |
| Singularity (Calm) — vitalezzz (approved S04, full strategy track) | `game/assets/music/singularity-calm.mp3` | https://opengameart.org/content/singularity-0 | CC0 1.0 |
| Sunset Plains — Yoiyami (approved S07, full strategy track) | `game/assets/music/sunset-plains.mp3` | https://opengameart.org/content/sunset-plains | CC0 1.0 |
| Battle Theme — Wolfgang_ (approved B02, full strategy track) | `game/assets/music/strategy-battle-theme.mp3` | https://opengameart.org/content/battle-theme-0 | CC0 1.0 |
| Universal Animation Library (Standard), by Quaternius: a rigged humanoid mannequin and 45 animation clips. Used by the rigged soldier prototype (`--rigged-soldiers`). | `game/assets/characters/ual_mannequin.glb` (the pack's `Godot/AnimationLibrary_Godot_Standard.glb`, renamed, otherwise unchanged) | https://opengameart.org/content/universal-animation-library (also https://quaternius.com/packs/universalanimationlibrary.html), downloaded 2026-10-21 | CC0 1.0 (public domain); the pack's License.txt says so. No credit required, but thanks, Quaternius. |

Third-party code:

| Code | File | Source | License |
|---|---|---|---|
| fdlibm's exp, log, sin and cos (and their argument reduction), ported to C# for `PortableMath` (ADR 0041) | `src/Warfront.Core/Common/PortableMath.cs` | fdlibm 5.3, Sun Microsystems, 1993 (as in netlib.org/fdlibm) | "Permission to use, copy, modify, and distribute this software is freely granted, provided that this notice is preserved." The notice is kept in the file. |
