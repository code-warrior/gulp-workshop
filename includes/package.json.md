
---

## The `package.json` File

Information about a Node project is saved in a manifest file called `package.json`.  It’s required by your Gulp projects.

---

## The `package.json` File

You may write this file by hand, or have Node create it for you interactively with the `init` option to the `npm` program:

        npm init

---

## The `package.json` File
### Saving modules/plugins

For just about every one of your projects, you’ll need to use modules, or plugins. (As of this writing, there are [2,483 Gulp plugins](http://gulpjs.com/plugins/).)

Any non-Node module you use needs to be listed in the `package.json` file and included in the `node_modules` folder, which will be explained in a moment.

---

## The `package.json` File
### Saving modules/plugins

The easiest way to update `package.json` and to download a module into the `node_modules` folder is to run the `npm install` command with the `--save-dev` flag. Let’s download an HTML compressor module:


        npm install --save-dev gulp-html-minifier

The `--save-dev` flag will be explained later.


