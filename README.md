# OpenAPI Directory Lite

> Lite version of [OpenAPI Directory](https://github.com/APIs-guru/openapi-directory) API 
> edited to contain Swedish Open Banking & PSD2 APIs only

## Features

* published via GitHub pages from master branch
* entry point: https://openbankingse.github.io/openapi-directory-lite/index.json
* JSON specs only (YAML is smaller, but not gzipped on GitHub pages), latest version of API only
* github.io CORS
* JavaScript API for spec api paths construction, see [index.js](./index.js) and [data.js](./data.js)
* ++ # specs
* full text search test page: https://darosh.github.io/openapi-directory-lite/search/ 

## Building

```bash
# Download APIs-guru/openapi-directory to node_modules
$ npm run init

# Build specs
$ npm run specs

# Build search index
$ npm run search:docs
$ npm run search:docs:preprocess
$ npm run search:index
```
