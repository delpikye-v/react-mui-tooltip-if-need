<div align="center">
    <h1>react-mui-tooltip-ifz</h1>
    <a href="https://github.com/delpikye-v/react-mui-tooltip-if-need">react-mui-tooltip-ifz</a>
    <br />
    <br />
    <b><a href="https://codesandbox.io/s/hjhn36">LIVE EXAMPLE</a>
    </b>
</div>

---

#### Description

React MUI (v.5). Show tooltip if need. (truncate)

---
### Usage

Install the package

```js
npm install --save react-mui-tooltip-ifz
```

Import the module in the place you want to use:
```js
import { MuiTooltipIfNeed } from "react-mui-tooltip-ifz";

```

#### Snippet

###### simple

```js
<MuiTooltipIfNeed title="abdc">
  {/* <div>fdsfs</div> */}
  <Button
    variant="contained"
    className="abcd"
    style={{
      width: 200 // => you should update it from css class
    }}
    onClick={() => setSize(400)}
    onDoubleClick={() => setSize(200)}
  >
    Hellofds fdsfsfsfdsdf fdsf s
  </Button>
</MuiTooltipIfNeed>
```

<br />

---


#### props

<b>TooltipProps</b>: from <b>react: @mui/material</b>


| props               | type                      | description                                      |
|---------------------|---------------------------|--------------------------------------------------|
| always              | boolean                   | default: false:  show if text is overflow        |
| bootstrapCss        | boolean                   | default: true: arrow and color like bootstrapCss |

<br />

#### Note



#### RUN

<b><a href="https://codesandbox.io/s/hjhn36">LIVE EXAMPLE</a></b>

<br />

### License

MIT