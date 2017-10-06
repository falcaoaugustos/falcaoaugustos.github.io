<p align="center">
 <a href="http://falcaoaugustos.github.io">falcaoaugustos</a> landing page.
</p>

<br>

---

## Table of Contents

- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

## Usage

### Getting Started

Make sure you have the main dependencies:

- [Git](http://git-scm.com/downloads)
- [NodeJS](http://nodejs.org/)

Clone this repository:

```sh
$ git clone https://github.com/falcaoaugustos/falcaoaugustos.github.io.git
```

Install all dependencies:

```sh
$ cd falcaoaugustos.github.io
$ npm install
```

### Structure

If everything from the [Getting Started](#getting-started) section goes well, you should have this:

```
|-- src/
|   |-- images/
|   |-- styles/
|   |-- templates/
|   |-- config.json
|-- tasks/
|   |-- deploy/
|       |-- gh-pages.js
|   |-- build/
|       |-- templates.js
|-- .gitignore
|-- package.json
|-- [...]
```

### Customization

For most of the updates/changes in our page, just go to the
[`config.json`](/src/config.json) file and change the value of variables.

### Workflow

All the tasks needed for development automation are defined in the
[`package.json`](package.json) *scripts* property and can be run via:

`npm run <command>`

Here is a summary of the main commands:

- `build:templates`: **compile** `.pug` files.
- `build:styles`: **compile** `.styl` files.
- `build:images`: **optimize** raster and vector images.
- `build`: **run** all `build:` tasks.
- `deploy`: **deploy** current `dist` to *GitHub Pages*.

## Contributing

Contributions are very welcome! If you'd like to contribute, feel free to send a pull request!

## License

- [falcaoaugustos landing page](https://github.com/falcaoaugustos/falcaoaugustos.github.io) 
source code is licensed under the [MIT License]().

**All contributions are assumed to be also licensed under the same.**

## Credits

- Some of the base of this code were result of inspiration from
written by the [stalkr](https://getstal.kr/) team. Copyright © 2017 [The Stalkr Foundation](https://getstal.kr).