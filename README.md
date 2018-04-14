# `modularscale-ratios`

Based on the work by [Scott Kellum and Tim Brown](http://www.modularscale.com).

These ratios are intended to be used with a [modular scale](http://www.modularscale.com/) for visual design. See [modularscale.com](http://www.modularscale.com/) for more details.

## Usage

```js
// 1. import the ratios along with modularscale-js
import modularscale-ratios as ratios from 'modularscale-ratios';
import ms from 'modularscale-js'; // see https://github.com/modularscale/modularscale-js/

// 2. choose a base and ratio
const $ratio = {
    base: 16,
    ratio: ratios.perfectFourth // choose any ratio from the predefined list
};

// 3. use the modular scale to give proportion to your design
const myBodyFontSize = ms(0, $ratio);
const myHeadingFontSize = ms(3, $ratio);
// ...
```

## Available Ratios

| Name           | JavaScript Name | Ratio           |
| ----           | -----           | --------------- |
| Minor Second   | minorSecond     | 16/15           |
| Major Second   | majorSecond     | 1.125           |
| Minor Third    | minorThird      | 1.2             |
| Major Third    | majorThird      | 1.25            |
| Perfect Fourth | perfectFourth   | 4/3             |
| Aug Fourth     | augFourth       | 1.414           |
| Perfect Fifth  | perfectFifth    | 1.5             |
| Minor Sixth    | minorSixth      | 1.6             |
| Golden Section | goldenSection   | 1.61803398875   |
| Major Sixth    | majorSixth      | 5/3             |
| Minor Seventh  | minorSeventh    | 16/9            |
| Major Seventh  | majorSeventh    | 1.875           |
| Octave         | octave          | 2               |
| Major Tenth    | majorTenth      | 2.5             |
| Major Eleventh | majorEleventh   | 8/3             |
| Major Twelfth  | majorTwelfth    | 3               |
| Double Octave  | doubleOctave    | 4               |
