pt-progressbar
================

Custom Element for Progressbar ! similar to bootstrap progress bar !

## Demo

[Check it live!](http://pitana.github.io/pt-progressbar)

## Usage
```html
<pt-progressbar min="200" max="500" value="340" showStatus striped active></pt-progressbar>
```

## Install

```sh
bower install pt-progressbar
```
## Options

### Attributes

Attribute         | Options    | Default     | Description
---               | ---        | ---         | ---
`min`             | *string*   | `0`         | Minimum value of Progressbar.
`max`             | *string*   | `100`       | Maximum value of Progressbar.
`value`           | *string*   | `0`         | Get/Set Value of Progressbar.
`type`            | *string*   | `default`   | possible values are success/info/danger/warning
`striped`         | *boolean*  | `false`     | Uses a gradient to create a striped effect. Not available in IE8.
`active`          | *boolean*  | `false`     | Show animation on striped. Not available in IE8.
`showStatus`      | *boolean*  | `false`     | Show Status like 32% or 350/500
`showActualValue` | *boolean*  | `false`     | Show Status in Percentage 32% if present, else show status in text like 350/500
`intermediate`    | *boolean*  | `false`     | Show Intermediate Progress bar


### Methods

Method            | Arguments        | Description
---               | ---              | ---
`toggle`          | *attr*           | It toggle boolean attributes. like ele.toggle("active")
