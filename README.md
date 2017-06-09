# ztocosiummodule
[![Build Status](https://travis-ci.org/mouss2010/ztocosiummodule.svg?branch=master)](https://travis-ci.org/mouss2010/ztocosiummodule)
[![codecov](https://codecov.io/gh/mouss2010/ztocosiummodule/branch/master/graph/badge.svg)](https://codecov.io/gh/mouss2010/ztocosiummodule)
[![npm version](https://badge.fury.io/js/ztocosiummodule.svg)](http://badge.fury.io/js/ztocosiummodule)
[![devDependency Status](https://david-dm.org/mouss2010/ztocosiummodule/dev-status.svg)](https://david-dm.org/mouss2010/ztocosiummodule?type=dev)
[![GitHub issues](https://img.shields.io/github/issues/mouss2010/ztocosiummodule.svg)](https://github.com/mouss2010/ztocosiummodule/issues)
[![GitHub stars](https://img.shields.io/github/stars/mouss2010/ztocosiummodule.svg)](https://github.com/mouss2010/ztocosiummodule/stargazers)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/mouss2010/ztocosiummodule/master/LICENSE)

## Demo
https://mouss2010.github.io/ztocosiummodule/

## Table of contents

- [About](#about)
- [Installation](#installation)
- [Documentation](#documentation)
- [Development](#development)
- [License](#license)

## About



## Installation

Install through npm:
```
npm install --save ztocosiummodule
```

Then include in your apps module:

```typescript
import { Component, NgModule } from '@angular/core';
import { ZtocosiummoduleModule } from 'ztocosiummodule';

@NgModule({
  imports: [
    ZtocosiummoduleModule.forRoot()
  ]
})
export class MyModule {}
```

Finally use in one of your apps components:
```typescript
import { Component } from '@angular/core';

@Component({
  template: '<hello-world></hello-world>'
})
export class MyComponent {}
```

You may also find it useful to view the [demo source](https://github.com/mouss2010/ztocosiummodule/blob/master/demo/demo.component.ts).

### Usage without a module bundler
```
<script src="node_modules/ztocosiummodule/bundles/ztocosiummodule.umd.js"></script>
<script>
    // everything is exported ztocosiummodule namespace
</script>
```

## Documentation
All documentation is auto-generated from the source via [compodoc](https://compodoc.github.io/compodoc/) and can be viewed here:
https://mouss2010.github.io/ztocosiummodule/docs/

## Development

### Prepare your environment
* Install [Node.js](http://nodejs.org/) and NPM
* Install local dev dependencies: `npm install` while current directory is this repo

### Development server
Run `npm start` to start a development server on port 8000 with auto reload + tests.

### Testing
Run `npm test` to run tests once or `npm run test:watch` to continually run tests.

### Release
* Bump the version in package.json (once the module hits 1.0 this will become automatic)
```bash
npm run release
```

## License

MIT
