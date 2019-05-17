# typescript-template
Basic typescript project

[![Dependency Status](https://david-dm.org/avdg/typescript-template.svg)](https://david-dm.org/avdg/typescript-template)
[![Dev dependency Status](https://david-dm.org/avdg/typescript-template/dev-status.svg)](https://david-dm.org/avdg/typescript-template?type=dev)

# Requirements
- Node and npm, which are bundled in one installer that can be found on http://nodejs.org/

# Install

- Run `npm install` to install dependencies.

# Writing code

- Write code in `src/`
- Use [import](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)
  and [export](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export)
  statements to split up your javascript/typescript code.
- `src/main.ts` or `src/main.js` is the file that will be executed first with
  this setup. Other files are only executed by importing these files.

# Testing / running code

- Make sure `npm start` is running.
- After compiling without errors, an (updated) js file will appear in `dist/main.js`.
  This is your export file and contains all code that is consumed by `src/main.ts`
  or `src/main.js`. The `dist/main.js` file is your final product.

Enjoy!
