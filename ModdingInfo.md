## About Modding Unreal Engine
Disclaimer: I don't know what I'm doing at all
### Neuro SDK
Unreal Engine doesn't have a Neuro SDK like Unity does. However, the methods used to mod VotV add support for C++ and Lua, which have SDKs.
- C++: https://github.com/chris-pie/neuro-sdk-websocketpp
- Lua: https://github.com/Gunoshozo/lua-neuro-sama-game-api
**Neither of these SDKs are official, use at your own risk.**
  
Additionally, there are a couple mods like [ChaosMod](https://github.com/modestimpala/VotVChaosMod) that add websocket support, which should be usable for Neuro's websocket. (will need to check to see if we can use the code)
### Getting Data out of VotV
Getting data out of VotV can be quite tricky, but with a few tools it can be done.

**DO NOT DATAMINE TO DISCOVER SECRETS, DO NOT SPOIL, AND VERY DO NOT JUST POST THE CODE YOU FIND ON THE WIDER INTERNET, YOU *WILL* BE KICKED FROM THE PROJECT IF YOU DO**

Datamining to spoil is against the devs' wishes and would most likely cause a lot of problems for this project
- Fmodel: Asset viewer, can export uasset files
- Kismet analyzer: Tool for viewing blueprints, can be hard to read them but it's far better than nothing
  - Kismet must be run from terminal in the folder with the exe
