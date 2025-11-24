# PlanetsAR Project

This project was developed as part of the **CEN 451 -- Introduction to
Mixed Reality Application** course. It is a mobile Augmented Reality
(AR) experience built with **Unity 2022 LTS** and **AR Foundation**,
allowing users to explore and interact with 3D planetary models in
real-world space.

## Project Objective

The aim of this project is to provide hands-on experience with:

-   AR Foundation and XR toolchain
-   Plane detection and AR session configuration
-   Scene management in mobile AR applications
-   UI interaction and button-based navigation
-   Basic object manipulation (e.g., rotation, positioning)
-   Integrating 3D assets into a mixed reality environment

## Key Features

-   Mobile AR experience powered by ARCore/ARKit
-   Interactive HomeScreen menu with planet selection
-   3D models of **Earth** and **Mars**
-   Real-time rotation system using `RotationController.cs`
-   Scene transitions handled via `SceneController.cs`
-   Clean XR setup (XR Origin, AR Session)
-   Optimized vertical layout for Android devices

## Supported Platforms

-   Android (ARCore-compatible devices)
-   Unity 2022.3.x + AR Foundation 5.x
-   Can be extended for iOS (with ARKit XR Plugin)

## Technologies Used

-   Unity 2022 LTS
-   AR Foundation
-   ARCore XR Plugin
-   C# scripting
-   Unity UI System
-   XR Interaction Subsystems

## Project Structure

    Assets/
     ├─ Scenes/
     │   ├─ HomeScreen
     │   ├─ Earth
     │   └─ Mars
     ├─ Scripts/
     │   ├─ RotationController.cs
     │   └─ SceneController.cs
     ├─ Textures/
     └─ XR/

## Summary

Planets AR demonstrates how AR technology can be used to visualize celestial objects in a mixed-reality context. The application presents a simple yet effective example of AR session setup, UI navigation, scene
management, and interactive 3D content.
