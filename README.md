## Razer X
**Razer X is a luau bytecode decompiler for local/module scripts in game!**
## Initialization
```lua
-->; Init
v0 = getgenv()["game"];
v1 = v0["HttpGet"];
v2 = "https://raw.githubusercontent.com/getrawmetatable/Razer.X/razer-.-x-%25/.lua";
v3 = v1(v2);
v4 = getgenv()["loadstring"];
v5 = v4(v2)();
local scr_bytecode = v5:RTN_LBTS(<string> path) -->; Initialize script // Returns script bytecode
return print(scr_bytecode)
```
