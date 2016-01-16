# Welcome ng2 modules coordination repository

# List of modules:
<!-- name, repo link, npm bange, demo link -->
<!-- should be sorted in alphabed order -->
- Bootstrap 3 and 4 components written in pure Angular2 [ng2-bootstrap](https://github.com/valor-software/ng2-bootstrap) [![npm version](https://badge.fury.io/js/ng2-bootstrap.svg)](http://badge.fury.io/js/ng2-bootstrap) [![github stars](https://img.shields.io/github/stars/valor-software/ng2-bootstrap.svg?style=social&label=Star)](https://github.com/valor-software/ng2-bootstrap)
- [ng2-charts](https://github.com/valor-software/ng2-charts) [![npm version](https://badge.fury.io/js/ng2-charts.svg)](http://badge.fury.io/js/ng2-charts)
- [ng2-dragula](https://github.com/valor-software/ng2-dragula) [![npm version](https://badge.fury.io/js/ng2-dragula.svg)](http://badge.fury.io/js/ng2-dragula)
- [ng2-file-upload](https://github.com/valor-software/ng2-file-upload) [![npm version](https://badge.fury.io/js/ng2-file-upload.svg)](http://badge.fury.io/js/ng2-file-upload)
- [ng2-google-maps](https://github.com/valor-software/ng2-google-maps) [![npm version](https://badge.fury.io/js/ng2-google-maps.svg)](http://badge.fury.io/js/ng2-google-maps)
- [ng2-grid](https://github.com/valor-software/ng2-grid) [![npm version](https://badge.fury.io/js/ng2-grid.svg)](http://badge.fury.io/js/ng2-grid)
- [ng2-handsontable](https://github.com/valor-software/ng2-handsontable) [![npm version](https://badge.fury.io/js/ng2-handsontable.svg)](http://badge.fury.io/js/ng2-handsontable)
- [ng2-infinite-scroll](https://github.com/valor-software/ng2-infinite-scroll) [![npm version](https://badge.fury.io/js/ng2-infinite-scroll.svg)](http://badge.fury.io/js/ng2-infinite-scroll)
- [ng2-progress](https://github.com/valor-software/ng2-progress) [![npm version](https://badge.fury.io/js/ng2-progress.svg)](http://badge.fury.io/js/ng2-progress)
- [ng2-select](https://github.com/valor-software/ng2-select) [![npm version](https://badge.fury.io/js/ng2-select.svg)](http://badge.fury.io/js/ng2-select)
- [ng2-table](https://github.com/valor-software/ng2-table) [![npm version](https://badge.fury.io/js/ng2-table.svg)](http://badge.fury.io/js/ng2-table)
- [ng2-tap](https://github.com/valor-software/ng2-tap) [![npm version](https://badge.fury.io/js/ng2-tap.svg)](http://badge.fury.io/js/ng2-tap)
- [ng2-xeditable](https://github.com/valor-software/ng2-xeditable) [![npm version](https://badge.fury.io/js/ng2-xeditable.svg)](http://badge.fury.io/js/ng2-xeditable)
 
# ng2 modules end goal vision

**IMPORTANT**: All of the written above is perfect vision of end result, don't take it serious from the start:)

**NOTE**: 90% of requirments will be solved by unified compilation of source code, docs, gh-pages

1. Consistency with Angular2
  1. semver consistency (1 to 1)
  2. delivy consistency (es5 commonjs as npm, ts near to js, systemjs bundles)
  3. availability (npm, jspm)
2. Modularity
  1. If module consists of severaly independant components, 
    each component should be required independently
  2. if module includes of js\html\css, should be availabale versions: js, js+html, js+html+css
3. Contributions are welcome:)
4. Feature request, create and issue or PR to specific module
5. Module request, create an issue or PR to this [ng2-plans](https://github.com/valor-software/ng2-plans/issues/new) repo
6. Code and style guide: should be consistent across all ng2 projects (tslint\eslint)
7. Guide lines will be centralized in [link](https://github.com/valor-software/valor-style-guides)
8. Open source initiative: 
  1. ng2-core team will have access to all ng2 projects, 
  2. if needed, per module will be creaded teams with granted `Team maintainer`
9. Required badges:
  1. NPM version [![Npm Version](https://badge.fury.io/js/ng2-bootstrap.svg)](http://badge.fury.io/js/ng2-bootstrap)
  2. Npm Downloads [![npm downloads](https://img.shields.io/npm/dm/ng2-bootstrap.svg)](https://npmjs.org/ng2-bootstrap)
  2. CI build status [![Build Status](https://travis-ci.org/ng2-bootstrap/ng2-bootstrap.svg?branch=master)](https://travis-ci.org/ng2-bootstrap/ng2-bootstrap) 
  3. Test Coverage [![Test Coverage](https://codeclimate.com/github/valor-software/angular2-bootstrap/badges/coverage.svg)](https://codeclimate.com/github/valor-software/angular2-bootstrap/coverage)
  4. Code quality [![Code Climate](https://codeclimate.com/github/valor-software/ng2-bootstrap/badges/gpa.svg)](https://codeclimate.com/github/valor-software/ng2-bootstrap) or Bithound [![bitHound Overall Score](https://www.bithound.io/github/valor-software/ng2-bootstrap/badges/score.svg)](https://www.bithound.io/github/valor-software/ng2-bootstrap)
  5. Gitter chat link (to [![Join the chat at https://gitter.im/valor-software/ng2-bootstrap](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/valor-software/ng2-bootstrap?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge))
  6. Dependencies status production and development [![Dependency Status](https://david-dm.org/valor-software/ng2-bootstrap.svg)](https://david-dm.org/valor-software/ng2-bootstrap) [![devDependency Status](https://david-dm.org/valor-software/ng2-bootstrap/dev-status.svg)](https://david-dm.org/valor-software/ng2-bootstrap#info=devDependencies)
  7. Sauce Test Status [![Sauce Test Status](https://saucelabs.com/browser-matrix/angular2-ci.svg)](https://saucelabs.com/u/angular2-ci)
  8. Waffle.io throughput tasks board [![Throughput Graph](https://graphs.waffle.io/valor-software/ng2-bootstrap/throughput.svg)](https://waffle.io/valor-software/ng2-bootstrap/metrics)
10. CI build should lint, unit test and run Open Sauce UI tests
11. Only angular2 native code (no 3rd party dependecies except integration modules like ng2-chars, ng2-dragula,...)
  *NOTE*: could be exceptions like `moment.js` for datepickers, calendar
12. Modules required to work should be in peer dependencies (like angular2, moment, es6-shim)



