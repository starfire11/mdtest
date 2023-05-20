# First steps

Lua^rt^ has two version of its interpreter, ``luart.exe`` for console applications and ``wluart.exe`` for desktop applications.
To be sure that everything went right during the installation process, let's run Lua^rt^ for the first time.

!!! notes
    Before proceeding, be sure to have a valid Lua^rt^ installed distribution. Read [Installation](..\installation\index.html) if needed.

## Running your first example

Let's start by running one of the examples bundled with Lua^rt^ :

* Open a console prompt (``cmd.exe`` or ``Windows Terminal`` for example)

* Change your current directory to the folder where Lua^rt^ is installed

* Type the command : 

```batch
luart examples\net\weather.lua
```

The console should display the current weather from your local area !

## Running your first desktop application

Let's proceed with another example with a GUI application :

* Keep the console prompt open

* Type the command :

```batch
wluart examples\ui\notepad.wlua
```
You should see a desktop application called "Notepad". Great !

!!! notes

    * Lua scripts can be executed also directly using the Windows file explorer, by double-clicking on it
      
    * During installation, file extensions `*.lua` and ``*.wlua`` are associated with ``luart.exe`` and ``wluart.exe`` interpreters respectively
  
    * The Lua^rt^ ``\bin`` subdirectory is added to the system PATH at installation time