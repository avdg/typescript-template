# typescript-template
Basic typescript project

# Requirements
- Node and npm, which are bundled in one installer that can be found on http://nodejs.org/

# Install

- Run `npm install` To install dependencies
- Run `npm install -g webpack` To install webpack
- After the dependencies and webpack are installed, use `webpack` to build the project.
  You can use `webpack --watch` to keep the command active on the background.
  The program will detect changes in the filesystem and rebuild the project when that happens.

# Writing code

- Write code in `src/`
- Use [import](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)
  and [export](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export)
  statements to split up your javascript/typescript code.
- `src/main.ts` or `src/main.js` is the file that will be executed first with
  this setup. Other files are only executed by importing these files.

# Testing / running code
- After `webpack` or `webpack --watch` is running and compiling without errors,
  an (updated) js file will appear in `dist/main.js` with the current settings.
  This is your export file and contains all code that is consumed by
  `src/main.ts` or `src/main.js`. This file is your final product.

Enjoy!
