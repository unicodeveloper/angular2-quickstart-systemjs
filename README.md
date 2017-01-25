# angular2-quickstart SystemJS

This repo is a quickstart for starting your Angular 2 apps with SystemJS. All the settings and config you need to kickstart your application is here.

# Quick start

Clone this repo `npm start` and you are ready to start hacking!

## How to add an angular 2 module/package like ng2-file-upload to your project

In the `map` section of the `systemjs.config.js` file:

Add `ng2-file-upload` like so:

```js
  ...
  'ng2-file-upload':             'npm:ng2-file-upload',
  ...
```

Now go to the `packages` section and Add them like so:

```js
 ...
 'ng2-file-upload': { main: 'ng2-file-upload.js', defaultExtension: 'js' }
 ...

```

Done.

Good luck with Angular 2 hacking!