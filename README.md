# Godot Responsive UI: Nine-Slice & Animated Progress Bar

This project was developed as a practical application of responsive UI techniques in **Godot Engine**. The goal is to demonstrate how to create scalable interfaces that maintain visual integrity across different screen resolutions.

## 🚀 Features

- **Nine-Slice Scaling (NinePatchRect):** Implementation of scalable textures that preserve corners and borders, preventing distortion in panels and buttons.
- **Animated Progress Bar:** A dynamic health/loading bar using the `Tween` node for smooth value transitions, enhancing user feedback.
- **Icon Integration:** Proper placement and scaling of UI icons within responsive containers.
- **Responsive Layout:** Utilizing Godot's Container system (`MarginContainer`, `HBoxContainer`, `VBoxContainer`) to ensure the UI adapts to any window size.

## 🛠️ Technologies & Concepts

- **Godot Engine 4.x**
- **GDScript**
- **Tweening:** Real-time property interpolation for fluid animations.
- **UI Containers:** Automatic positioning and sizing management.

## 📖 What is Nine-Slice?

The Nine-Slice technique divides a texture into a 3x3 grid. The four corners remain unscaled, the edges stretch (or repeat) in one axis, and the center scales in both. This allows a small sprite to fill a UI element of any size without losing quality.
