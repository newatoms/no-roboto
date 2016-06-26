# no-roboto
A replacement for [`font-roboto`](https://github.com/PolymerElements/font-roboto/) that doesn't include any Roboto.

Example use: build a website with Polymer elements that doesn't include Roboto without editing any of the other dependencies.

## Installing

Add the folowing to your `bower.json`:

```json
"resolutions": {
  "font-roboto": "newatoms/no-roboto"
}
```

This will install `no-roboto` in the place of `font-roboto`, fooling your application it actually has Roboto installed.
