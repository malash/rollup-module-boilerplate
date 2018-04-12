# A Rollup Module Boilerplate

## Clone

Run `git clone https://github.com/malash/rollup-module-boilerplate.git`

## Select branch

Select branch, like `git checkout module`. All branch here:

| Branch | Usage |
| - | - |
| `module` | Release a plain JavaScript NPM module |
| `react` | Release a React Component NPM module |

## Git

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

All files could be rewrite, like `.babelrc` / `.eslintrc` and so on.
