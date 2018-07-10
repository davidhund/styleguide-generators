# An overview of Pattern Library Generators

Pattern Libraries (or _Style Guides_) are a helpful tool in developing websites. Read more about Creating Style Guides at this [A List Apart article](http://alistapart.com/article/creating-style-guides).

Maintaining a _static_ Pattern Library (in HTML/CSS) is hard work and errorprone. There are, however, various tools that help us _generate_ a dynamic Pattern Library or ['Living Style Guide'](https://speakerdeck.com/hagenburger/style-guide-driven-development).

This page aims to list these tools. If you know of other tools or have other feedback, please let me know or submit a PR. Thanks, [David Hund](https://github.com/davidhund) [@valuedstandards](https://twitter.com/valuedstandards)

**NOTE:** This should list _generators_ only: no Bootstrap, Foundation, Topcoat, etc. but **tools** to _generate_ a Living Style Guide.

**Table of Contents**

- [Multiple](#multiple)
- [PHP](#user-content-php)
- [Python / Flask](#user-content-python--flask)
- [Ruby / RAILS](#user-content-ruby--rails)
- [ReactJS](#user-content-react)
- [VueJs](#user-content-vue)
- [NodeJS](#user-content-nodejs)
- [Jekyll](#user-content-jekyll)
- [Angular](#user-content-angular)
- [CSS (parsing CSS source)](#user-content-css-parsing-css-source)
- [Grunt / Gulp Tasks](#user-content-grunt--gulp-tasks)
- [Online Services](#user-content-online-services)
- [Other](#user-content-other)
- [Articles](#user-content-articles)

## Multiple

### Storybook
> The UI development environment you'll love to use. 

Storybook is a UI development environment for your UI components. With it, you can visualize different states of your UI components and develop them interactively. Then generate a static styleguide to host anywhere.

[Demos](https://storybook.js.org/examples/) [Docs](https://storybook.js.org/) [Source](https://github.com/storybooks/storybook) | *React, React-Native, Preact, Vue, Angular, Polymer, Webcomponents, HTML**

## PHP

### [Pattern Primer](https://github.com/adactio/Pattern-Primer)
> Generating styled markup from a folder of markup snippets.

[Demo](http://patternprimer.adactio.com/) | [Source](https://github.com/adactio/Pattern-Primer) | **PHP, HTML patterns**


### [Pattern Lab](http://patternlab.io/)
> Pattern Lab is a collection of tools to help you create atomic design systems.

[Demo](http://demo.patternlab.io/) | [Source](https://github.com/pattern-lab/patternlab-php) | **PHP, Atomic, Static Generator, Grunt Task**


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

### [atomicdocs](http://atomicdocs.io/)
> Atomic Docs is a front end style guide generator and Scss/Less/Stylus partial manager. Atomic Docs is built in PHP and Sass.

[Demo](http://www.nickberens.me/atomic-docs/atomic-core/base.php) | [Source](https://github.com/nickberens360/atomic-docs) | **PHP, Atomic, HTML patterns**


## Python / Flask

### [Flask-Styleguide](https://github.com/vitalk/flask-styleguide)
> A living style guide for your Flask application.

[Demo](https://vitalk.github.io/flask-styleguide-example) | [Source](https://github.com/vitalk/flask-styleguide) | [Documentation](http://flask-styleguide.readthedocs.org/en/latest/) | **Python, Flask, KSS**


## Ruby / RAILS

### [Pattern Primer on Ruby](https://github.com/micdijkstra/Pattern-Primer-Ruby)
[Source](https://github.com/micdijkstra/Pattern-Primer-Ruby) | **Ruby, HTML patterns**


### [Living Style Guide](http://livingstyleguide.org/)
> The easiest way to create front-end style guides with Sass and Compass

[Demo](http://www.homify.de/assets/styleguide.html) | [Open source demo](http://livingstyleguide.com/eurucamp/) | [Source](https://github.com/hagenburger/livingstyleguide) | **Ruby, Markdown, Sass**

### [Mountain View](https://github.com/jgnatch/mountain_view/)
[Source](https://github.com/jgnatch/mountain_view/) | **Ruby, Rails, Components**


## React

### [Bluekit](http://bluekit.blueberry.io/)
[Demo](http://bluekit.blueberry.io/) | [Source](https://github.com/blueberryapps/react-bluekit) | **React, components**

### [React Styleguidist](https://github.com/styleguidist/react-styleguidist)
[Demo](http://react-styleguidist.js.org/) | **React, Markdown, components**

### [Catalog](https://interactivethings.github.io/catalog/)
> Catalog lets you create beautiful living and fully interactive style guides using Markdown and React components.

[Source](https://github.com/interactivethings/catalog) | [Demo](https://interactivethings.github.io/catalog/) **React, NodeJS, CLI, Markdown, components**

### [React Showroom](https://github.com/OpusCapita/react-showroom-client)
> React components catalog with live examples and documenting using markdown

[Source](https://github.com/OpusCapita/react-showroom-client) | [Demo](https://opuscapita.github.io/react-rich-editors) **React, Markdown, components**

## Vue

### [Vue Styleguidist](https://github.com/vue-styleguidist/vue-styleguidist)
[Demo](http://rafaelescala.com/vue-styleguide/) | [Source](https://github.com/vue-styleguidist/vue-styleguidist) | **Vue, Markdown, components**


## NodeJS

### [Stylemark](https://github.com/nextbigsoundinc/stylemark)
> A living style guide generator for everything&mdash;CSS, JS, React, Angular, and more.

[Demo](http://stylemark-bootstrap.surge.sh/) | [Source](https://github.com/nextbigsoundinc/stylemark) | **Static Site Generator, NodeJS, Markdown, React, Angular, Ember, CSS, LESS, SASS**


### [DocumentCSS](http://documentcss.com/)
> Create a live style guide that can easily expand into a documentation hub. Store all kinds of documentation, from design rationale, to CSS, JS, and API docs.

[Demo](http://documentcss.com/examples/styles/variables.less.html) | [Source](https://github.com/bitovi/documentcss) | **NodeJS, Markdown, Custom Tags, Static Site Generator**


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


### [Pattern Lab on Node](https://github.com/pattern-lab/patternlab-node)
[Source](https://github.com/pattern-lab/patternlab-node) | **NodeJS, Static Site Generator, Mustache patterns**


### [patternplate](https://github.com/sinnerschrader/patternplate)
> patternplate is a platform designed to help you create and maintain component libraries.

[Source](https://github.com/sinnerschrader/patternplate) | **NodeJS, React (jsx) patterns, LESS**

### [Fabricator](http://fbrctr.github.io)
> A tool for building website UI toolkits

[Demo](http://fbrctr.github.io/demo/) | [Source](https://github.com/fbrctr/fabricator) | **NodeJS, Gulp, Markdown, Static Site Generator, Mustache patterns**

### [Component Styleguide](https://github.com/webpro/component-styleguide)
> Simple styleguide framework

[Demo](http://component-styleguide-example.webpro.nl) | [Source](https://github.com/webpro/component-styleguide) | **NodeJS, HTML & Handlebars patterns**

### [Fractal](http://fractal.build/)
> A tool to help you build and document web component libraries and then integrate them into your projects. By default, Fractal uses Handlebars to render so called view templates, but you are free to use a different template engine.

[Source](https://github.com/frctl/fractal) | **NodeJS, Markdown, Handlebars**


### [Astrum](http://astrum.nodividestudio.com/)
> A lightweight, non-opinionated, pattern library designed to be included with any web project.

[Source](https://github.com/NoDivide/astrum) | **NodeJS, CLI, Markdown**


### [Swanky Docs](https://swanky-docs.org/)
> A simple, flexible and powerful ecosystem for creating beautiful documentation.

[Source](https://github.com/swanky-docs) | **NodeJS, CLI, Markdown**


### [Component Library](https://github.com/sneas/component-library)
> An easy way to create HTML styleguide for a web project.

[Source](https://github.com/sneas/component-library) | [Demo](http://sneas.github.io/component-library/index.html) | **NodeJS, HTML, Static Site Generator**


### [Drizzle](https://cloudfour.com/thinks/introducing-drizzle/)
> A streamlined tool for developing, documenting and presenting UI pattern libraries.

[Source](https://github.com/cloudfour/drizzle/) | [Demo](https://cloudfour.github.io/drizzle/) | **NodeJS, Gulp, Handlebards, Static Site Generator**


### [UIengine](https://github.com/dennisreimann/uiengine)
> The UIengine is a tool for developers, designers and product owners to create, document and evolve a design system collaboratively. It generates your design system documentation (i.e. pattern library, styleguide or brand manual) and brings the tools to implement the design system in your web site or application.

[Source](https://github.com/dennisreimann/uiengine) | **NodeJS, Gulp, CLI, Markdown, YAML, Templating agnostic (Pug, React/JSX, Handlebars, …)**

### [Fepper](http://fepper.io)                                                                                           
> Easily integrate your pattern library into your web application! Or even just output a static site!

[Source](https://github.com/electric-eloquence/fepper) | **NodeJS, Prototype to Webapp Interface, Static Site Generator, Mustache/[Feplet](https://www.npmjs.com/package/feplet)**

### [Malvid](https://malvid.io/)
> Developing components. The right way. Generate an interactive UI to develop, preview and document web components.

[Source](https://github.com/Malvid/Malvid) | **NodeJS, EJS, Twig, Nunjucks, Babel**


## Jekyll

### [Jekyll Styleguide](https://github.com/davidhund/jekyll-styleguide)
> Using Jekyll Styleguide you can generate a Pattern Library and add patterns by simply adding new files to the `_posts` folder. Includes a GulpJS workflow that compiles Sass auto-builds Jekyll and refreshes your browser :)

[Demo](https://davidhund.github.io/jekyll-styleguide) | [Source](https://github.com/davidhund/jekyll-styleguide) | **Jekyll, Static Site Generator, Markdown, Gulp**

### [Pattern Primer on Jekyll](https://github.com/opattison/Pattern-Primer-Jekyll)
[Source](https://github.com/opattison/Pattern-Primer-Jekyll) | **Jekyll, Static Site Generator**


## Angular

### [UI-jar](https://github.com/ui-jar/ui-jar)
> Test Driven Style Guide Development - Angular (2.x and above). 
A drop in module to automatically create a living style guide based on the test you write for your components.
Bundle with your favorite build tool and you will automatically get a web app where you can view examples of each component together with associated documentation.

[Source](https://github.com/ui-jar/ui-jar) | **Angular (2.x and above), Test Driven Style Guide Development**


## CSS (parsing CSS source)

These tools define a documenting syntax for CSS. You would e.g. write your components' HTML in a comment above the component's CSS and the tool would generate a Styleguide from it.

### [Knyle Style Sheets: KSS](http://warpspire.com/kss/)
> KSS is intended to help automate the creation of a living styleguide. A styleguide serves as a place to publish KSS documentation and visualize different states of UI elements defined in your CSS.

[Demo](http://warpspire.com/kss/) | [Source](https://github.com/kneath/kss) | **\*CSS, Ruby**

### [KSS on Node](http://kss-node.github.io/kss-node/)
[Demo](http://kss-node.github.io/kss-node/) | [Source](https://github.com/hughsk/kss-node) | **\*CSS, NodeJS, KSS**


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


### [Hologram](http://trulia.github.io/hologram/)
> Hologram is a Ruby gem that parses comments in your CSS and turns them into a beautiful style guide.

[Demo](http://trulia.github.io/hologram-example/base_css.html) | **\*CSS, Ruby, Markdown**

### [Nucleus](https://holidaypirates.github.io/nucleus/)
> Nucleus is a living style guide generator for atomic css based components.

[Demo](https://holidaypirates.github.io/nucleus/demo/index.html) | **\*SCSS, NodeJS**


### [Styleguide.js](https://github.com/EightMedia/styleguide.js)
> Generate a styleguide from your CSS, by adding YAML data in the comments. It generates a self-contained html file. Works great for component based CSS.

[Demo](https://rawgithub.com/EightMedia/styleguide.js/master/test/expected/index.html) | [Source](https://github.com/EightMedia/styleguide.js) | **\*CSS, NodeJS, Coffeescript, YAML**


### [YSS](http://yago.io/project/yss/)
> YSS is styleguide framework written in PHP and jQuery. It display nicely all your commented CSS […]

[Demo](http://yago.io/project/yss/) | [Source](https://github.com/Yago31/YSS) | **CSS, PHP, jQuery, Markdown**


### [postcss-style-guide](https://github.com/morishitter/postcss-style-guide)
> [PostCSS](https://github.com/postcss/postcss) plugin. CSS comments will be parsed through Markdown and displayed in a generated HTML document.

[Source](https://github.com/morishitter/postcss-style-guide) | **CSS, NodeJS, GruntJS, GulpJS, Markdown**


### [mdcss](https://github.com/jonathantneal/mdcss)
> [PostCSS](https://github.com/postcss/postcss) plugin. Easily create and maintain style guides with CSS comments using Markdown.

[Demo](http://jonathantneal.github.io/mdcss-theme-github/demo/) | [Source](https://github.com/jonathantneal/mdcss) | **CSS, PostCSS, NodeJS, GruntJS, GulpJS, Markdown**


### [aigis](https://pxgrid.github.io/aigis/)
> Aigis is a Node.js package that parses comments in your CSS and auto-generate a style guide. It is similar to Hologram, like a Node.js implementation of Hologram.

[Demo](https://pxgrid.github.io/aigis/sample/category/base/index.html) | [Source](https://github.com/pxgrid/aigis) | **CSS, NodeJS, [GulpJS](https://pxgrid.github.io/gulp-aigis/), Markdown**


### [Styledown](https://github.com/styledown/styledown)
> Styledown is made to work in most web development setups. It doesn't favor any framework or language or any preprocessor.

[Demo](http://cdn.rawgit.com/styledown/styledown/v1.0.2/examples/bootstrap/index.html) | [Source](https://github.com/styledown/styledown) | **CSS, NodeJS, Markdown**


### [markdown-styleguide-generator](https://github.com/emiloberg/markdown-styleguide-generator)
> Markdown-styleguide-generator will search all your style files (your .css, .scss _partial.scss, .less, .whatever) for comments and create a html file living style guide for your developers to use.

[Source](https://github.com/emiloberg/markdown-styleguide-generator) | **CSS, Less, Markdown, NodeJS, Gulp, Grunt**

### [Atlas-guide](https://github.com/dimanech/atlas-guide)
> Atlas will search comments in scss and regular markdown files and create html structure based on this. It comes with extensive styles monitoring and project reports. It is similar to Hologram.

[Source](https://github.com/dimanech/atlas-guide) | [Demo](https://dimanech.github.io/atlas-guide/) | **NodeJS, Mustache, Markdown, Static Site Generator**



## Grunt / Gulp Tasks


### [SC5 style guide generator](http://styleguide.sc5.io/)
> CLI, gulp/grunt task to create style guides from stylesheets using KSS notation.

[Demo](http://styleguide.sc5.io/) | [Source](https://github.com/SC5/sc5-styleguide) | **GruntJS, GulpJS, \*CSS, NodeJS, KSS, Gulp, Grunt**

### [Sassdown](https://github.com/nopr/sassdown)
> Grunt plugin for building living styleguides with Handlebars from Markdown comments in CSS, SASS and LESS files.

[Source](https://github.com/nopr/sassdown) | **GruntJS, Handlebars, Markdown**

### [PatternPack](http://patternpack.org/)
> Build and Document Your Interface. Then Share the Code.

[Source](https://github.com/patternpack/patternpack) | **GruntJS, Markdown**

### [Pattern Primer on Grunt](https://github.com/asciidisco/grunt-patternprimer)
[Demo](http://patternprimer.adactio.com/) | [Source](https://github.com/asciidisco/grunt-patternprimer) | **GruntJS, HTML patterns**

### [Devbridge Styleguide](http://livingstyleguide.devbridge.com/)
> Devbridge Styleguide helps you create, share, and automate a living visual style library of your brand. Share your digital brand standards, improve team collaboration, and implement an independent easily-extendable modular structure.

[Demo](http://styleguide.devbproto.com/styleguide/) | [Source](https://github.com/devbridge/Styleguide) | **NodeJS, GulpJS, GruntJS, Scss, Less, HTML patterns**

## Online Services

These services provide a web-app to generate your styleguide. Some require an account

### [Frontify Style Guide](https://frontify.com/styleguide)
> You can create design, brand or UI guidelines with the Frontify Style Guide editor. Use existing templates or start from scratch by choosing from over 20 smart blocks (like colors, media, typography, UI elements, & more) - For Non-coders and coders =)

[Service](https://frontify.com/styleguide) | **Service, Login, Free (“Powered by Frontify”), Commercial ($9/$49)**

### [Patternry](http://patternry.com/)
[Service](http://patternry.com/) | **Service, Login, (Commercial)**

### [Runway](http://runway-app.cfapps.io/)
> Go from stylesheet to styleguide, instantly. Runway parses comments in your CSS/SCSS and deploys a beautiful, shareable styleguide. Choose between multiple themes / syntax highlighting choices, and tweak your styleguide in realtime through an interactive editor.

[Service](http://runway-app.cfapps.io/) | **Service, Login, Free**

## Other

### [Simple style guide](https://github.com/Dkogan90/simple-style-guide)
> A Simple style guide generator/template that uses handlebars and markdown syntax. This tool creates documentation for your already developed js and css files.

[Source](https://github.com/Dkogan90/simple-style-guide) | **Grunt, Markdown, highlightJs, Template, Sass,  Static Site Generator**

### [Stylify Me](http://stylifyme.com)
> Stylify Me extracts the styles of a given website and displays them in a styleguide

[Demo](http://stylifyme.com/?stylify=github.com) | **Extract, Example**


### [North Generator Style Prototype](https://github.com/north/generator-style-prototype)
> Yeoman Generator for Style Prototypes

[Yeoman Generator](https://github.com/north/generator-style-prototype) | **Templates, Sass, Compass, Yeoman, Grunt,Bower, Styletiles**


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
* [paulrobertlloyd.com/styleguide/](http://paulrobertlloyd.com/styleguide/)
* [UI component playbook](https://blog.hichroma.com/ui-component-playbook-fd3022d00590)
