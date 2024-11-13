# Car control sample with A-Frame

## How to use

Live site: https://klausw.github.io/a-frame-car-sample/index.html

This is a fork of https://github.com/dala00/a-frame-car-sample to demonstrate
WebXR support in A-Frame and experiment with new features.

Just clone and access index.html. (Server needed for loading resources)
Needs to be served via https:, or on localhost, to enable WebXR APIs.

AR mode needs Chrome 79+ with "WebXR AR Module" enabled in chrome://flags.

The optional DOM Overlay needs "WebXR DOM Overlay" or "WebXR Incubations"
enabled in chrome://flags, it uses a [modified A-Frame
build](https://github.com/klausw/a-frame-car-sample/commit/4116d9d10eda98214a91586bbb3d581e1ca8c3de)
to enable this and doesn't currently work with stock A-Frame. See
https://github.com/aframevr/aframe/issues/4315 for context.

## Resources

### Ground

[pipoya](https://pipoya.net/sozai/)

## License

MIT
