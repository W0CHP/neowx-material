# NeoWX Material

**The most versatile and modern weewx skin**

You want a modern UI for your weather station and its archive?

Including translation, customization, great appearance on tablets and
smartphones, and even a dark mode?

Then this skin is the one you're looking for!

This is the new version of the famous NeoWX (based on Sofaskin), 
including a modern Material Design UI, full weather data archive, 
and many more new features.

## Key features

- beautiful Material Design
- many color schemes to choose from- 
- interactive and zoomable graphs
- wind direction + speed visualization as a wind rose
- accessible HTML + NOAA TXT file archive for all years and months
- easy translation - provides many languages out of the box! 
  (or add your own translation)
- auto dark mode - works great on mobile and desktop
- responsive design - optimized for modern tablets and smartphones
- support for all available sensors (not all yet - but we're working on it!)
- many options to customize your reports even more - 
  have a look at the skin.conf
- ...and much more!

Learn more about all features on our project page: 
[NeoWX Material | Neoground Projects](https://projects.neoground.com/neowx-material).

## Contribution

Feel free to add your own improvements. Contributions are always welcome!

Our previous skin, NeoWX, was used all over the world in many countries.
We hope that this skin will do the same. Please consider translating our skin
in your language.

If you want to provide any improvements, feel free to create a pull request.
We use [Gitmoji](https://gitmoji.dev/) commit messages.

## Development

Setting up the development environment is easy:

- clone / download repository
- install npm packages (`yarn install` / `npm install`)
- for easy testing create a symlink from your `WEEWX_HOME/skins/neowx-material`
  to the `src` directory
  
For basic tasks npm scripts are available.

Styling is done via SCSS, compile it to `css/style.css` by: `yarn run build-css`.

## Thank You!

This config and some parts of the skin are based on the template code      
of the original "Standard" skin of weewx. Many thanks to Tom Keffer and     
the weewx contributors. 
One of the best solutions for your weather station under linux!

The design is based on 
[Material Design for Bootstrap (MDB) Free](https://mdbootstrap.com).

The NOAA reports, and some parts of the configuration 
are based on the Standard weewx skin as well.

These 3rd party libraries are used:

- [Apexcharts](https://github.com/apexcharts/apexcharts.js) (MIT license)
- [MomentJS](https://github.com/moment/moment) (MIT license)
- [Weather Icons by Erik Flowers](https://github.com/erikflowers/weather-icons)
  (MIT / SIL OFL 1.1 license)

## TODO

- Add missing graphs
- Graph export fix
- Build job
