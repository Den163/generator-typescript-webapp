# generator-typescript-modern-webapp [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url]
> 

## Installation

First, install [Yeoman](http://yeoman.io) and generator-typescript-modern-webapp using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g generator-typescript-modern-webapp
```

Then generate your new project:

```bash
yo typescript-modern-webapp
```

## Generated project structure

<bold>src</bold> - is a root folder with your typescript code. Where main.js just makes jquery global and calls static 'main()' method of the Program class. Program class using as an entry point of your web application (Like in Java or C#)

<bold>public</bold> - is a root folder for your web application
<bold>public/js</bold> - contains transpilled javascript code and source maps
<bold>public/css</bold> - contains custom css styles. Style.css importing a [CSS reset](https://meyerweb.com/eric/tools/css/reset/)

src - is a root folder 

## Getting To Know Yeoman

 * Yeoman has a heart of gold.
 * Yeoman is a person with feelings and opinions, but is very easy to work with.
 * Yeoman can be too opinionated at times but is easily convinced not to be.
 * Feel free to [learn more about Yeoman](http://yeoman.io/).

## License

GPL-3.0 © [denis](https://github.com/Den163)


[npm-image]: https://badge.fury.io/js/generator-typescript-modern-webapp.svg
[npm-url]: https://npmjs.org/package/generator-typescript-modern-webapp
[travis-image]: https://travis-ci.org/Den163/generator-typescript-modern-webapp.svg?branch=master
[travis-url]: https://travis-ci.org/Den163/generator-typescript-modern-webapp
[daviddm-image]: https://david-dm.org/Den163/generator-typescript-modern-webapp.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/Den163/generator-typescript-modern-webapp
