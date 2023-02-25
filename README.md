# IMGUI-Base

This project is a base boilerplate adapted from the ImGui example_glfw_vulkan project. You are required to have the Vulkan SDK installed on system which can be found at https://sdk.lunarg.com/sdk/download/latest/windows/vulkan-sdk.exe, default install settings should work just fine.

To use this base execute the following:
```
git clone --recurse-submodules https://github.com/Coincadink/IMGUI-Base.git
cd IMGUI-Base
mkdir build
cmake --configure .
cmake --build ./build --config Debug --target IMGUI-Base
```
This should generate an executable file within the builds folder which can be launched from file browser, or from command prompt.

This project is licensed under the MIT Licens so do with it what you would like :)
