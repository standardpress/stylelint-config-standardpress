# stylelint-config-standardpress

[![npm version](https://img.shields.io/npm/v/stylelint-config-standardpress.svg)](https://npmjs.com/package/stylelint-config-standardpress)
[![travis-ci build status](https://travis-ci.com/standardpress/stylelint-config-standardpress.svg?branch=master)](https://travis-ci.com/standardpress/stylelint-config-standardpress)
[![appveyor build status](https://ci.appveyor.com/api/projects/status/ygxptjl6u9450761/branch/master?svg=true)](https://ci.appveyor.com/project/jasonnam/stylelint-config-standardpress/branch/master)

stylelint shareable config by StandardPress.

## Installation

### install-peerdeps

Install with [`install-peerdeps`](https://npmjs.com/package/install-peerdeps):

```sh
npx install-peerdeps --dev stylelint-config-standardpress
```

### npm

Install with npm:

```sh
npm install --save-dev stylelint-config-standardpress
```

Next, install the correct versions of each package, which are listed by the command:

```sh
npm info "stylelint-config-standardpress@latest" peerDependencies
```

## Usage

### CSS

Extend stylelint config with `stylelint-config-standardpress/css`.

```json
{
  "extends": "stylelint-config-standardpress/css"
}
```

### Sass

Extend stylelint config with `stylelint-config-standardpress/scss`.

```json
{
  "extends": "stylelint-config-standardpress/scss"
}
```

## License

stylelint-config-standardpress is released under the MIT license. [See LICENSE](https://github.com/standardpress/stylelint-config-standardpress/blob/master/LICENSE) for details.
