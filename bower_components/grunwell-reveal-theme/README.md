# Grunwell Reveal.js Theme

This is my custom theme for [Reveal.js](https://github.com/hakimel/reveal.js). It's intended to be loaded via [Bower](http://bower.io/) when using the [Yeoman Reveal.js generator](https://github.com/slara/generator-reveal).

## Installation

1. Start a new Reveal.js project, using the [Reveal.js generator documentation](https://github.com/slara/generator-reveal#revealjs-generator) documentation as a guide.

2. Once installed, run `bower install https://github.com/stevegrunwell/grunwell-reveal-theme.git --save` to download this theme into your presentation.

3. Load the theme in css/source/theme.scss. You can also lose a lot of the default theme as well to save on loading time; the important elements are:

    ```scss
@import "../../bower_components/reveal.js/css/theme/template/mixins";
@import "../../bower_components/reveal.js/css/theme/template/settings";
@import "../../bower_components/reveal.js/css/theme/template/theme";
@import "../../bower_components/grunwell-reveal-theme/grunwell-theme.scss";
    ```

## License

This theme starter is dual-licensed under both the [Don't Be a Dick](http://www.dbad-license.org/) and [WTF](http://www.wtfpl.net/) Public Licenses, which are GPLv2, MIT, and pretty much every-other-license-ever compatible.

Please have fun and build something awesome!