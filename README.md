# DirectX 12 ImGui Hook
DirectX 12 Hooking with ImGui Implementation (x64)

- Present Hook
- DrawInstanced Hook
- DrawIndexedInstanced Hook
- ExecuteCommandLists Hook

```bash
Supports x64
```

## Built With
- [ImGuiHook](https://github.com/furkankadirguzeloglu/ImGuiHook) - DirectX Hooking for DirectX 11, 12, 9.
- [ImGui v1.83](https://github.com/ocornut/imgui) - Dear ImGui: Bloat-free Graphical User interface for C++ with minimal dependencies.
- [DirectX SDK](https://www.microsoft.com/en-us/download/details.aspx?id=6812) - This DirectX SDK release contains updates to tools, utilities, samples, documentation, and runtime debug files for x64 and x86 platforms.
- [MinHook](https://github.com/TsudaKageyu/minhook) - The Minimalistic x86/x64 API Hooking Library for Windows.

## How to Build
- Make sure to have [DirectX SDK](https://www.microsoft.com/en-us/download/details.aspx?id=6812) installed.
- Open Properties and make sure the right configurations are set.

### General
```bash
Configuration Type: Dynamic Library (.dll)
Windows SDK Version: 10.0
Platform Toolset: Visual Studio 2022 (v143)
C++ Language Standard: ISO C++20 Standard (/std:c++20)
```
### Advanced
```bash
Character Set: Use Multi-Byte Character Set
Whole Program Optimization: Use Link Time Code Generation
```
- Done!

## Preview
![PNG](https://i.imgur.com/oJA5b90.png)
