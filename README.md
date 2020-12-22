# Rebuilding frontend frameworks from scratch

> Featuring - Alpine, React, AngularJS, Vue, Redux, Styled Components

This repo will try to reproduce a minimal working version of each framework by building a [reactive counter example](https://webcomponents.dev/blog/all-the-ways-to-make-a-web-component/).

The core components of a reactive framework:

- We keep track of some data
- When data changes, refresh the DOM

### Frameworks

| Framework      | Library Source                           | App Source                               | Demo                                                          |
| -------------- | ---------------------------------------- | ---------------------------------------- | ------------------------------------------------------------- |
| Alpine         | [`alpine.js`](./alpine/alpine.js)        | [`index.html`](./alpine/index.html)      | [Example](https://tehkaiyu.github.io/frameworks/alpine/)      |
| React          | [`react.js`](./react/react.js)           | [`index.html`](./react/index.html)       | [Example](https://tehkaiyu.github.io/frameworks/react/)       |
| React w/ Fiber | [`react.js`](./react-fiber/react.js)     | [`index.html`](./react-fiber/index.html) | [Example](https://tehkaiyu.github.io/frameworks/react-fiber/) |
| AngularJS      | [`angular.js`](./angularjs/angularjs.js) | [`index.html`](./angularjs/index.html)   | [Example](https://tehkaiyu.github.io/frameworks/angularjs/)   |
