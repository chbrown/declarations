# declarations

[DefinitelyTyped](https://github.com/borisyankov/DefinitelyTyped) as an [`npm`](https://www.npmjs.com/) package.

An experiment in using the new module resolution strategies in [TypeScript 1.6](http://blogs.msdn.com/b/typescript/archive/2015/09/16/announcing-typescript-1-6.aspx).


## Omissions

The following directories are massive (1MB+), so I exclude them from the npm package:

* `angular2/`
* `devextreme/`
* `dojo/`
* `extjs/`
* `mendixmodelsdk/`
* `sencha_touch/`
* `winrt/`


## Instructions

This is a fork of [DefinitelyTyped](https://github.com/borisyankov/DefinitelyTyped), so it should be trivial to merge in updates.

    git remote add upstream https://github.com/DefinitelyTyped/DefinitelyTyped.git
    git pull upstream master

Then just confirm the default merge message, set a version, and publish.

    npm version patch
    git push
    git push --tags
    npm publish


## License

This source code is distributed under the MIT License.
