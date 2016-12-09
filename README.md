# <test-test>

`test-test` is a standalone web-app built with [Polymer](https://www.polymer-project.org/).

## Developement environment

This project requires **[npm](https://www.npmjs.com/)** and **[bower](https://bower.io/#install-bower)** to be installed.

### Setup

```bash
$ npm install && bower update
```

### Run

```bash
$ npm start
```
_default port is 8080_

### Production

Create a dist version of the project with vulcanize. This will inline all HTML imports, thus reducing the number require network requests.

```bash
$ npm run build
```

### Test

Run tests from console/terminal
```bash
$ npm test
```

Run wct tests in browser with locally hosted content.
[http://localhost:8080/test-test/test/index.html](http://localhost:8080/test-test/test/index.html)

## Resources

* [Polymer](https://www.polymer-project.org/)
* [WebComponents](http://webcomponents.org/)
* [Web Component Tester](https://github.com/Polymer/web-component-tester)
* [Vulcanize](https://www.npmjs.com/package/vulcanize)