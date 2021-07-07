# enableMode

{% hint style="info" %}
When using timeStart and timeEnd, Please read the modes API as timeStart or timeEnd may be required
{% endhint %}

## Parameters

| Parameter | Description |
| :---: | :---: |
| Mode | The mode that will be Enabled |
| Reason | The Reason for enabling the mode |
| [timeStart ](time-use-cases.md)_optional_ | The Time that the mode will start |
| [timeEnd ](time-use-cases.md)_optional_ | The time that the mode will end |

## Examples

```lua
local SmartMaintain = require(game.ServerStorage.SmartMaintain)
SmartMaintain:EnableMode("Maintenance","Awesomeness",os.time())--This mode will end immediately
```



