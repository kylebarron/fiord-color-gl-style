# Fiord Color
[![Build Status](https://travis-ci.org/openmaptiles/fiord-color-gl-style.svg?branch=master)](https://travis-ci.org/openmaptiles/fiord-color-gl-style)

A basemap style useful with fiord color ideal as background map for data visualizations. It is using the vector tile
schema of [OpenMapTiles](https://github.com/openmaptiles/openmaptiles).

## Fork updates

### Hosted sprite

The sprites are also hosted from this repository.

To make the sprite:

1. Install spritezero-cli: `npm install -g @mapbox/spritezero-cli`
2. Make the `sprite` dir: `mkdir -p sprite && cd sprite`
3. Generate the low resolution sprite: `spritezero fiord-color-gl-style ../icons/`
4. Generate the high resolution sprite: `spritezero --retina fiord-color-gl-style@2x ../icons/`

## Preview

**[:globe_with_meridians: Browse the map](https://openmaptiles.github.io/fiord-color-gl-style/)**

<img src="https://github.com/openmaptiles/fiord-color-gl-style/raw/gh-pages/preview/preview-15.png" width="600" title="Preview Zurich">

<img src="https://github.com/openmaptiles/fiord-color-gl-style/raw/gh-pages/preview/preview-10.png" width="600" title="Preview Lake Zurich">

<img src="https://github.com/openmaptiles/fiord-color-gl-style/raw/gh-pages/preview/preview-7.png" width="600" title="Preview Switzerland">

<img src="https://github.com/openmaptiles/fiord-color-gl-style/raw/gh-pages/preview/preview-4.png" width="600" title="Preview Europe">

## Edit the Style

Use the [Maputnik CLI](http://openmaptiles.org/docs/style/maputnik/) to edit and develop the style.
After you've started Maputnik open the editor on `localhost:8000`.

```
maputnik --watch --file style.json
```


## License

- [ ] Clarify license
