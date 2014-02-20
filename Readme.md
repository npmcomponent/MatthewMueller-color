*This repository is a mirror of the [component](http://component.io) module [matthewmueller/color](http://github.com/matthewmueller/color). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/matthewmueller-color`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# color

  Extremely basic color tinting component. Based on an answer to the SO question: [Programmatically darken a Hex colour](http://stackoverflow.com/a/1787140/145435)

## Installation

    $ component install matthewmueller/color

## Example

```js
var color = require('color'),
    c = 'red';

color.darken(c, .5) // '#ff3232'
color.lighten(c, .5) // '#cd3232'
```

## API

### darken(color, val)

  Darkens the `color` by the given `val`.

### lighten(color, val)

  Lightens the `color` by the given `val`.

## License

  MIT
