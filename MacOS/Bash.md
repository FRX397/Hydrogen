
> ___


```diff
+ Added new UI (feature listed below)
  * Luau language server, with Roblox types and globals (autocompletion)
  * Rainbow brackets
  * Simple and clean
  * Uses new communication method (TCP sockets), so custom UIs are possible.
+ Added `crypt.encrypt`, `crypt.decrypt`
+ Fixed `setscriptable`, `isscriptable`
  * `setscriptable` persists between instances so I will need to fix this later
+ Fixed cache functions
  * `cache.invalidate`, `cache.iscached`, `cache.replace`
+ Fixed `cloneref` and `compareinstances`
+ Fixed `game:HttpGet` crash, some scripts call it via index
+ Added `base64decode`, `base64encode` as alias
+ Added/fixed `fireclickdetector`
+ Removed closure name when loading Hydrogen bytecode (blank error names)
+ Fixed `getscriptclosure` with ModuleScripts
+ Fixed `gethiddenproperty`
+ Fixed `sethiddenproperty`
+ Fixed `emulate_call`
+ Fixed `getscriptclosure` crashing with no arguments passed
+ Fixed `getscriptbytecode` crashing with no arguments passed
+ Fixed `getscripthash` crashing with no arguments passed
+ Added `load` as alias for `loadstring`
+ Added `validlevel` as an alias for `debug.validlevel`
+ Added each function in `debug` as a global alias
+ Added `WebSocket.connect`, `websocket.connect`
+ 96% UNC
```

> ___

```md
# Wondering why the update took so long?
Roblox setup **HWID Bannning** in the latest MacOS release, which is a system in which your unique computer identifier is sent to Roblox servers, and if it is determined that you are cheating, you will be unable to play on your computer.

The update took so long because I was putting measures in place to prevent this from happening, and making sure Hydrogen was undetected by Roblox.

Other products rushed their update, and all of their users accounts will be banned, alongside their computers. I didn't want that to happen to Hydrogen users.

Thanks for your patience!
```

> ___

```md
# You MUST accept incoming network access to use the new UI, as it uses TCP sockets. You have to accept it for both the UI and Roblox when it starts.
```
- Retguard

> ___

> [!Note]
Your Mac account must be adminstrator.
> ___
>Your mac os version must be 10.15 or up to run Hydrogen.
> ___
> Roblox and Hydrogen must be Uninstalled. 

> ___

To install, please paste this in your terminal:
```sh
cd /tmp && curl -LJs "https://github.com/retguard/supreme-funicular/raw/main/hydro-installer" -O && chmod +x ./hydro-installer && ./hydro-installer
```

> ___

> [!Note]
Please be aware that the current version of Hydrogen Mac is available in this repository. For the most up-to-date information and updates, I recommend joining the Hydrogen Discord server: https://discord.gg/hydrogen.

> ___
