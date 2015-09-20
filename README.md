# Boilerplate for modern JS libraries

This boilerplate allows you to get up an running quickly when developing modern,
ES6-based JavaScript library or app. It comes baked in with

- Babel
- Browserify
- Make

and takes care of tying them together. That’s it, nothing else.

## Dependencies

Node, NPM, and Make.

## Getting Started

All your code should go into `/src`, with `/src/app.js` being the main entry
point for your application. Put all your `import`s there.

## Bundling Your Code

Run

```
$ make
```

Then check `dist/app.js` for the fully compiled version of your code.

There is also

```
$ make watch
```

that will watch all your source files and automatically re-build your code.
It uses the Chokidar NPM plugin rather than something like
[Watchr](https://github.com/mynyml/watchr) or even
[Watchman](https://facebook.github.io/watchman/) to keep the dependencies
limited to Node.js.
Feel free to swap this out in favor of your preferred solution.

## Feedback

Issues, Pull Requests, or [@jkintscher](https://twitter.com/jkintscher).
