# Projekt-dodatkowy-7.7

Dziś nie wiem dalczego przy testowaniu plików pojawia się taki dziwny komunikat o błędzie.

$ npm run build

> projekt-dodatkowy-7.7@1.0.0 build C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7
> npm-run-all build:* test


> projekt-dodatkowy-7.7@1.0.0 build:clean C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7
> rimraf css/*


> projekt-dodatkowy-7.7@1.0.0 build:sass C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7
> node-sass --output-style compact -o css sass

Rendering Complete, saving .css file...
Wrote CSS to C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7\css\style.css
Wrote 1 CSS files to C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7\css

> projekt-dodatkowy-7.7@1.0.0 build:autoprefixer C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7
> autoprefixer-cli css/style.css

[Browsersync] File event [change] : css\style.css

> projekt-dodatkowy-7.7@1.0.0 test C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7
> npm-run-all test:*


> projekt-dodatkowy-7.7@1.0.0 test:html C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7
> globstar nu-html-checker *.html

C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7\node_modules\nu-html-checker\lib\formatters\stylish.js:40
  if (!list.length) return chalk.green('No validation errors found!');
            ^

TypeError: Cannot read property 'length' of undefined
    at body (C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7\node_modules\nu-html-checker\lib\formatters\stylish.js:40:13)
    at module.exports (C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7\node_modules\nu-html-checker\lib\formatters\stylish.js:17:26)
    at Object.module.exports [as format] (C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7\node_modules\nu-html-checker\lib\formatters\index.js:5:10)
    at Batch.<anonymous> (C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7\node_modules\nu-html-checker\bin\cli:31:26)
    at emitOne (events.js:116:13)
    at Batch.emit (events.js:211:7)
    at callback (C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7\node_modules\batch\index.js:132:12)
    at C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7\node_modules\nu-html-checker\lib\validate.js:56:5
    at Request.callback (C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7\node_modules\superagent\lib\node\index.js:746:30)
    at Request.<anonymous> (C:\Kurs kodilla\Zadania\Projekt-dodatkowy-7.7\node_modules\superagent\lib\node\index.js:135:10)
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! projekt-dodatkowy-7.7@1.0.0 test:html: `globstar nu-html-checker *.html`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the projekt-dodatkowy-7.7@1.0.0 test:html script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Jacek Sańko\AppData\Roaming\npm-cache\_logs\2018-02-22T16_34_18_499Z-debug.log
ERROR: "test:html" exited with 1.
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! projekt-dodatkowy-7.7@1.0.0 test: `npm-run-all test:*`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the projekt-dodatkowy-7.7@1.0.0 test script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Jacek Sańko\AppData\Roaming\npm-cache\_logs\2018-02-22T16_34_18_538Z-debug.log
ERROR: "test" exited with 1.
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! projekt-dodatkowy-7.7@1.0.0 build: `npm-run-all build:* test`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the projekt-dodatkowy-7.7@1.0.0 build script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Jacek Sańko\AppData\Roaming\npm-cache\_logs\2018-02-22T16_34_18_568Z-debug.log
