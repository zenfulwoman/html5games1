# HTML5 Games: Novice to Ninja

![HTML5 Games](https://user-images.githubusercontent.com/129330/36218826-9cdf69a0-1183-11e8-9822-a92fdc6cd9ac.png)

Welcome to the [HTML5 Games: Novice to Ninja](https://www.sitepoint.com/premium/books/html5games1) code examples.

Most of the examples (anything after chapter 03, example 06) use JavaScript native modules. If you are reading this in the future, then JavaScript modules are well supported by all browsers, and you can run any of the examples by viewing the `index-native.html` file.

[Try the examples](https://spbooks.github.io/html5games1/). [under construction.gif].

They should run in all recent browsers (for Firefox it's enabled behind the about:config `dom.moduleScripts.enabled` flag). If you want to run them locally you need to serve the example via web browser (JavaScript modules will only work via `http://` and not `file://` - so you can't just double-click and run it). There is a webserver in the root directory that you can install and run (via `npm`) with:

```
npm install
npm start
```

This will run a server on http://localhost:9966/. If you browse here there will be links to each example (eventually! For now you will have to type the full URL. eg, `http://localhost:9966/ch04/05-rotate/index-native.html`).

## Without JavaScript Module support

If your browser doesn't yet support native modules, every example directory also has its own `package.json` file. For *every* example you will have to install and run:

```
npm install
npm start
```

The example will be transpiled via Babel (into old days JavaScript) and a server will run (at http://localhost:9966 by default).

## Building an example

Each example package also includes a `npm run build` command that will transpile the JavaScript into a single `build.js` file that can be run with the included `index.html` file, and deployed to servers etc.


## Examples to come

I'm organizing the code for each chapter. There's still a little tidying going on. Also, still remaining:

```
ch09/01-02,05-10
```
