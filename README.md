# Vulkan PBR Sandbox (Early Renderer)

![Vulkan](https://img.shields.io/badge/Vulkan-1.2-red.svg)
![C++](https://img.shields.io/badge/C++-17-blue.svg)

This repository contains my early explorations into the Vulkan API and Physically Based Rendering (PBR). It was built as a sandbox to understand the extreme verbosity and explicit control mechanisms of modern graphics APIs, including Swapchains, Command Buffers, Descriptor Sets, and Pipeline State Objects (PSOs).

> **💡 Architecture Note:** > This is an archived learning project, and the codebase reflects a rapid-prototyping approach. For my current, production-oriented engine architecture with a highly structured Rendering Hardware Interface (RHI), please check out my primary project: **[Lumina Engine (DirectX 12) ➔](https://github.com/PtPix/Lumina-Engine)**

## ✨ Key Features Implemented
- **Vulkan Core Initialization**: Custom wrappers for `VkInstance`, `VkDevice`, Swapchain management, and Command Buffers.
- **PBR Shading Pipeline**: Basic implementation of a Physically Based Rendering workflow (Albedo, Normal, Roughness, Metallic) written in GLSL (`shader.vert`, `shader.frag`).
- **Asset Loading**: Integrated `tiny_obj_loader` for 3D models and `stb_image` for texture mapping.
- **Immediate Mode GUI**: Fully integrated ImGui with Vulkan backends for real-time parameter tweaking.

## 📷 Screenshots

https://github.com/user-attachments/assets/92bdaecc-5939-47cf-853b-0c09d623defe
