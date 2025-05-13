# Military Domination Idle Game - Godot Project

## Overview
This project is set up for development with the Godot Engine (4.x recommended), targeting both desktop and mobile platforms.

## Prerequisites
- Godot Engine (download from [godotengine.org](https://godotengine.org/download))
- For Android export: Android SDK, Java JDK, and Godot Android export templates
- For iOS export: Xcode and Godot iOS export templates (macOS only)

## Project Structure
- `project.godot` – Godot project config
- `.godot/` – Godot internal files
- `icon.svg` – Project icon

## Export Setup
1. Open the project in Godot.
2. Go to **Project > Export** and install export templates if prompted.
3. Add export presets for each target platform (Windows, Linux, Mac, Android, iOS).
4. For Android: Set up the Android SDK path in **Editor Settings > Export > Android**.
5. For iOS: Set up export options in **Export Preset > iOS** (requires macOS).

## .gitignore
A `.gitignore` is included for Godot projects.

## Getting Started
1. Open Godot and import this folder as a project.
2. Start coding your game!

---
For detailed platform export instructions, see the [official Godot docs](https://docs.godotengine.org/en/stable/tutorials/export/index.html).
