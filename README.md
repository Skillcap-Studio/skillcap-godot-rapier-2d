<div align="center">
  <h1>Godot Rapier2D</h1>
</div>

<p align="center">
	<a href="https://github.com/appsinacup/godot-rapier2d/actions/workflows/runner.yml">
        <img src="https://github.com/appsinacup/godot-rapier2d/actions/workflows/runner.yml/badge.svg?branch=main"
            alt="Godot Rapier2D Build"></a>
    <a href="https://github.com/dimforge/rapier/releases/tag/v0.17.2" alt="Rapier2D Version">
        <img src="https://img.shields.io/badge/Rapier2D-v0.17.2-%23478cbf?logoColor=white" /></a>
    <a href="https://github.com/godotengine/godot-cpp" alt="Godot Version">
        <img src="https://img.shields.io/badge/Godot-v4.1-%23478cbf?logo=godot-engine&logoColor=white" /></a>
    <a href="https://github.com/appsinacup/godot-rapier2d/graphs/contributors" alt="Contributors">
        <img src="https://img.shields.io/github/contributors/appsinacup/godot-rapier2d" /></a>
    <a href="https://github.com/appsinacup/godot-rapier2d/pulse" alt="Activity">
        <img src="https://img.shields.io/github/commit-activity/m/appsinacup/godot-rapier2d" /></a>
    <a href="https://discord.gg/56dMud8HYn">
        <img src="https://img.shields.io/discord/1138836561102897172?logo=discord"
            alt="Chat on Discord"></a>
</p>

<img src="https://github.com/appsinacup/godot-rapier2d/blob/main/logo.jpg?raw=true"/> 

A 2d [rapier](https://github.com/dimforge/rapier) physics server for [Godot Engine](https://github.com/godotengine/godot), implemented as a GDExtension.

## Supported Platforms

Curently the Godot Box2d addon builds for:

- Windows (x86_64)
- macOS (x86-64 + arm64 Universal)
- Linux (x86_64)
- Android (x86_64, arm64)
- iOS (arm64) without signing
- Web (wasm32)

# Limitations

- One way direction for CharacterBody2D missing.
- Static Body Constant Speed for CharacterBody2D and RigidBody2D missing.
- Spring Joint missing.
- Shape skewing missing.
- Shape Cast Margin isn't supported.

# Features

- Single and double float precision build
- SIMD (Single instruction, multiple data) build
- Cross-platform determinism (assuming the rest of your code is also deterministic)

[More on different rapier features](https://rapier.rs/docs/user_guides/rust/getting_started)

# Installation

- Automatic (Recommended): Download the plugin from the official [Godot Asset Store](https://godotengine.org/asset-library/asset/2267) using the `AssetLib` tab in Godot.

- Manual: Download the github release and move only the `addons` folder into your project `addons` folder.

- Build it yourself. Read more about it in the [documentation](DOCUMENTATION.md).

After installing, go to `Advanced Settings` -> `Physics` -> `2D`. Change `Physics Engine` to `Rapier2D`.

# Roadmap

- Fix all other issues from Limitations.

# [Discord](https://discord.gg/56dMud8HYn)

A vibrant community for discussion, user support and showcases.

# License

All code in this repository is provided under the MIT license. See `LICENSE` for more details and `THIRDPARTY.txt` for third-party licenses.
This repo is a continuation of https://github.com/fabriceci/godot-rapier2d .
