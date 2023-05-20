# Installation
There are two ways to install the official Lua<sup style="color:#FFB300">rt</sup> distribution on Windows:

* **Lua<sup style="color:#FFB300">rt</sup> installer**
This approach involves downloading Lua<sup style="color:#FFB300">rt</sup> directly from the official website [https://www.luart.org](https://luart.org). This is the simplest and recommended installation method.

* **Manual installation**
This method offers more customization for advanced users. It involves downloading Lua<sup style="color:#FFB300">rt</sup> sources and manual compilation. This is a complex installation method and should not be recommended for newcomers.

# Installation with Lua<sup style="color:#FFB300">rt</sup> installer

This method is rather simple, thanks to its specific Windows installer (built with Lua<sup style="color:#FFB300">rt</sup> !).

### Download the installer
Follow these steps to download the full installer:

* Open a browser window and navigate to the official website [https://www.luart.org](https://luart.org) page and click on the "Download Lua<sup>rt</sup>" button.
* This will take you to the latest GitHub Release page.
* Scroll to the bottom and select either Windows x86 or x64 installer (depending on your Windows platform)
  
!!! question "Help on choosing installation version"
    The Lua<sup style="color:#FFB300">rt</sup> installer comes in either 32-bit or 64-bit versions :
    - On a 32-bit processor, you should choose the x86 installer. The installation will fail if you try to install the x64 version on a 32-bit processor.
    - On a 64-bit processor, it is possible to use both installers, but it is highly recommended using the x64 one, as applications will run faster on a 64-bit system.

    If you're not sure which one to choose, the 64-bit version is the best choice.
  
    Don't try to install both version on the same computer.

### Run the installer
Once you have chosen and downloaded the right installer, execute it by double-clicking on the downloaded file in an explorer window.
This white window should appear :

![LuaRT installer running](install.png)

The installation process is simple :
* Click on the installation button to proceed
* You will be prompted to choose the installation directory
* Wait until the installation process is done
  
!!! warning "Windows operating system prevents the applications from starting"        
    Lua<sup>rt</sup> may be blocked by Microsoft Defender SmartScreen because executable is not EV certified (executables are not signed).
    ➡️If the blue window opens when running setup file, click on "More info" and then "Run anyway"

!!! warning "Windows Defender places the installer in quarantine"
    During virus scanning, Microsoft Defender may show a false positive result for LuaRT, since the setup executable is not signed with an EV certificate.
    ➡️Open Windows Defender
    ➡️Click on "Virus & Threat Protection", select "All recent items", then select "Allow from the actions" drop-down menu.