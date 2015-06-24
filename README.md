## Neon animated pages example

> Polymer 1.0

### Included out of the box:

* [Polymer](http://polymer-project.org), [Paper](https://elements.polymer-project.org/browse?package=paper-elements) and [Iron](https://elements.polymer-project.org/browse?package=iron-elements) elements
* [Material Design](http://www.google.com/design/spec/material-design/introduction.html) layout 
* Routing with [Page.js](https://visionmedia.github.io/page.js/)
* Offline-first setup through [Platinum](https://elements.polymer-project.org/browse?package=platinum-elements) Service Worker elements
* End-to-end Build Tooling (including [Vulcanize](https://github.com/Polymer/vulcanize))

## Getting Started

To take advantage of Polymer Starter Kit you need to:

1. Get a copy of the code.
2. Install the dependencies if you don't already have them.
3. Modify the application to your liking.
4. Deploy your production code.

### Get the code

[Download](https://github.com/polymerelements/polymer-starter-kit/releases/latest) and extract Polymer Starter Kit to where you want to work.

The standard version of Polymer Starter Kit comes with tools that are very handy when developing a Polymer app. If you'd like to get started without installing any new tools, see Polymer Starter Kit Light in the [Releases](https://github.com/polymerelements/polymer-starter-kit/releases/latest) page.

### Install dependencies

#### Quick-start (for experienced users)

With Node.js installed, run the following one liner from the root of your Polymer Starter Kit download:

```sh
npm install -g gulp bower && npm install && bower install
```

#### Prerequisites (for everyone)

The full starter kit requires the following major dependencies:

- Node.js, used to run JavaScript tools from the command line.
- npm, the node package manager, installed with Node.js and used to install Node.js packages.
- gulp, a Node.js-based build tool.
- bower, a Node.js-based package manager used to install front-end packages (like Polymer).

**To install dependencies:**

1)  Check your Node.js version.

```
node --version
```

The version should be at or above 0.12.x. 

2)  If you don't have Node.js installed, or you have a lower version, go to [nodejs.org](https://nodejs.org) and click on the big green Install button. 

3)  Install `gulp` and `bower` globally.

```sh
npm install -g gulp bower
```

This lets you run `gulp` and `bower` from the command line.

4)  Install the starter kit's local `npm` and `bower` dependencies.

```sh
cd polymer-animation-example && npm install && bower install
```

This installs the element sets (Paper, Iron, Platinum) and tools the starter kit requires to build and serve apps.

### Development workflow

#### Serve / watch

```
gulp serve
```

This outputs an IP address you can use to locally test and another that can be used on devices connected to your network.

#### Build & Vulcanize

```
gulp
```

Build and optimize the current project, ready for deployment. This includes linting as well as vulcanization, image, script, stylesheet and HTML optimization and minification.


## Yeoman support

[generator-polymer](https://github.com/yeoman/generator-polymer/releases) now includes support for Polymer Starter Kit out of the box.

