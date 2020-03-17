# Installation

npm install --save tooltip-sipizork

Then...

```
import ToolTip from 'tooltip-sipizork'
<div className="something that requires a tooltip>Need some ToolTip</div> "
<ToolTip tip="text" position="bottom" />
```

## Options

* *tip* - _string_ (required)
* *position* - _top | right | bottom | left_ (optional, default top)
* *color* - _HEX | RGB_ (optional, default white)
* *bgColor* - _HEX | RGB_ (optional, default black)
