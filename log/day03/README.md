# 100 Days Of Code - Log | Day 3: June 21, 2022

## Today's Progress

* Completed [FreeCodeCamp.org - Learn CSS Colors by Building a Set of Colored Markers][1]

## Notes

* Named colors (for example - `red, green, blue, cyan`)
* Use Red Green Blue (RGB) notation - `rgb(red-value, green-value, blue-value)`. Each value can range from 0 to 255
* Hex Value (for example, `#4B5320`). Each pair of value is a Hex value for Red, Green and Blue respectively
* Hue Saturation and Lightness (HSL) notation.
    * Hue value ranges from 0 to 360. Hue Red (0), Hue Green (120), Hue Blue (240)
    * Saturation is intensity of color. 0% (gray) to 100% (pure color)
    * Lightness is how bright a color appears. 0% (complete black) to 100% (complete white). 50% being natural
    * Example - `hsl(240, 100%, 50%)` represents blue
* Linear Gradients - Color transition from one color to another along a line
    * Usually works with `background` property
    * `linear-gradient(gradientDirection, color1 color1-stop, color2 color2-stop, ...);`
    * Needs at least 2 colors to work
    * Color stops define how much area the color uses along the line
* Alpha Channel - Used along with RGB as `rgba` or `hsla`. Alpha value indicates how strong the color is. Value ranges from 0.0 to 1.0
* CSS properties
    * `opacity` - Sets opacity for the element. Value ranges from 0.0 to 1.0
    * `box-shadow` - Sets the shadow for an element. `box-radius: offsetX offsetY blurRadius spreadRadius color`

## How To Center A Div Horizontally

```css
div {
    width: 80%;
    margin-left: auto;
    margin-right: auto;
}
```

## Thoughts:

* CSS is so powerful

## Link to Work

* [FreeCodeCamp.org - Learn CSS Colors by Building a Set of Colored Markers][1]



  [1]: https://www.freecodecamp.org/learn/2022/responsive-web-design/#learn-css-colors-by-building-a-set-of-colored-markers
