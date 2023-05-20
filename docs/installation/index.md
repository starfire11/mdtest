# Installation
There are two ways to install the official Lua<sup style="color:#FFB300">rt</sup> distribution on Windows:

* **Lua<sup style="color:#FFB300">rt</sup> installer**
This approach involves downloading Lua<sup style="color:#FFB300">rt</sup> directly from the official website [https://www.luart.org](https://luart.org). This is the simplest and recommended installation method.

* **Manual installation**
This method offers more customization for advanced users. It involves downloading Lua<sup style="color:#FFB300">rt</sup> sources and manual compilation. This is a complex installation method and should not be recommended for newcomers.

# Installation with Lua<sup style="color:#FFB300">rt</sup> installer

This method is rather simple, thanks to its specific Windows installer (built with Lua<sup style="color:#FFB300">rt</sup> !).

### Download 
Follow these steps to download the full installer:

- Open a browser window and navigate to the official website [https://www.luart.org](https://luart.org) page and click on `Download Lua^rt^`
- This will take you to the latest GitHub Release
- Scroll to the bottom and select either Windows x64 installer for 64-bit or Windows x86 installer for 32-bit (depending on your Windows platform)

!!! question "Which installer to choose : x64 or x86 ?"
    The Windows installer comes in either 32-bit or 64-bit versions :
    - On a 32-bit processor, you should choose the x86 installer. The installation will fail if you try to install the x64 version on a 32-bit processor.
    - On a 64-bit processor, it is possible to use both installers, but it is highly recommended using x64, as applications will run faster on a 64-bit system.

    If you're not sure which one to choose, the 64-bit version is the best choice?

    To switch from 64-bit to 32-bit LuaRT (or vice versa), simply uninstall LuaRT, then download the other installer, and reinstall it.
    Don't try to install both version on the same computer.

