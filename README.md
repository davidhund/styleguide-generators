# An overview of Pattern Library Generators

Pattern Libraries (or _Style Guides_) are a helpful tool in developing websites. Read more about Creating Style Guides at this [A List Apart article](http://alistapart.com/article/creating-style-guides).

Maintaining a _static_ Pattern Library (in HTML/CSS) is hard work and errorprone. There are, however, various tools that help us _generate_ a dynamic Pattern Library or ['Living Style Guide'](https://speakerdeck.com/hagenburger/style-guide-driven-development).

This page aims to list these tools. If you know of other tools, please a PR ;)

**NOTE:** This should list _generators_ only: no Bootstrap, Foundation, Topcoat, etc. but **tools** to _generate_ a Living Style Guide.

<!-- TOC -->

## PHP

These tools are built on PHP (and therefore require running a (local) webserver.)

* **[Pattern Primer](https://github.com/adactio/Pattern-Primer)** - [Demo](http://patternprimer.adactio.com/) | [Source](https://github.com/adactio/Pattern-Primer)
> Generating styled markup from a folder of markup snippets.
* **[Pea.rs](http://pea.rs/)** - [Demo](http://pea.rs/) | [Source](https://github.com/simplebits/Pears)
> Pears is an open source WordPress theme, enabling people like you to get your own pattern library up and running quickly.
* **[Pattern Lab](http://patternlab.io/)** - [Demo](http://demo.pattern-lab.info/) | [Source](https://github.com/pattern-lab/patternlab-php)
> Pattern Lab is a collection of tools to help you create atomic design systems.
* **[Drupal Project Styleguide](https://drupal.org/project/styleguide)** - [Demo](http://styleguide.allgoo.de/) | [Source](https://drupal.org/project/styleguide)
> Provides a visual testing page for Drupal themes.
* **[Style Guide Boilerplate](https://github.com/bjankord/Style-Guide-Boilerplate)** - [Demo](http://bjankord.github.io/Style-Guide-Boilerplate/) | [Source](https://github.com/bjankord/Style-Guide-Boilerplate)
> A starting point for crafting living style guides.
* **[Barebones](http://barebones.paulrobertlloyd.com/)** - [Demo](http://barebones.paulrobertlloyd.com/) | [Source](https://github.com/paulrobertlloyd/barebones)
> An initial directory setup, style guide and pattern primer. Intended as a starting point for my own projects, Barebones is freely available to fork and adapt for your own needs.


## RUBY / RAILS

* **[Pattern Primer on Ruby](https://github.com/micdijkstra/Pattern-Primer-Ruby)**
* **[Living Styleguide](http://livingstyleguide.org/)** - [Demo](https://github.com/hagenburger/livingstyleguide-example) | [Source](https://github.com/hagenburger/livingstyleguide)
> The easiest way to create front-end style guides with Sass and Compass
* **[Element CSS](http://elementcss.com/)** - [Demo](http://elementcss.com/gallery)
> ElementCSS is the easiest way for designers, clients and front-end developers to create, edit and view website style guides in the medium they're intended for — the browser.

## NodeJS

These tools are built on NodeJS (and therefore require running a (local) webserver.)

* **[Source JS](http://sourcejs.com/)** - [Demo](http://sourcejs.com/docs/) | [Source](https://github.com/sourcejs/Source)
> Front-end documentation engine
* **[Tapestry App](http://www.pebbleroad.com/labs/tapestry)** - [Demo](http://demos.pebbleroad.com/tapestry/src/) | [Source](https://github.com/PebbleRoad/tapestry)
> A free app that gives you an interface to store and manage your front-end patterns.
* **[Team-Sass / generator-style-prototype](https://github.com/team-sass/generator-style-prototype)** - [Source](https://github.com/team-sass/generator-style-prototype)
> Yeoman Generator for Style Prototypes
* **[Pattern Primer on Node](https://github.com/codetwizzle/Pattern-Primer-on-Node)**
* **[Pattern Lab on Node](https://github.com/midnightspecial/patternlab-node)**
* **[KSS on Node](http://hughsk.io/kss-node/)**


## Static Site Generators (e.g. Jekyll)

These tools generate a _static_ Style Guide website: a folder of static files.

* **[Jekyll Styleguide](https://github.com/davidhund/jekyll-styleguide)** - [Demo](https://davidhund.github.io/jekyll-styleguide) | [Source](https://github.com/davidhund/jekyll-styleguide)
> Using Jekyll Styleguide you can generate a Pattern Library and add patterns by simply adding new files to the `_posts` folder. Includes a GulpJS workflow that compiles Sass auto-builds Jekyll and refreshes your browser :)
* **[Pattern Primer on Jekyll](https://github.com/opattison/Pattern-Primer-Jekyll)**
* **[KSS Middleman](https://github.com/Darep/middleman-styleguide-template)**
* **[Middleman KSS](http://github.com/smt/middleman-kss)**


## CSS (parsing CSS source)

These tools define a documenting syntax for CSS. You would e.g. write your components' HTML in a comment above the component's CSS and the tool would generate a Styleguide from it.

* **[Knyle Style Sheets: KSS](http://warpspire.com/kss/)** - [Demo](http://warpspire.com/kss/) | [Source](https://github.com/kneath/kss)
> KSS is intended to help automate the creation of a living styleguide. A styleguide serves as a place to publish KSS documentation and visualize different states of UI elements defined in your CSS.
* **[StyleDocco](http://jacobrask.github.io/styledocco/)** - [Source](https://github.com/jacobrask/styledocco/issues)
> StyleDocco generates documentation and style guide documents from your stylesheets.
* **[DSS](https://github.com/darcyclarke/DSS)**
> DSS, Documented Style Sheets, is a comment styleguide and parser for CSS, LESS, STYLUS, SASS and SCSS code.
* **[Kalei Style guide](http://kaleistyleguide.com/)** - [Source](git://github.com/thomasdavis/kaleistyleguide.git)
> Generates bootstrap-like documentation for your own CSS!
* **[Hologram](http://trulia.github.io/hologram/)** - [Demo](http://trulia.github.io/hologram-example/base_css.html)
> Hologram is a Ruby gem that parses comments in your CSS and turns them into a beautiful style guide.

## Grunt Tasks

* **[Sassdown](https://github.com/nopr/sassdown)**
> Grunt plugin for building living styleguides with Handlebars from Markdown comments in CSS, SASS and LESS files.
* **[Pattern Primer on Grunt](https://github.com/asciidisco/grunt-patternprimer)**

## Other

* **[Stylify Me](http://stylifyme.com)** - [Demo](http://stylifyme.com/?stylify=github.com)
> Stylify Me extracts the styles of a given website and displays them in a styleguide
* **[Survival Kit](https://github.com/canarymason/survival-kit)** (Compass)
> Tools and defaults for designing websites in the brower.
* http://patternry.com/ **(Commercial)**


## Articles

* [24ways.org/2011/front-end-style-guides/](http://24ways.org/2011/front-end-style-guides/)
* [styletil.es/](http://styletil.es/)
* [maban.co.uk/66/](http://maban.co.uk/66/)
* [gimmebar.com/.../front-end-styleguides-and-pattern-libraries](https://gimmebar.com/collection/4ecd439c2f0aaad734000022/front-end-styleguides-and-pattern-libraries)
* [alistapart.com/article/creating-style-guides](http://alistapart.com/article/creating-style-guides)
* [patternlab.io/resources.html](http://patternlab.io/resources.html)
* [kippt.com/asiermartinez/style-guides](https://kippt.com/asiermartinez/style-guides)
* [bradfrost.github.io/this-is-responsive/](http://bradfrost.github.io/this-is-responsive/)
* [docs.google.com/spreadsheet/](https://docs.google.com/spreadsheet/ccc?key=0AiN0QfBTPpOCdDFjWlM0eU1ra21XanZkekxGbjA2WWc#gid=0)
* [medium.com/daily-ui-ux-inspirations/](https://medium.com/daily-ui-ux-inspirations/e5bb62db91e5)
* [speakerdeck.com/.../style-guide-driven-development](https://speakerdeck.com/hagenburger/style-guide-driven-development)
* [speakerdeck.com/.../improving-your-responsive-workflow-with-style-guides](https://speakerdeck.com/lukebrooker/improving-your-responsive-workflow-with-style-guides)
* [paulrobertlloyd.com/about/styleguide/](http://paulrobertlloyd.com/about/styleguide/)

