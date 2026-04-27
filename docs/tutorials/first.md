A first step of developing your own addon for Kinetic Engine is pretty easy, no downloads needed.

Create an Instance "ModuleScript".

```lua
local serverStorage = game:GetService("ServerStorage")
local serverGame = serverStorage.Game
local api = require(serverGame.AddonAPI)
```

this code fetches api for making addons