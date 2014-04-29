# An overview of Pattern Library Generators

Pattern Libraries (or _Style Guides_) are a helpful tool in developing websites. Read more about Creating Style Guides at this [A List Apart article](http://alistapart.com/article/creating-style-guides).

Maintaining a _static_ Pattern Library (in HTML/CSS) is hard work and errorprone. There are, however, various tools that help us _generate_ a dynamic Pattern Library or ['Living Style Guide'](https://speakerdeck.com/hagenburger/style-guide-driven-development).

This page aims to list these tools. If you know of other tools or have other feedback, please let me know or submit a PR. Thanks, [David Hund](https://github.com/davidhund) [@valuedstandards](https://twitter.com/valuedstandards)

**NOTE:** This should list _generators_ only: no Bootstrap, Foundation, Topcoat, etc. but **tools** to _generate_ a Living Style Guide.

**Table of Contents**

- [PHP](#user-content-php)
- [Ruby / RAILS](#user-content-ruby--rails)
- [NodeJS](#user-content-nodejs)
- [Jekyll](#user-content-jekyll)
- [CSS (parsing CSS source)](#user-content-css-parsing-css-source)
- [Grunt Tasks](#user-content-grunt-tasks)
- [Online Services](#user-content-online-services)
- [Other](#user-content-other)
- [Articles](#user-content-articles)

## PHP

### [Pattern Primer](https://github.com/adactio/Pattern-Primer)
> Generating styled markup from a folder of markup snippets.

[Demo](http://patternprimer.adactio.com/) | [Source](https://github.com/adactio/Pattern-Primer) | **PHP, HTML patterns**


### [Pea.rs](http://pea.rs/)
> Pears is an open source WordPress theme, enabling people like you to get your own pattern library up and running quickly.

[Demo](http://pea.rs/) | [Source](https://github.com/simplebits/Pears) | **PHP, Wordpress Theme**


### [Pattern Lab](http://patternlab.io/)
> Pattern Lab is a collection of tools to help you create atomic design systems.

[Demo](http://demo.pattern-lab.info/) | [Source](https://github.com/pattern-lab/patternlab-php) | **PHP, Static Generator, Grunt Task**


### [Drupal Project Styleguide](https://drupal.org/project/styleguide)
> Provides a visual testing page for Drupal themes.

[Demo](http://styleguide.allgoo.de/) | [Source](https://drupal.org/project/styleguide) | **PHP, Drupal**


### [Style Guide Boilerplate](https://github.com/bjankord/Style-Guide-Boilerplate)
> A starting point for crafting living style guides.

[Demo](http://bjankord.github.io/Style-Guide-Boilerplate/) | [Source](https://github.com/bjankord/Style-Guide-Boilerplate) | **PHP, HTML patterns**


### [Style Guide Boilerplate Bootstrap Edition](http://www.monolinea.com/labs/bootstrap-style-guide-boilerplate/)
> A starting point for crafting living style guides for Bootstrap-based projects.

[Demo](http://www.monolinea.com/projects/styleguide/) | [Source](https://github.com/kemie/Style-Guide-Boilerplate-Bootstrap-Edition) | **PHP, HTML patterns, Bootstrap**


### [Barebones](http://barebones.paulrobertlloyd.com/)
> An initial directory setup, style guide and pattern primer. Intended as a starting point for […] projects…

[Demo](http://barebones.paulrobertlloyd.com/) | [Source](https://github.com/paulrobertlloyd/barebones) | **PHP, HTML patterns**


## Ruby / RAILS

### [Pattern Primer on Ruby](https://github.com/micdijkstra/Pattern-Primer-Ruby)
[Source](https://github.com/micdijkstra/Pattern-Primer-Ruby) | **Ruby, HTML patterns**


### [Living Styleguide](http://livingstyleguide.org/)
> The easiest way to create front-end style guides with Sass and Compass

[Demo](https://github.com/hagenburger/livingstyleguide-example) | [Source](https://github.com/hagenburger/livingstyleguide) | **Ruby, Markdown, Sass**


## NodeJS

### [Source JS](http://sourcejs.com/)
> Front-end documentation engine

[Demo](http://sourcejs.com/docs/) | [Source](https://github.com/sourcejs/Source) | **NodeJS, Grunt, RequireJS, LESS**


### [Tapestry App](http://www.pebbleroad.com/labs/tapestry)
> A free app that gives you an interface to store and manage your front-end patterns.

[Demo](http://demos.pebbleroad.com/tapestry/src/) | [Source](https://github.com/PebbleRoad/tapestry) | **NodeJS, Gulp, Angular, Markdown/YAML**


### [Team-Sass / generator-style-prototype](https://github.com/team-sass/generator-style-prototype)
> Yeoman Generator for Style Prototypes

[Source](https://github.com/team-sass/generator-style-prototype) | **NodeJS, Yeoman, Ruby, Git**


### [Pattern Primer on Node](https://github.com/codetwizzle/Pattern-Primer-on-Node)
[Source](https://github.com/codetwizzle/Pattern-Primer-on-Node) | **NodeJS, HTML patterns**


### [Pattern Lab on Node](https://github.com/midnightspecial/patternlab-node)
[Source](https://github.com/midnightspecial/patternlab-node) | **NodeJS, Static Site Generator, Mustache patterns**


### [Fabricator](https://github.com/resource/fabricator)
[Source](https://github.com/resource/fabricator) | **NodeJS, Gulp, Markdown, Static Site Generator, Mustache patterns**

> A tool for creating modular website toolkits


## Jekyll

### [Jekyll Styleguide](https://github.com/davidhund/jekyll-styleguide)
> Using Jekyll Styleguide you can generate a Pattern Library and add patterns by simply adding new files to the `_posts` folder. Includes a GulpJS workflow that compiles Sass auto-builds Jekyll and refreshes your browser :)

[Demo](https://davidhund.github.io/jekyll-styleguide) | [Source](https://github.com/davidhund/jekyll-styleguide) | **Jekyll, Static Site Generator, Markdown, Gulp**

### [Pattern Primer on Jekyll](https://github.com/opattison/Pattern-Primer-Jekyll)
[Source](https://github.com/opattison/Pattern-Primer-Jekyll) | **Jekyll, Static Site Generator**


## CSS (parsing CSS source)

These tools define a documenting syntax for CSS. You would e.g. write your components' HTML in a comment above the component's CSS and the tool would generate a Styleguide from it.

### [Knyle Style Sheets: KSS](http://warpspire.com/kss/)
> KSS is intended to help automate the creation of a living styleguide. A styleguide serves as a place to publish KSS documentation and visualize different states of UI elements defined in your CSS.

[Demo](http://warpspire.com/kss/) | [Source](https://github.com/kneath/kss) | **\*CSS, Ruby**

### [KSS on Node](http://hughsk.io/kss-node/)
[Demo](http://hughsk.io/kss-node/) | [Source](https://github.com/hughsk/kss-node) | **\*CSS, NodeJS, KSS**


### [KSS Middleman](https://github.com/Darep/middleman-styleguide-template)
[Source](https://github.com/Darep/middleman-styleguide-template) | **\*CSS, Ruby, MiddleMan, KSS**


### [Middleman KSS](http://github.com/smt/middleman-kss)
[Source](http://github.com/smt/middleman-kss) | **\*CSS, Ruby, MiddleMan, KSS**


### [StyleDocco](http://jacobrask.github.io/styledocco/)
> StyleDocco generates documentation and style guide documents from your stylesheets.

[Source](https://github.com/jacobrask/styledocco/issues) | **\*CSS, NodeJS, Markdown**


### [DSS](https://github.com/darcyclarke/DSS)
> DSS, Documented Style Sheets, is a comment styleguide and parser for CSS, LESS, STYLUS, SASS and SCSS code.

[Source](https://github.com/darcyclarke/DSS) | **\*CSS, NodeJS, Grunt, Sublime Plugin**


### [Kalei Style guide](http://kaleistyleguide.com/)
> Generates bootstrap-like documentation for your own CSS!

[Source](git://github.com/thomasdavis/kaleistyleguide.git) | **\*CSS, JS, Backbone, Underscore, Markdown**


### [Hologram](http://trulia.github.io/hologram/)
> Hologram is a Ruby gem that parses comments in your CSS and turns them into a beautiful style guide.

[Demo](http://trulia.github.io/hologram-example/base_css.html) | **\*CSS, Ruby, Markdown**


### [Styleguide.js](https://github.com/EightMedia/styleguide.js)
> Generate a styleguide from your CSS, by adding YAML data in the comments. It generates a self-contained html file. Works great for component based CSS.

[Demo](https://rawgithub.com/EightMedia/styleguide.js/master/test/expected/index.html) | [Source](https://github.com/EightMedia/styleguide.js) | **\*CSS, NodeJS, Coffeescript, YAML**


### [YSS](http://yago.io/project/yss/)
> YSS is styleguide framework written in PHP and jQuery. It display nicely all your commented CSS […]

[Demo](http://yago.io/project/yss/) | [Source](https://github.com/Yago31/YSS) | **CSS, PHP, jQuery, Markdown**


## Grunt Tasks

### [Sassdown](https://github.com/nopr/sassdown)
> Grunt plugin for building living styleguides with Handlebars from Markdown comments in CSS, SASS and LESS files.

[Source](https://github.com/nopr/sassdown) | **GruntJS, Handlebars, Markdown**


### [Pattern Primer on Grunt](https://github.com/asciidisco/grunt-patternprimer)
[Source](https://github.com/asciidisco/grunt-patternprimer) | **GruntJS, HTML patterns**


## Online Services

These services provide a web-app to generate your styleguide. Some require an account

### [Element CSS](http://elementcss.com/)
> ElementCSS is the easiest way for designers, clients and front-end developers to create, edit and view website style guides in the medium they're intended for — the browser.

[Service](http://elementcss.com) | [Demo](http://elementcss.com/gallery) | **Service, Login**


### [Patternry](http://patternry.com/)
[Service](http://patternry.com/) | **Service, Login, (Commercial)**


## Other

### [Stylify Me](http://stylifyme.com)
> Stylify Me extracts the styles of a given website and displays them in a styleguide

[Demo](http://stylifyme.com/?stylify=github.com) | **Extract, Example**


### [Survival Kit](https://github.com/canarymason/survival-kit)
> Tools and defaults for designing websites in the brower.

[Source Kit](https://github.com/canarymason/survival-kit) | **Templates, HTML, Sass, Compass, Styletiles**


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
