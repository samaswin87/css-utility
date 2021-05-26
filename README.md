# css-utility: Generic CSS utility classes

Classes designed for easily applying the spacing and alignments without needing to add new classes/modifiers for everything.

## Installation

`yarn add css-utility`

## Classes

Classes that may require `!important` have an `i` suffix.
Classes that may require `%` have an `ratio` suffix.

text-align: 
- `.text-right`
- `.text-left`
- `.text-center`

float:
- `.float-right`
- `.float-left`
- `.float-none`

display:
- `.d-{property}`

position:
- `.p-{property}`

font-weight:
- `fw-b` for `font-weight` with `bold`
- `fw-n` for `font-weight` with `normal`

font-size: size is `:medium| xx-small| x-small| small| large| x-large| xx-large| smaller| larger| length| initial| inherit` and `0-100`
- `fs-xx-#{size}` for `font-size`

width: size is `0-100`
- `w-#{size}` for `width`
- `w-i-#{size}` for `width` with `!important`
- `w-ratio-#{size}` for `width` with `%`
- `w-ratio-i-#{size}` for `width` with `%` and `!important`

height: size is `0-100`
- `h-#{size}` for `height`
- `h-i-#{size}` for `height` with `!important`
- `h-ratio-#{size}` for `height` with `%`
- `h-ratio-i-#{size}` for `height` with `%` and `!important`


min-height: size is `0 - 200` incrementing up by `5%`
- `.mh-#{size}-ratio` for `margin`, `.mh-#{size}-ratio-i` with `!important`

margin: size is `0 - 100`
- `.m-#{size}-ratio` for `margin`, `.m-#{size}-ratio-i` with `!important` (all following classes have the same option)
- `.mt-#{size}-ratio` for `top-margin`
- `.mr-#{size}-ratio` for `right-margin`
- `.mb-#{size}-ratio` for `bottom-margin`
- `.ml-#{size}-ratio` for `left-margin`
- `.mx-#{size}-ratio` for `left-margin` and `right-margin`
- `.my-#{size}-ratio` for `top-margin` and `bottom-margin`

padding: size is `0 - 100`
- `.p-#{size}-ratio` for `padding`, `.p-#{size}-ratio-i` with `!important` (all following classes have the same option)
- `.pt-#{size}-ratio` for `top-padding`
- `.pr-#{size}-ratio` for `right-padding`
- `.pb-#{size}-ratio` for `bottom-padding`
- `.pl-#{size}-ratio` for `left-padding`
- `.px-#{size}-ratio` for `left-padding` and `right-padding`
- `.py-#{size}-ratio` for `top-padding` and `bottom-padding`

margin: size is `0 - 100`
- `.m-#{size}-px` for `margin`, `.m-#{size}-px-i` with `!important` (all following classes have the same option)
- `.mt-#{size}-px` for `top-margin`
- `.mr-#{size}-px` for `right-margin`
- `.mb-#{size}-px` for `bottom-margin`
- `.ml-#{size}-px` for `left-margin`
- `.mx-#{size}-px` for `left-margin` and `right-margin`
- `.my-#{size}-px` for `top-margin` and `bottom-margin`

padding: size is `0 - 100`
- `.p-#{size}-px` for `padding`, `.p-#{size}-px-i` with `!important` (all following classes have the same option)
- `.pt-#{size}-px` for `top-padding`
- `.pr-#{size}-px` for `right-padding`
- `.pb-#{size}-px` for `bottom-padding`
- `.pl-#{size}-px` for `left-padding`
- `.px-#{size}-px` for `left-padding` and `right-padding`
- `.py-#{size}-px` for `top-padding` and `bottom-padding`

## Development

Requires yarn or npm (use yarn don't be dumb).

Setup:
- `git clone git@github.com:samaswin87/css-utility.git`
- `yarn setup`

Commands:
- `yarn build`
- `yarn run watch`

When committing git hooks will run `yarn build` and add the build to the current commit.

## Testing

Yolo.
