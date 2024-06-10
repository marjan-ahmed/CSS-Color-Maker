![css color maker](https://github.com/marjan-ahmed/CSS-Color-Maker/assets/159646510/97fd0773-cef3-4867-bf34-be51a8533032)

# CSS-Color-Maker
The topic covers the basic CSS colors and background properties.

# The Repo support the concepts of the following below:
- Font colors & backgound colors
- linear gradient
- **rgb** (red,green,blue), **hex** (#) code, **hsl** (hue,saturation,lightning)
- Color transparency by opacities and alpha channel (alphaValue)
- Border Color
- Box Shadow

<h2>Colors & background colors</h2>
<h3>Syntax:</h3>

for font color
```Font colors
color: white;
```

for bg color
```Background colors
background-color: white /* by color name */
```

<h2>Linear gradient</h2>
<h3>Syntax:</h3>

```
background-image: linear-gradient([`direction`(deg)], `argu1` (color), `argu2` (color));
background-image: linear-gradient(90deg, blue, red);

/* Note: linear gradient will only work in `background-image` property
```

<h2>Rgb (red,green,blue), Hex (#) code, Hsl (hue,saturation,lightning)</h2>
<h3>Syntax</h3>

rgb color
```
color: rgb(0,0,0); /* Black */
background-color: rgb(255,255,255); /* White */

/* Note that the highest value of rgb is 255 */
```

hex code
```
background-color: #[red][green][blue]
backgound-color: #000000; /* black */
```

hsl color
```
backgound-color: hsl([hue],[saturation],[lightning]);
background-color: hsl(180,0%,50%) /* grey */
```

<h2>Color transparency by opacities and alpha channel (alphaValue)</h2>
<h3>Syntax</h3>

Color Transparency by Opacity

```
background-color: red;
opacity: 0.5;
```

Color Transparency by Rgba (alpha channel)

```
background-color: rgba(127,255,8,0.8) /* highligted green */;
```
<h2>Border Color</h2>
<h3>Syntax</h3>

```
border-color-weight: 10px;
border-color-style: solid;
border-color: blue;

border: 10px solid blue;
```

<h2>Box Shadow</h2>
<h3>Syntax</h3>

```
box-shadow: [offsetX]px [offsetY]px [blur radius]px [spread color]px;
box-shadow: 2px 2px 5px 10px;
```
