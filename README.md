font-roboto-local
============

See the [component page](https://github.com/elrancid/font-roboto-local) for more information.

## DEPRECATED:

Warning: use this repo only for polymer 0.5. For polymer 1.0 there is the official
[PolymerElements/font-roboto-local](https://github.com/PolymerElements/font-roboto-local) repo.

## Getting Started

`font-roboto-local` is a replacement for `font-roboto` for the local use.
`font-roboto` uses googleapis.com site to retrive the fonts, so it needs internet connection.
`font-roboto-local` can be used in a local project, because has the local copy of the fonts.

The version of `font-roboto-local` follows the version of `font-roboto`.

Example:

my-font-demo.html:

```html
<link rel="import" href="bower_components/font-roboto-local/roboto.html">
<style>
body {
	font-family: 'RobotoDraft';
}
</style>
```
