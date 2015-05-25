[postcss-simple-vars]: https://github.com/postcss/postcss-simple-vars
[PostCSS]:             https://github.com/postcss/postcss

This is a fork of [postcss-simple-vars] plugin for [PostCSS]. Only added preventing overrides.

## Example:

```css
$foo: 200px !important; /* $foo equal 200px */
...
... some CSS ...
... 
... more CSS ...
...
$foo: 400px; /* $foo still equal 200px */
