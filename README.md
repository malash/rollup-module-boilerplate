# A Rollup Module Boilerplate

Supported features:

* Use [Rollup](https://github.com/rollup/rollup) .
* Support babel `stage-0` (can be customized).
* Auto replacing `NODE_ENV`
* Resolve [Node.js module](https://github.com/rollup/rollup-plugin-commonjs)
* Show bundle [file size](https://github.com/ritz078/rollup-plugin-filesize)
* Output `es` / `cjs` / `umd` and minified versions.
* Use [AVA](https://github.com/avajs/ava) for tests.
* Support React and [jsdom](https://github.com/jsdom/jsdom) (in `react` branch).

## Clone

Run `git clone https://github.com/malash/rollup-module-boilerplate.git`

## Select branch

Select branch, like `git checkout module`. All branch here:

| Branch | Usage |
| - | - |
| `module` | Release a plain JavaScript NPM module |
| `react` | Release a React Component NPM module |

## Init Git

Run `rm -rf ./.git` and `git init` to init a new repo.

## Files

Normally, you need to change these files:

| File | Content |
| - | - |
| `package.json` | All `rollup-module-boilerplate` / `author` / `license` |
| `LICENSE` | Your name and email |
| `src/*` | Your source code here |
| `test/*` | Your test code here |

## Development

Run `npm run dev` .

## Publish

Run `npm run build` and `npm publish` .

More `npm` script in `package.json`.

## Other files

All files could be rewrite, like `README.md` / `.babelrc` / `.eslintrc` and so on.
