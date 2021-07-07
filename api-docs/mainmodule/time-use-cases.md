# Time use cases

When using timeStart and timeEnd, Make sure to use the Unix time format, you can find a Unix Converter [here](https://www.epochconverter.com/).

## Example

```lua
local SmartMaintain = require(game.ServerStorage.SmartMaintain)
SmartMaintain:EnableMode("Maintenance","Awesomeness",1767182400)--This will end on December 31st, 2025, at 12 PM GMT
```

