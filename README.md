# 100% CSS switch

## Customizable switch using only html and css

### Props

- `--switch-on-color`
  - Changes the color of the handle when the switch is on
- `--switch-off-color`
  - Changes the color of the handle when the switch is off
- `--switch-background-color`
  - Changes the color of the background of the switch
- `--switch-border-color`
  - Changes the color of the outline when the switch is focused
- `--switch-z-index`
  - The wanted z-index for the switch (max-used : `--switch-z-index + 3`)
- `--switch-animation-duration`
  - The duration of the animation when the state is changed
- `font-size`
  - Change the font size to make the switch bigger or smaller

### Default values
```css
:root {
  --switch-on-color: yellow;
  --switch-off-color: grey;
  --switch-background-color: black;
  --switch-border-color: #00BFFF;
  --switch-z-index: 0;
  --switch-animation-duration: .1s;
  font-size: 1rem;
}
```

## Examples

Examples can be found in the [index.html](index.html) file :
- default checkbox (no style)
- default switch (no design)
- sky switch (day / night)

© [M4gicalCat](https://github.com/M4gicalCat) ([Philippe FAISANDIER](https://pfaisand.fr))