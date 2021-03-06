[![Version](http://img.shields.io/npm/v/create-ecma-app.svg)](https://www.npmjs.org/package/create-ecma-app) [![Build Status](https://travis-ci.org/tacnoman/create-ecma-app.svg?branch=master)](https://travis-ci.org/tacnoman/create-ecma-app) [![Code Climate](https://codeclimate.com/github/tacnoman/create-ecma-app/badges/gpa.svg)](https://codeclimate.com/github/tacnoman/create-ecma-app) [![codecov](https://codecov.io/gh/tacnoman/create-ecma-app/branch/master/graph/badge.svg)](https://codecov.io/gh/tacnoman/create-ecma-app) [![HitCount](http://hits.dwyl.io/tacnoman/create-ecma-app.svg)](http://hits.dwyl.io/tacnoman/create-ecma-app)


# Create Ecma App

This project is like a create-react-app. Everybody knows that install and configure Babel is boring.

This boilerplate uses the last version of babel and create a small vanilla project using Ecma features.

<p align="center">
  <img src="https://github.com/tacnoman/create-ecma-app/blob/master/images/demo.gif?raw=true" width="600" alt="create ecma app command">
</p>


## Create your own project

To create your project you only must run:

```bash
  $ npx create-ecma-app my-app-name
  $ cd my-app-name
```

And now you have a node with ecma features working.

### Options to create your project

The create-ecma-app will generate the project with default params, but you can set
passing params in terminal.

```bash
Usage: create-ecma-app <project-name> [options]

Options:
  -V, --version                    output the version number
  -v, --verbose                    print additional logs
  -d, --description [description]  description to project
  -a, --author [author]            author of the project
  --ask-me                         the create-ecma-app will ask about props
                                   in generation
  -h, --help                       output usage information
    Only <project-name> is required.
```

## Commands in project generated

In your project you have the commands:

| Command       | Description                                              |
|---------------|----------------------------------------------------------|
| start         | Start the project in production mode (must build before) |
| build         | Build the project in `dist` folder                       |
| build:web     | Build the project in `dist` folder to run in browser     |
| dev           | Run in development mode with watcher                     |
| exec          | Run the code in `src` folder once without build          |
| lint          | Run lint validator using Airbnb lint pattern             |
| lint:fix      | Run lint validator and fix some bugs if exists           |
| test          | Run tests using jest                                     |
| test:coverage | Run tests using jest and return the coverage code        |
| validate      | Run tests and lint (ideal to CI)                         |

You can run with `npm run` or `yarn`.
Ps: If yarn exists in your machine, the installation will use instead of npm
