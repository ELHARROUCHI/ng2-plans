# Welcome ng2 modules coordination repository

# List of modules:
<!-- name, repo link, npm bange, demo link -->
<!-- should be sorted in alphabed order -->
- [ng2-bootstrap](https://github.com/valor-software/ng2-bootstrap) [![npm version](https://badge.fury.io/js/ng2-bootstrap.svg)](http://badge.fury.io/js/ng2-bootstrap)
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
  2. delivy consistency (es5 commonjs, es6, ts, systemjs)
  3. availability (npm, jspm, bower...)
2. Modularity
  1. If module consists of severaly independant components, 
    module should be able to get only required component from module
  2. if module includes of js\html\css, should be availabale versions: js, js+html, js+html+css
3. Contributions are welcome:)
4. Feature request, create and issue or PR to specific module
5. Module request, create an issue or PR to this(ng2-plans) repo
6. Code and style guide: should be consistent across all ng2 projects (including tslint)
7. Guide lines will be centralized in [link](https://github.com/valor-software/valor-style-guides)
8. Open source initiative: 
  1. ng2-core team will have access to all ng2 projects, 
  2. if needed, per module will be creaded teams with granted `Team maintainer` and outside collaborators
9. Testability [codeclimate](https://codeclimate.com) badges should be present, coverage > 90%
10. CI (travis or codeship)
11. Only angular2 native code (no 3rd party dependecies except integration modules like ng2-chars, ng2-dragula,...)
  *NOTE*: could be exceptions like `moment.js` for datepickers, calendar
12. Badges: npm version, dependencies, codeclimat (rank and coverage, hope they will add typescript soon), build status



