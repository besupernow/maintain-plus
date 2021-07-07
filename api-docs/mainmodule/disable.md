# Disable

{% hint style="info" %}
It will only Disable the Current mode, meaning that multiple modes can't be enabled at the same time
{% endhint %}

## Example

```lua
local Maintain = require(game.ServerStorage.SmartMaintain)
Maintain:EnableMode("Maintenance","Awesomeness",os.time())
wait(1)
Maintain:Disable()
```

