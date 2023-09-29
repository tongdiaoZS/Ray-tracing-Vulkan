# A Ray Tracing Project

This is a ray tracer while is using Vulkan and ImGui, I used the Walnut App template to make it easier to focus on the development of the ray tracing part.

## Ray Tracing
1. Using **Path Tracing**;
2. Implemented a simple **PBR** material;
3. Encapsulate light, objects, and environments into different **class** or **struct** to improve readability;
4. Acceleration using **multi-threading**;
5. Can use the control to modify object properties.

## Result
I using AMD R7 5800H to rendering piture at **150fps**.

## Build
### Windows
1. Run `scripts/Setup.bat`;
2. Using Visual Studio to Generate `.exe`



## Why using Walnut ?
Directly use the vulkan package of glfw in imgui, using a multi-subpass scheme, easy to use and quick to integrate.

## Walnut
This is a simple app template for [Walnut](https://github.com/TheCherno/Walnut) - unlike the example within the Walnut repository, this keeps Walnut as an external submodule and is much more sensible for actually building applications. See the [Walnut](https://github.com/TheCherno/Walnut) repository for more details.

### Getting Started
Once you've cloned, you can customize the `premake5.lua` and `WalnutApp/premake5.lua` files to your liking (eg. change the name from "WalnutApp" to something else).  Once you're happy, run `scripts/Setup.bat` to generate Visual Studio 2022 solution/project files(I using Visual Studio 2019, if you using Visual Studio 2022, please revise `scripts/Setup.bat`). Your app is located in the `WalnutApp/` directory, which some basic example code to get you going in `WalnutApp/src/WalnutApp.cpp`. I recommend modifying that WalnutApp project to create your own application, as everything should be setup and ready to go.
