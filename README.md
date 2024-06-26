# minimal-line-coverage-with-tsx

An absolutely bare minimum setup for getting line coverage working with [c8](https://www.npmjs.com/package/c8), [Mocha](https://www.npmjs.com/package/mocha), [TypeScript](https://www.npmjs.com/package/typescript), and `package.json`'s [`"type": "module"`](https://nodejs.org/docs/latest-v13.x/api/esm.html#esm_package_json_type_field).

Turns out this is actually quite simple. Similarly simple setups with [nyc](https://www.npmjs.com/package/nyc) simply do not work (they report wildly inaccurate line numbers).

## How to use

1. clone the repo
2. run `npm i`
3. run `npm test`