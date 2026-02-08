# Universal Syn Save Instance

---
## LoadString
```lua
local Params = {
 RepoURL = "https://raw.githubusercontent.com/BOXLEGENDARY/UniversalSynSaveInstance/main/",
 SSI = "saveinstance",
}
local synsaveinstance = loadstring(game:HttpGet(Params.RepoURL .. Params.SSI .. ".luau", true), Params.SSI)()
local Options = {} -- Documentation here https://luau.github.io/UniversalSynSaveInstance/api/SynSaveInstance
synsaveinstance(Options)
```
---
## License

[![USSI License](https://img.shields.io/badge/USSI-License-green)](https://github.com/luau/UniversalSynSaveInstance/blob/main/LICENSE)

---

## Credits
[phoriah](https://github.com/luau/UniversalSynSaveInstance) - Owner
