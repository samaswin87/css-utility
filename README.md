# css-utility: Generic CSS utility classes

Classes designed for easily applying the spacing and alignments without needing to add new classes/modifiers for everything.

## Installation

`yarn add css-utility`

## Classes

Classes that may require `!important` have an `i` suffix.
Classes that may require `%` have an `p` suffix.

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

cursor:
- `.c-{property}`

font-weight:
- `fw-b` for `font-weight` with `bold`
- `fw-n` for `font-weight` with `normal`

font-size: size is `:medium| xx-small| x-small| small| large| x-large| xx-large| smaller| larger| length| initial| inherit` and `0-100`
- `fs-xx-#{size}` for `font-size`

width: size is `0-100`
- `w-#{size}` for `width`
- `w-#{size}-i` for `width` with `!important`
- `w-#{size}-p` for `width` with `%`
- `w-#{size}-p-i` for `width` with `%` and `!important`

height: size is `0-100`
- `w-#{size}` for `height`
- `w-#{size}-i` for `height` with `!important`
- `w-#{size}-p` for `height` with `%`
- `w-#{size}-p-i` for `height` with `%` and `!important`


min-height: size is `0 - 200` incrementing up by `5%`
- `.mh-#{size}-p` for `margin`, `.mh-#{size}-p-i` with `!important`

margin: size is `0 - 100`
- `.m-#{size}-p` for `margin`, `.m-#{size}-p-i` with `!important` (all following classes have the same option)
- `.mt-#{size}-p` for `top-margin`
- `.mr-#{size}-p` for `right-margin`
- `.mb-#{size}-p` for `bottom-margin`
- `.ml-#{size}-p` for `left-margin`
- `.mx-#{size}-p` for `left-margin` and `right-margin`
- `.my-#{size}-p` for `top-margin` and `bottom-margin`

padding: size is `0 - 100`
- `.p-#{size}-p` for `padding`, `.p-#{size}-p-i` with `!important` (all following classes have the same option)
- `.pt-#{size}-p` for `top-padding`
- `.pr-#{size}-p` for `right-padding`
- `.pb-#{size}-p` for `bottom-padding`
- `.pl-#{size}-p` for `left-padding`
- `.px-#{size}-p` for `left-padding` and `right-padding`
- `.py-#{size}-p` for `top-padding` and `bottom-padding`

margin: size is `0 - 100`
- `.m-#{size}` for `margin`, `.m-#{size}-i` with `!important` (all following classes have the same option)
- `.mt-#{size}` for `top-margin`
- `.mr-#{size}` for `right-margin`
- `.mb-#{size}` for `bottom-margin`
- `.ml-#{size}` for `left-margin`
- `.mx-#{size}` for `left-margin` and `right-margin`
- `.my-#{size}` for `top-margin` and `bottom-margin`

padding: size is `0 - 100`
- `.p-#{size}` for `padding`, `.p-#{size}-i` with `!important` (all following classes have the same option)
- `.pt-#{size}` for `top-padding`
- `.pr-#{size}` for `right-padding`
- `.pb-#{size}` for `bottom-padding`
- `.pl-#{size}` for `left-padding`
- `.px-#{size}` for `left-padding` and `right-padding`
- `.py-#{size}` for `top-padding` and `bottom-padding`

border-radius: size is `0 - 50` incrementing up by `1`
- `.b-r-#{size}` for `border-radius`, `.mh-#{size}-i` with `!important`
- `.b-r-#{size}-p` for `border-radius`, `.mh-#{size}-p-i` with `!important`

border-style:
- `.#{style}` for `border-style`


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
