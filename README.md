# Express JS Quickstart
> A starter project generated with the Express CLI

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/express-quickstart?include_prereleases&sort=semver)](https://github.com/MichaelCurrin/express-quickstart/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Node.js](https://img.shields.io/badge/Node.js->=12-blue?logo=node.js&logoColor=white)](https://nodejs.org)
[![Package - express](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/express-quickstart/express?logo=express&logoColor=white)](https://www.npmjs.com/package/express)
[![Known Vulnerabilities](https://snyk.io/test/github/MichaelCurrin/express-quickstart/badge.svg)](https://snyk.io/test/github/MichaelCurrin/express-quickstart)


## Requirements

- [Node.js](https://nodejs.org)


## Installation

### Install system dependencies

Install Node.js using insructions in this [gist](https://gist.github.com/MichaelCurrin/aa1fc56419a355972b96bce23f3bccba).

### Clone

Clone the repo:

```sh
$ git clone git@github.com:MichaelCurrin/express-quickstart.git
$ cd express-quickstart
```

### Install project dependencies

```sh
$ npm install
```


## Usage

### Serve

Start the local dev server.

```sh
$ npm start
```

Open in the browser:

- Homepage: http://localhost:3000
- Users endpoint: http://localhost:3000/users


## Create a fresh app

Using the Express create app CLI.

See more info on the [Expression generator](https://expressjs.com/en/starter/generator.html) in the docs.

### Use NPX

Run the quickstart template generator. You can run this without installing it first.

```sh
$ npx express-generator
```

e.g.

```sh
$ mkdir my-app
$ cd my-app
$ npx express-generator
```

Or

```sh
$ npx express-generator my-app
$ cd my-app
```

### Use NPM

For _earlier_ versions of Node.js, install globally and then run.

```sh
$ npm install -g express-generator
```

```sh
$ express .
```

### Config options

You can choose a view engine.

- Default: `jade`
- Options: `ejs|hbs|hjs|jade|pug|twig|vash`
- Example: `--view=pug`

See the [Pug.js](https://pugjs.org/) homepage for how to use `.pug` files.


## Dev notes

The `main` field does not seem to serve a purpose but it was added by the template I think so I've left it.

The entrypoint ends up actually being `src/bin/www` as per the `start` script command.


## Resources

- [Express.js](https://expressjs.com/) homepage
- [Node.js (Express) with TypeScript, Eslint, Jest, Prettier and Husky - Part 1](https://dev.to/ornio/node-js-express-with-typescript-eslint-jest-prettier-and-husky-part-1-1lin) blog post


## Related projects

- [![MichaelCurrin - express-rest-quickstart](https://img.shields.io/static/v1?label=MichaelCurrin&message=express-rest-quickstart&color=blue&logo=github)](https://github.com/MichaelCurrin/express-rest-quickstart)
- [![MichaelCurrin - node-project-template](https://img.shields.io/static/v1?label=MichaelCurrin&message=node-project-template&color=blue&logo=github)](https://github.com/MichaelCurrin/node-project-template)


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
