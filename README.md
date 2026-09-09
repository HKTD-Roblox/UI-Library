
# THIS IS A UI LIBRARY FROM *FORSAKEN*, IT'S SAME AS *FORSAKEN*!!!

*it only have dropdown, slider , toggle, paragraph, Textbox, no buttons yettt*


Make the window  
```lua
local lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/ImDevsVeux/Ui-lib/refs/heads/main/Bsnsn.txt"))()  

local win = lib:CreateWindow({Title = "Name idk"})
```

Tab -  
```lua
local tab = win:CreateTab({Title = "a tab"})
```

Toggle -  
```lua
tab:Toggle({
    Title = "Toggle",
    Desc = "Example toggle",
    Callback = function(val)
        print(val)
    end
})
```

Slider -  
```lua
tab:Slider({
    Title = "Slider",
    Desc = "Example slider",
    Min = 16,
    Max = 100,
    Callback = function(val)
        print(val)
    end
})
```

Textbox -  
```lua
tab:Textbox({
    Title = "Textbox",
    Desc = "Example textbox",
    Callback = function(val)
        print(val)
    end
})
```

Dropdown -  
```lua
tab:Dropdown({
    Title = "Dropdown",
    Desc = "Example dropdown",
    Options = {"Option 1", "Option 2", "Option 3"},
    Callback = function(pick)
        print(pick)
    end
})
```
![Preview](https://github.com/ImDevsVeux/Ui-lib/raw/refs/heads/main/1781933126749.png)

The Ui lib 
used many plugins to make it
ofc ultra skidding skills.
